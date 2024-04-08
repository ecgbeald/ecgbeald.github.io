---
title: Aware
summary: A geofencing application for crime awareness
tags:
  - Android
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

An application that was targeted to tourists in popular cities like London, where authorities can post geo-located alerts about crimes or road closures on a map. Geofencing background notifications were used to inform the user about nearby alerts. This application is built in Kotlin for the front-end with Android Studio, and a blend of Django REST API and Websocket as the backend. 

CI/CD pipelines (mainly on Docker Containers) were used to unit test, generate apk files, and deploy changes to the backend web interface.