---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}

{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{{ site.staffersnobio }}

[Jump to the current week](#week-5-gradient-descent-br-small-read-course-notes-a-href-https-sawyer-jack-1-github-io-assets-teaching-tfds-book-pdf-page-74-section-3-2-a-optional-see-a-href-https-sboyles-github-io-teaching-ce377k-convexity-pdf-these-notes-on-convexity-a-a-href-https-x-com-sillyalexnorris-status-1022803306173923328-webcomic-name-a-small){: .btn } <!--[Assignment Solutions](){: .btn .btn-purple }-->

<!-- {: .green }

> Welcome to DSC 40A! See you in class this week. To begin, fill out the (required) [Welcome Survey](https://forms.gle/qA5xnzXiNZc55nii6). -->

{% for module in site.modules %}
{{ module }}
{% endfor %}

