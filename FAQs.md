---
layout: default
title: FAQs
---

<div class="blog-container">
    <div class="blog-header">
        <h1>BotsBlog</h1>
        <p>Latest updates and news from Unibots</p>
    </div>

    <div class="blog-posts">
        {% for post in site.posts %}
        <article class="blog-post">
            <header class="post-header">
                <h2 class="post-title">
                    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
                </h2>
                <div class="post-meta">
                    <time class="post-date" datetime="{{ post.date | date_to_xmlschema }}">
                        {{ post.date | date: "%B %d, %Y" }}
                    </time>
                    {% if post.categories %}
                    <div class="post-categories">
                        {% for category in post.categories %}
                        <span class="category-tag">{{ category }}</span>
                        {% endfor %}
                    </div>
                    {% endif %}
                </div>
            </header>
            
            {% if post.excerpt %}
            <div class="post-excerpt">
                {{ post.excerpt }}
            </div>
            {% endif %}
            
            <div class="post-read-more">
                <a href="{{ post.url | relative_url }}" class="read-more-link">Read More →</a>
            </div>
        </article>
        {% endfor %}
    </div>
</div>
