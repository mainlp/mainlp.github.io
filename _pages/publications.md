---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 6
---
<div class="highlight-publications">
<h2 class="category">Selected Publications</h2>
  {% bibliography --file highlights --template highlight --max 2 %}
</div>

<div class="publications">
<h2 class="category">All Publications</h2>
  {% bibliography --file papers --template bib %}
  <button class="show-more" id="show-more-btn">
      Show More
  </button>
</div>


<script>
/*
  Reveal more publications on button click
*/
document.addEventListener('DOMContentLoaded', function() {
  const publicationContainer = document.querySelector('.publications');
  const showMoreBtn = document.getElementById('show-more-btn');
  const publicationItems = publicationContainer.querySelectorAll('.item');
  const numItemsToShow = 10;
  let currentVisibleIndex = 0;

  if (showMoreBtn && publicationContainer) {
    function showMoreItems() {
      const nextVisibleIndex = currentVisibleIndex + numItemsToShow;

      for (let i = currentVisibleIndex; i < nextVisibleIndex && i < publicationItems.length; i++) {
        publicationItems[i].style.display = 'block';
      }

      currentVisibleIndex = nextVisibleIndex;

      if (currentVisibleIndex >= publicationItems.length) {
        showMoreBtn.style.display = 'none';
      }
    }

    showMoreBtn.addEventListener('click', showMoreItems);
    // display first items
    showMoreItems();
    
    // only show button after first items have been displayed
    if (currentVisibleIndex < publicationItems.length) {
        showMoreBtn.style.display = 'block';
    }
    
  }
});
</script>