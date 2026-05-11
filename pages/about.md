---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://cdil.lib.uidaho.edu/images/palouse_sm.jpg" %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## About the Database

Welcome to ShakesReel, an exhaustive, online compendium of films, videos, and series which are adapted from, or inspired by, one or more of the 38 plays written by William Shakespeare. This database gives users a means to curate and search through hundreds of Shakespearean motion-pictures throughout the full 130 years of cinematic history in a variety of ways, most notably via tags, timelines, and maps. As of this moment, the site contains over 380 entrees for five Shakespearean tragedies: Romeo and Juliet, Julius Caesar, Hamlet, King Lear, and Macbeth. Enjoy your visit, and feel free to download the website’s metadata in a reusable format (CSV and JSON files) for alternative use in larger computational studies. Below are some helpful notes for new users:

ShakesReel abides by [DublinCore](https://www.dublincore.org/specifications/dublin-core/dcmi-type-vocabulary/) formatting rules and is thus limited in the ways in which it represents some data. Some pointers users should be aware of when navigating the site and digesting its data:
- The "creator" label is for the director of the adaptation in question, not always the play production that the film captures
- The order that entrees appear in on the timeline is random and not at all the order of release throughout that respective year

Videos:
- ShakesReel uses YouTube videos as "items" due to copyright issues with most film posters. Most videos are trailers. However, if a film or video is available in full for free on YouTube and has not been removed from the platform for violating infringement rules, as is the case with most silent films, video productions, and foreign pictures, it is featured in our collection
- If a YouTube video will not play, it is because the uploader has disabled embedding or restricted video privacy settings. These entrees will be replaced and corrected as they are caught by the site's moderator

Tags:
- The order of information for each work's tags is as follows: adapted play, type of media (e.g., Silent, Feature, Short, Series, TV/Video/Recording), type of adaptation (Faithful/Direct or Loose/Inspired), genres, and actors
- The most famous actors in an adapatation, if not all of them, are listed as the last tags for all entrees. Many are only in one film, but a handful are in several

This site is generated using [CollectionBuilder-GH](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPG images or PDF documents

The template repository features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

For full details of creating your own collection site, visit [CollectionBuilder Documentation](https://collectionbuilder.github.io/cb-docs/)!

