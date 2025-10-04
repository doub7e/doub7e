---
layout: about
title: about
permalink: /
subtitle: Ph.D. student at EPFL (Swiss Federal Technology Institute of Lausanne)

profile:
  align: right
  image: profile.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    shuangqi.li@epfl.ch

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi! I am Shuangqi, a Ph.D. student at EPFL, advised by [Dr. Mathieu Salzmann](https://people.epfl.ch/mathieu.salzmann/) and [Prof. Pascal Fua](https://people.epfl.ch/pascal.fua). My research interests lie in building steerable, reliable and explainable AI. Currently, I am working on scaling up <button type="button" class="btn btn-link p-0 align-baseline tda-popover" data-toggle="popover" data-trigger="focus" data-placement="top" data-html="true" data-content="Training Data Attribution quantifies which training examples most influence a model’s prediction for a given test case.">Training Data Attribution (TDA)</button> so that we can build better LLMs in a data-driven way. If this sounds interesting to you, feel free to reach out and discuss with me!

<script>
window.addEventListener('load', function() {
  if (window.jQuery && typeof jQuery.fn.popover === 'function') {
    jQuery('[data-toggle="popover"]').popover();
  } else if (window.bootstrap && window.bootstrap.Popover) {
    var triggers = document.querySelectorAll('[data-toggle="popover"]');
    Array.prototype.forEach.call(triggers, function(el){
      new bootstrap.Popover(el);
    });
  }
});
</script>
