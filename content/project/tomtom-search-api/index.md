---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Tomtom Search Api"
summary: "Search is a RESTful API designed for developers allowing single-line fuzzy search for addresses and POIs. Search assigns a latitude/longitude to a specific address, cross street, geographic feature, or point of interest (POI)."
authors: []
tags: []
categories: []
date: 2020-10-30T23:44:06+03:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

https://developer.tomtom.com/search-api

TomTom has a broad list of location technology products. One major group is the search product unit responsible for providing online search services on the top of maps data.

I've been working on the search product unit to provide extended search APIs to the customers. Those APIs cover a list of different capabilities, including parking space availability, fuel prices, electric vehicle charging station availability, and rich data services. All of these products are available worldwide via highly available, distributed, resilient cloud deployments located on multiple geographical regions to serve low latency APIs to the customers. These services are being used by cars and Azure maps back end and developers who have acquired the developer API key via the TomTom developer portal.

I developed four new microservices from scratch and was responsible for the products from end to end—starting from software design to final deployment including on-call duty. I've made a remarkable impact on the cost optimization of the cloud environment without sacrificing service availability.

