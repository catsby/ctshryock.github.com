---
layout: default
title: ctshryock @ github
image: magic_tree.JPG
---

##home

<img id="main-image" src="/images/{{page.image}}" width="500"  />

> I think Rudolf is a terrible story to tell kids.  This poor deer tries to change himself to be more like everyone else, but he fails, and everyone still hates and mocks the guy.  Then all of a sudden they're in a tight spot and he's useful so they all love him?


<ul>
    {% for post in site.posts %}
    <ul>
        <li>
            <img width="50" src="/images/{{post.image}}" /><a href="{{post.url}}">{{post.title}}</a><br />{{ post.date | date_to_string }}
        </li>
    </ul>
    {% endfor %}
</ul>