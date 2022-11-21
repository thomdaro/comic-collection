---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid=comic001 %}

{% include feature/nav-menu.html sections="The Collection;The Staff;Acknowledgements;Standards;Rights" %}

## The Collection

Through the entirety of the 90s and into the 2000s, my grandfather was an avid collector of comic books. As a child, I would read through his collection, picking out issues that caught my eye. Noticing my interest, he decided that it should be passed down to my parents, and then to me. This site documents only a small portion of the 374 comics present in it, though I fully intend to put the collection online in its entirety, eventually. It contains a number of series from Marvel, DC, and Dark Horse, and features many significant characters, storylines, and spinoffs. My grandfather continues to express his love for these characters and stories today, as he's a huge fan of the Marvel Cinemantic Universe and its silver screen adaptations of the elements that made these comic books great.

Despite the age of this collection, I've never really spoken to him about the rationale behind what he chose to collect. It's clear that there are patterns present – the same series purchased several months in a row, all the issues of a limited run bundled together, lines that span multiple series diligently accounted for. In documenting and identifying the characteristics of this collection, I hope to make some inferences about what exactly these patterns are, connect those purchases to the larger cultural conversation around certain characters or publishers at the time, and ideally give my grandfather a new and exciting way to peruse his decades-old collection, even when it is not physically present.

## The Staff

Damien Thomas is a graduate student at Indiana University in Bloomington, currently obtaining a dual Master's in Information and Library Science. His undergraduate work was split evenly between Computer Science and Religious Studies, and this love of both technology and the humanities has greatly influenced his professional work in archives (public and corporate), film and audio preservation, and research on large digital library projects. In his free time, he enjoys video games, cooking new soups and stews, programming, and contributing to wikis for obscure and nearly-forgotten games.

## Acknowledgements

I'd like to thank my grandfather for not only purhasing this collection in the first place, but for preserving them in beautiful condition for so many years, and of course for passing them down to me for further preservation efforts. 

I'd also like to thank John Walsh and Alex Wingate, the principle educators involved in ILS-Z652 Digital Libraries. Without them, it's unlikely I would've had the idea to document and preserve this collection in this way in the first place. Their support and guidance has been instrumental in shaping this project and my future ambitions for it.  

Lastly, I'd like to thank the fine folks at CollectionBuilder, for providing an intuitive and powerful framework for putting digital collections online, and Github for providing the Pages framework that the site is built on. You can find the CollectionBuilder project [here](https://collectionbuilding.github.io/gh/) and documentation for Github Pages [here](https://pages.github.com/).

## Standards

### Technical

Comic covers were scanned at the Scholar's Commons Digitization Lab at IU's Wells Library – read more about their services [here](https://libraries.indiana.edu/scholars-commons-digitization-lab). Scans were set to output jpegs at custom dimensions for comic book covers (6.55" x 10"), then cropped slightly as needed. The majority of output files are 1965px by 3000px, at a resolution of 300 dpi and bit depth of 24. These parameters were chosen as a compromise between quality and file size – given the the entire collection will eventually be hosted in the Github repository, it is necessary to keep the total size of the Objects folder below 1 GB. The current batch of scans is approximately 50 MB, so the entire collection should only take up ~770 MB when all scans are uploaded.

### Metadata

CollectionBuilder has a few metadata fields that are required for any project (_objectid_, _filename_, _title_, _format_), as well as some optional fields for visualizations (_date_, _subject_). Further reading on those fields can be found [here](https://collectionbuilder.github.io/cb-docs/docs/metadata/gh_metadata/).

The remainder of the field names were selected from the Grand Comics Database. You can read their formatting documentation [here](https://docs.comics.org/wiki/Formatting_Documentation).

## Rights

Given the non-commercial nature of this project, as well as the lack of copyrighted content present, the author believes he has performed due diligence and is confident in asserting that the project falls under Fair Use guidelines.
