---
layout: page
title: Photo App
description: a full stack web app for photo sharing social network
img:
importance: 1
category: work
---

Link: <a href="https://photo-app-demo-kcli.herokuapp.com/">photo-app-demo-kcli.herokuapp.com</a>

Log in with default Username: webdev, Password: password

This is a web based photo app on which users can like, bookmark, and add comments to posts, as well as follow and unfollow users. Users can view posts from themselves and from people they follow. Vice versa, their followers can also view photos that they post. 

· Developed using HTML, CSS, Javascript.

· Designed and built REST API endpoints with Python’s SQLAlchemy & Flask RESTful library to handle GET, PUT, DELETE, PATCH, etc. commands and updates the database accordingly.

· Maintained a PostgresSQL database for posts, user, followers, likes data according to the message received at API endpoints.

· Built authentication methods supporting username / password, and valid JSON web tokens after logging in for the first time.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/photo_app_auth.png" title="authentication page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Upon initial visit to the site, user will be redirected to the authentication page
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/photo_app_main.png" title="main page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    After logged in, user can view posts from other users
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/photo_app_modal.png" title="modal box" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    a box pops up when user wants to view more comments
</div>
