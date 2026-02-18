---
layout: default
title: Home
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">

<link rel="stylesheet" href="{{ '/css/index1.css' | relative_url }}">
<link rel="icon" href="{{ '/assets/images/unibots.ico' | relative_url }}">

<div id="index">
    <div id="header">
        <div id="header-intro">
            <div id="logo-container">
                <img src="{{ '/assets/images/unibots.png' | relative_url }}" width="200" height="200" id="unibots-logo" alt="UniBots UK Logo">
            </div>
            <div id="header-text">
                <h1>Unibots UK</h1>
                Unibots UK is an autonomous robotics competition aimed at University students and clubs, fostering enthusiasm and engineering skills into the next generation of robotics students!
            </div>
        </div>
        <div id="header-about">
            <div id="header-about-item">
                <div class="small">ORGANISED BY</div>
                <div class="row">
                    <img src="{{ '/assets/images/CURLOGO_TEXT.svg' | relative_url }}" height="100" class="logo-about cur" alt="Cambridge University Robotics Logo">
                    <img src="{{ '/assets/images/hwrobotics.jpg' | relative_url }}" class="logo-about hw" alt="Heriot-Watt Robotics Society Logo">
                    <img src="{{ '/assets/images/Queen_Mary_Logo.jpeg' | relative_url }}" class="logo-about qm" alt="Quen Mary Robotics Society Logo">
                </div>
            </div>
        </div>
        <div id="prizes-subsidies" class="row">
            <div id="header-text">
                <h2>The 2026 Season</h2>
                It's official, the Unibots 2026 season begins!<br>
                After the success of last year, we decided to bring back Unibots bigger and better than ever with a new format and more events.
            </div>
            <div id="header-text">
                <h2>New for 2026</h2>
                This year we are introducing Regionals! We want to help everyone across the country and enable them to have a taste of the arena and competition format before the Finals in July, and to help you practice in a tournament setting.<br> 
                More information to come soon!
            </div>
        </div>
    </div>

    <div class="section">
        <div class="content">
            <div class="desc-picture-cont">
                <img src="{{ '/assets/images/DSC_2716-min.jpg' | relative_url }}">
                <div class="desc">
                    <h3>Intermediate-level Competition</h3>
                    <p>We designed the competition to allow anyone who has elementary experience with robotics to be able to build and compete.</p>
                    <p>For 2026, robots will go head to head to compete in the arena, trying to collect as many ping pong and steel ball bearings as possible.</p>
                    <p>Our competition will be great fun for competitors with any level of experience!</p>
                </div>
            </div>
            <div class="desc-picture-cont alt">
                <img src="{{ '/assets/images/DSC_2517-min.jpg' | relative_url }}">
                <div class="desc">
                    <h3>Competition Day</h3>
                    <p>The regionals will be held across the UK before the final event as a one day competition, with dates to be announced soon. In these you'll get to practice and improve your robot to be one step closer to winning the two day event in July</p>
                    <p>The competition is a great way to meet other students that are as passionate about robotics as you are.</p>
                    <p>Dates for Regionals (one-day event):<br>

    Edinburgh: Saturday 28 February 2026 at Heriot-Watt University.<br>
    Cambridge: Saturday 21 March 2026 at University of Cambridge.<br>
</p>
                </div>
            </div>
        </div>
    </div>

    <div class="section">
        <div class="desc-picture-vert">
            <img src="{{ '/assets/images/DSC_2866-min.jpg' | relative_url }}">
            <div class="desc">
                If all this sounds fun, sign up for our competition!
            </div>
        </div>
    </div>

    <div class="section">
        <div id="info-buttons" class="row">
            <a href="https://linkly.link/2Firr" class="button intro doc">2026 RULEBOOK</a>
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSfEvT1Q8A_u6wGSomogfAurt6BKIho082s9yv_fDwZlbdy3TQ/viewform" class="button rulebook">2026 SIGN UPS</a>
        </div>
        <div id="info-buttons" class="row">
            <a href="https://www.instagram.com/unibots_uk/" class="button signup">INSTAGRAM</a>
            <a href="https://discord.gg/N2xYcKAT5a" class="button discord">DISCORD SERVER</a>
        </div>
    </div>

    <div class="section">
        {% include sponsors.html %}
    </div>
</div>
