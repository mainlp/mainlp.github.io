---
layout: page
permalink: /website-notes/
title: Updating the website
description: 
nav: false
---

## Basic info

To make simple edits to the webpage, all you need to know is that most content is formatted using the [Kramdown](https://kramdown.gettalong.org/quickref.html) flavour of Markdown, and that new pages require YAML headers, as explained below.

Setting up Ruby and Jekyll to preview changes locally before pushing them is encouraged but not necessary, you can also make changes by directly editing the files in the repo and checking the changes once GitHub has updated the website.

Table of contents:
- [Previewing changes locally](#previewing-changes-locally)
- [Repo set-up](#repo-set-up)
- [Adding lab members](#adding-lab-members)
- [Adding events](#adding-events)
- [Adding a new page](#adding-a-new-page)
- [GitHub security alerts](#github-security-alerts)
- [Adding new plug-ins](#adding-new-plug-ins)

## Previewing changes locally

(This is optional.)

1. Install [Ruby and Jekyll](https://jekyllrb.com/docs/installation/#guides).
2. Clone the rep: `git clone git@github.com:mainlp/mainlp.github.io.git` and navigate to the corresponding directory.
3. Run `bundle install` to install all dependencies.
4. To build the site locally, run `bundle exec jekyll serve` and open [http://localhost:4000](http://localhost:4000).

If you make changes to the markdown, HTML, CSS, etc. files, you only need to refresh the page in your browser. For changes to the config or the Gemfile, you need to run the bundle command again.

## Repo set-up

- `_bibliography/` -- currently not used, but could be used to keep track of publications & publication metadata via custom bibtex files
- `_data/` -- currently not used, metadata for different formatting, e.g., publication lists
- `_events/` -- see above
- `_includes/` and `_layouts/` -- (Jekyll-ized) HTML files that dictate the site structure
- `_pages/` -- markdown files for the homepage and subpages; PDFs are currently in the `content` subfolder
- `_plugins/` -- currently not used
- `_sass/` -- style files; the colors are set in `_variables.scss`
- `assets/` -- where pictures live; we could also move the PDFs there
- `bin/` -- deployment scripts, we probably won't need to touch these
- `blog/` -- currently unused
- `_config.yml` -- all the important metadata

## Adding lab members

Edit [_pages/about.md](https://github.com/mainlp/mainlp.github.io/blob/main/_pages/about.md) and add the following to one of the staff sections:

```
    - name: The Name
      description: job title, date
      website: example.com [remove this line if there's no website]
      picture: mainlp-logo-150.png [or replace with name.jpg]
```

To include a picture name.jpg, add it to [assets/img](https://github.com/mainlp/mainlp.github.io/tree/main/assets/img).

To add a new staff section, add its name to the groups list towards the top of the page (`groups: [staff, support, admin, affiliated]`), and then define the new section like, e.g., `staff` is defined:

```
newgroup:
  title: New Group
  people:
  - name: First Last
    description: Job Title
    picture: name.jpg
```

## Adding events

Add a new markdown file `YYYY-MM-DD-short-description.md` to `_events`. This is done most easily by altering a copy of an existing event description. Event descriptions consist simply of YAML frontmatter:

```
---
title: The title
abstract: [optional, remove line if not required for event]
speaker: [optional, remove line if not required for event]
bio: [optional, remove line if not required for event]
website: [optional, remove line if not required for event]
time: Time and date
location: [optional, remove line if not required for event]
roomfinder: Location URL [optional, remove line if not required for event]
img: Path to picture, starting with assets/img/ [optional, remove line if not required for event]
imgalt: Image description [optional, remove line if not required for event]
imgside: 'right' of 'left' (default: 'right')
anchor: YYYY-MM-DD-short-description [same as in file name]
---
```

The location link can be, for instance, to the relevant [LMU room finder](https://www.lmu.de/raumfinder/#/) page.

## Adding a new page

Add a new markdown file to [_pages](https://github.com/mainlp/mainlp.github.io/tree/main/_pages).
It needs to have a YAML header like so:
```
---
layout: page
permalink: /slug-goes-here/
title: New Title
description: [optional]
nav: true [if false, it's not in the navigation bar]
nav_order: 6 [lower = more to the left; leave out if nav==false]
---
```

And then the actual content can follow.

## Adding new plug-ins

1. Add the plug-in to the `plugins` list in [_config.yml](https://github.com/mainlp/mainlp.github.io/blob/main/_config.yml).
2. Add it to the [Gemfile](https://github.com/mainlp/mainlp.github.io/blob/main/Gemfile).
3. Install it:
```
gem install gem-name-here
bundle install
```

## GitHub security alerts

GitHub might occasionally have security alerts concerning the dependencies (currently not a problem since we don't specify the version numbers in our Gemfile at the moment -- this might change in case we need to manually handle version conflicts). Usually, it will suggest a Dependabot PR that immediately solves the issue.
If there's no Dependabot PR, you can typically generate one via the repo's [security tab](https://github.com/mainlp/mainlp.github.io/security). 
You can also do this by hand: add the code suggested by the security alert (`gem "gem-name-here", ">= version.number.here"`) to the [Gemfile](https://github.com/mainlp/mainlp.github.io/blob/main/Gemfile) and update `Gemfile.lock` by running
```
gem install gem-name-here
gem update gem-name-here
bundle update gem-name-here
bundle install
```
