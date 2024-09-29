---
layout: page
title: Kindle Revenant Project
description: A Qt-based project aimed at suceeding Kindle Mate
img: assets/img/connected.PNG
importance: 1
category: work
related_publications: true
---

<h2>Introduction</h2>
The Kindle provides a useful feature that records words looked up, along with related information such as word stems and usage context, storing this data in a SQLite database. Many users have leveraged this to create flashcards for vocabulary building. Especially for Anki, a spaced repetition software.

Previously, Kindle Mate was a widely-used tool for this purpose, but it is no longer maintained, and the website has been shut down. Therefore, I decided to create an open-source program that aims to replicate and eventually surpass the functionality of Kindle Mate. This tool will also serve as a resource for others pursuing similar goals.

Currently, Kindle Revenant includes the following features:
<ul>
    <li>Creating, maintaining, and displaying a local database that stores Kindle lookup data</li>
    <li>Automatically detecting the Kindle database file location</li>
    <li>Scraping word definitions from online sources</li>
    <li>Exporting words and definitions to a tab-indented .txt file for easy import into Anki</li>
</ul>

<h2>Project Experience</h2>
While I initially anticipated significant challenges due to the variety of new technologies involved, the development process proved more manageable but frustrating at times. All the technologies I worked with were fairly intuitive to use which made it straightforward when it came to implementing most of the functionality. Most technologies were intuitive to implement; however, working with Qt, particularly Qt for Python, was more complex due to its niche nature. The PyQt documentation became an invaluable resource, guiding me through many of the difficulties. Through this project, I have gained valuable experience in:
<ul>
    <li>Adapting to new technologies</li>
    <li>Enhancing my debugging skills</li>
    <li>Effectively utilizing technical documentation</li>
    <li>Setting up a CI/CD pipeline for automated testing and packaging</li>
    <li>Interacting with APIs</li>
    <li>Writing unit tests</li>
</ul>

Although Kindle Revenant has not yet achieved full feature parity with Kindle Mate, I have successfully implemented the majority of the core functionalities I initially set out to develop.

<div class="row">
    <div class="col-sm mt-3 mft-md-0">
        {% include figure.liquid loading="eager" path="assets/img/connected.PNG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Kindle Revenant UI
</div>

{% raw %}
{% endraw %}
