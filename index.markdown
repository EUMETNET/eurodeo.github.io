---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
author_profile: true
layout: splash

header: 
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/rodeo-hero.webp
  actions:
  - label: "Explore more"
    url: "https://github.com/EURODEO"

excerpt: "The provision of open access to public meteorological data and development of shared federated data infrastructure for the development of information products and services."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

feature_row:
  - image_path: /assets/images/img-sample-01.webp
    alt: "rodeo1"
    title: "Open Access"
    url: "/rodeo"
    excerpt: "The provision of open access to public meteorological data and development of shared federated data infrastructure for the development of information products and services."
    btn_label: "Explore more"
  - image_path: /assets/images/img-sample-02.webp
    alt: "rodeo2"
    title: "Meteorological Data"
    url: "/rodeo"
    excerpt: "The provision of open access to public meteorological data and development of shared federated data infrastructure for the development of information products and services."
    btn_label: "Explore more"

  - image_path: /assets/images/img-sample-02.webp
    alt: "rodeo2"
    title: "Data and Development"
    url: "/rodeo"
    excerpt: "The provision of open access to public meteorological data and development of shared federated data infrastructure for the development of information products and services."
    btn_label: "Explore more"


---

{% include feature_row %}

{% include feature_row id="intro" type="center" %}
