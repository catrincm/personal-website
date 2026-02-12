---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Probability Filters as a Model of Belief"
authors:
- catrin

date: 2021-03-29T17:45:44+01:00


# Optional date to print, e.g. "Forthcoming or "preprint"
# date_print: "Forthcoming"

featured: false


# Options for drafts

lastmod: 2021-05-23T17:45:44+01:00
#draft: true

# Publication type.
# 0 = Uncategorized;
# 1 = Journal article;
# 2 = Book;
# 3 = Book section;
# 4 = Thesis;
# 5 = Book review;
# 6 = Conference paper;
# 7 = Report;
# 8 = Preprint / Working Paper;
# 9 = Other
publication_types: []

# Publication name and optional abbreviated publication name.
publication: "Proceedings of Machine Learning Research -- ISIPTA 2021"
publication_short: "ISIPTA 2021"

abstract: ""

# Summary. An optional shortened abstract.
summary: "We propose representing a (possibly imprecise) epistemic state using a probability filter focusing on probabilistic properties, such as whether pr(A)>0.2. It is very expressively powerful.
"

#Feel free to add others
tags:
- Probability Filters
#- Self-referential probability
#- Accuracy
- Imprecise Probability
#- Risk-sensitive decision theory
#- Kripkean fixed-points
#- Revision Theory of Truth



categories: []


# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

doi: ""

url_preprint: papers/prfilters-des.pdf
url_pdf: https://proceedings.mlr.press/v147/campbell-moore21a.html
url_project:
url_slides:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
#image:
#  caption: ""
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
projects: []
related_to_projects: []
---

This conference version was developed into the journal article [Probability Filters and Desirable Gambles]({{< relref "/publication/2026-prfilters-des-IJAR" >}}).

We propose representing a (possibly imprecise) epistemic state using a probability filter.


This focuses on judgements on sets of probabilities.
When you think that it is more likely to be sunny than rainy, we capture your attitude with a collection of probabilistic judgements including the judgement that p(Sunny)>p(Rainy).
Judgement may also be suspended, you might allowing for imprecision.


Coherent such judgements are given when the judgements are closed under finite intersections and supersets. This allows for non-Archimadean behaviour.


The framework is very expressively powerful. It can unify work in the imprecise probability literature on desirable gambles and credal sets.


This paper in particular shows that this captures the desirable gambles model.
