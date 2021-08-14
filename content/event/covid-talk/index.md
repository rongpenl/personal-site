---
title: COVID-19 Visualizations, the Good, the Bad and the Malicious

event: PyData Global 2020
event_url: https://pydata.org/

location: Virtual
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: A systematic survey of the visualization of COVID-19 data.
abstract: Visualization is supposed to convert data into more informative, digestible format so readers without too much analytical training can grasp the ideas or situations the data contains. This is especially important during the age of crisis, like the COVID-19 pandemic.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-11-12T13:00:00Z"
date_end: "2020-11-12T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
# - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}} -->

## What is This Talk About?

This talk is a rough survey of visualizations about COVID-19 as November 2020. I collected several representative visualizations and analyzed them in a systematic, scientific way, essentially three key steps.

1. What is the information the visualization tries to convey? Is it in agreement with scientific consensus?
2. Is the data reliable? Does the data contain the intended information in principle?
3. What kind of plot and aesthetic elements does the visualization use? Do such visual elements help or not?

## Why did I Give This Talk?

Visualization is supposed to convert data into more informative, digestible format so readers without too much analytical training can grasp the ideas or situations the data contains. This is especially important during the age of crisis, like the COVID-19 pandemic.

I believe in a public crisis like COVID-19, The most important thing for data science is to precisely and exactly convey the objective information. Even when the data is of high quality and the visualization is correct, the data scientists should inform the readers the possible judgmental consequences of the data preprocessing, transformation and aesthetic choices. In many cases data scientists think this is unnecessary or omit such information. However, when the audience is general public, these self-discrediting footnotes become a corner-stone for reliability and trustworthiness.

## What's the Future of the Talk

You may find the original code for the presentation here: [rongpenl/pydata-global-covid-visualization](https://github.com/rongpenl/pydata-global-covid-visualization/blob/main/reproducibile/COVID-19%20Visualizations-the-Good-the-Bad-and-the-Malicious.ipynb).

The age of misinformation and information diabetes is upon us. Misinformation and echo chamber effect caused by recommendation algorithm already caused tremendous amount of damage to the society of United States and around the globe. This talk inspired me to write a book called **Practical Digital Civics** **by a Data Scientist** to combat such threat. As January 2021, I am finalizing the draft of this book.