---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
author_profile: true
layout: splash

header: 
  overlay_color: "#fff"
  overlay_filter: "0"
  overlay_image: assets/images/rodeo-hero@3x.webp
  actions:
  - label: "Explore more"
    url: "/about"

excerpt: "The provision of open access to public meteorological data and development of shared federated data infrastructure for the development of information products and services."

feature_row:
  - image_path: /assets/images/img-sample-01.webp
    alt: "rodeo1"
    title: "Project Activities"
    url: "/projectactivities"
    excerpt: "Introduction to the project content and activities. Description of plans for providing tools to access open meteorological data."
    btn_label: "Explore more"
    image_path: /assets/images/img-sample-02.webp
    alt: "rodeo2"
    title: "Deliverables"
    url: "/deliverables"
    excerpt: "Project public technical deliverables."
    btn_label: "Explore more"
  - image_path: /assets/images/img-sample-02.webp
    alt: "rodeo2"
    title: "News"
    url: "/news"
    excerpt: "Project news and articles, upcoming events with RODEO representatives and other communication and engagement activities."
    btn_label: "Explore more"
  - image_path: /assets/images/img-sample-02.webp
    alt: "rodeo2"
    title: "Contacts"
    url: "/contacts"
    excerpt: "Contact us – please ask, inquire, request, approach, invite, collaborate. We are looking forward to talking and meeting with you!"
    btn_label: "Explore more"


---

{% include feature_row %}

{% include feature_row id="intro" type="center" %}
