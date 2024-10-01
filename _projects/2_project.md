---
layout: page
title: TechTreausre
description: A full stack web application
img: assets/img/techtreasure_home.png
importance: 2
category: work
related_publications: true
---

<h2>Introduction</h2>
As part of our second-year university team project, we were tasked with developing a full-stack web application using the Django framework. Our team decided to create a simple auction website, specifically aimed at technology enthusiasts. The primary objectives were to design a user-friendly interface, ensure responsiveness across various screen sizes and ratios, and deliver an aesthetically pleasing experience.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/techtreasure_home.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/techtreasure_listing.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/techtreasure_login.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   screenshots of the techtreasure website showcasing different pages
</div>

<h2>Process</h2>
<h3>Planning Stage</h3>
During the planning phase, we developed a detailed outline of our goals and deliverables. We mapped out the pages to be built and created an Entity-Relationship (ER) diagram, which proved invaluable during the development of Django models. It was at this stage we decided that users would need to register to create or bid on listings, with all users acting as both buyers and sellers. Additionally, we developed personas to better target our intended audience and ensure that the website’s design aligned with user needs. A paper prototype was created to visualize the layout of the final product..

<h3>Implementation</h3>
During the project we implemented basic features that are paramount to nearly all web apps which were signup, login and logout features. This meant we could restrict certain features to only registered users. We also added some quality of life features for users including a history of all the purchases that they had previously made, the items that they have listed but have not been sold yet, and any offers that they have made on other existing listings. Eventually we added in a responsive CSS framework which allowed us to make the web app responsive.

Throughout the implementation phase, we focused on key features common to most web applications, including user registration, login, and logout functionalities. These features allowed us to restrict certain actions to registered users. We also introduced quality-of-life features, such as viewing the history of previous purchases, tracking unsold listings, and managing offers on existing listings. To enhance the user experience, we incorporated a responsive CSS framework, ensuring the application adapted to different screen sizes.

As with any project, challenges arose, and we encountered various bugs and needed to modify the original deliverables. To combat this we implemented tests to ensure functionality and prioritized the most important features.

<h4>Technologies Used</h4>
<ul>
    <li>HTML & CSS</li>
    <li>Bootstrap</li>
    <li>Django</li>
    <li>JQuery</li>
    <li>Pythonanywhere</li>
</ul>

<h2>Team Project Reflection</h2>
At the outset, we envisioned a wide array of features for the auction site. However, upon reflection, I realized that our expectations for the user interface were overly ambitious given the timeframe and the size of our team. This led to time constraints and a need to rush certain aspects of the project. Despite these challenges, we successfully developed a functional auction platform that allows users to sign up, log in, create listings, and interact with existing ones.

While the final product may not have fully met all our original goals, the project provided invaluable learning opportunities. I was able to further develop my communication, time management, and leadership skills—skills that will undoubtedly serve me well in my future career.

If you would like to explore our website please click <a href="http://devansh16.pythonanywhere.com/">here<a>.
{% endraw %}