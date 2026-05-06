---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Accuracy Representations and Estimates"
authors:
 - catrin
date: 2022-04-23


# Optional date to print, e.g. "forthcoming" or "preprint"
# date_print: ""

featured: false

lastmod: 2024-12-02

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
#publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""


# Summary. An optional shortened abstract.
summary: "We present standard results about representations of strictly proper measures of accuracy. We also show the same results hold when measuring accuracy of previsions more generally. This has significant philosophical payoff"

abstract: "This document goes through some standard results about strictly proper measures of accuracy and representation theorems (Schervish and Savage/Bregman).

It also presents the slightly less well studied case of measuring the accuracy of
estimates of random variables.

The spirit of the document is to include proofs, but to make things simple
in order to make the central ideas of the proofs across, often at the cost of
generality. A number of restrictive assumptions are made throughout.

Full analysis of what restrictions can be dropped in the estimates case requires
further work."


#Feel free to add others
tags:
#- Self-referential probability
- Accuracy
#- Imprecise Probability
#- Risk-sensitive decision theory
#- Kripkean fixed-points
#- Revision Theory of Truth



categories: []


# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
 - name: arXiv
   url: https://arxiv.org/abs/2412.06420
#   icon_pack: fab
#   icon: twitter

doi: ""

url_preprint:
url_pdf: 
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
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [accuracy]

---


There are philosophical payoffs of extending accuracy measures to estimates:
1) Agents should be thought of not only as having probabilities but associating real-valued expectation values to quantities. If this is to be taken seriously rather than derivatively, such measures are needed. 
2) If truth-values are non-classical and given real valued 'cognitive load' (in the sense of Williams) such extended accuracy measures are needed. 
3) Two accuracy arguments seemingly different arguments for the Principal Principle which Richard Pettigrew gives turn out to be mathematically equivalent. We can indeed meaure closeness to chance, and it matches chance's estiamte of closeness to truth.
4) A better argument for the Brier score can be given by taking measures of estimates to be 'value symmetric', extending the 0/1-symmetry from Joyce, but in the general estimates setting, a unique accuracy score is identified: the Brier score. This helps in a response to the Bronfman objection and gives a natural justification of this measure which is simpler than alternative arguments for it which are given by Pettigrew. 