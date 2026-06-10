---
layout: null
title: Redirecting to Take Part
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="refresh" content="0; url={{ '/sign-up/' | relative_url }}">
    <link rel="canonical" href="{{ '/sign-up/' | absolute_url }}">
    <title>Redirecting to Take Part</title>
</head>
<body>
    <p>Participant information has moved to <a href="{{ '/sign-up/' | relative_url }}">Take Part</a>.</p>
    <script>window.location.replace("{{ '/sign-up/' | relative_url }}");</script>
</body>
</html>
