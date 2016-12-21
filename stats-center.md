---
layout: default
title: stats-center - Fight Analytics
permalink: /stats-center/
---

<div class="inner-page">
    <article id="page" class="page jumbotron">
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="text-container col-md-8">
                        <h1>Stats Center</h1>
                    </div>
                </div>
            </div>
        </div>
    </article>
    <br><br>
    <div class="container">
        <div class="list-post col-md-12">
            {% for post in site.categories.stats-center %}
                <article class="post-thumb col-md-4">
                    <strong>
                        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
                    </strong>
                    <h2>
                        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
                            <span class="img-thumb"><img src="{{ post.imgthumb }}" alt="{{ post.title }}"></span>
                            <br><br>
                            {{ post.title }}
                        </a>
                    </h2>
                    <hr>
                    <br>
                </article>
            {% endfor %}
        </div>
    </div>

    <br><br>
    <div class="well well-lg">
        <div class="container">
            <h3>Start improving the live fight experience for your MMA fans now.</h3>
            <a href="http://manager.fightanalytics.cc/users/sign_up" class="btn btn-primary btn-lg"> <strong>Free Trial</strong> <span class="subtext">(no credit card required)</span></a>
        </div>
    </div>
</div>