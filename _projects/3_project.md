---
layout: page
title: Sharpening the Tools
description: Innovations in Computational Genomics
img:
importance: 3
category: methodology
---

Our investigations into complex population histories have consistently revealed the limitations of existing analytical tools. This has driven a parallel research program dedicated to testing, improving, and understanding the fundamental behavior of the statistical methods that underpin our field.

A key publication in this area is our [2023 *eLife* paper](https://doi.org/10.7554/eLife.85492), "On the limits of fitting complex models of population history to f-statistics". In this work, we demonstrated that as demographic models become more complex—for instance, involving more than six populations and multiple admixture events—they often cease to be unique. Many alternative models can fit the genetic data equally well, or even better, than a published model. This finding urges caution against making overly strong historical claims based on a single "best-fit" model and advocates for a more rigorous approach where the full space of plausible scenarios is explored.

We have also conducted [extensive performance tests of the widely used qpAdm software](https://doi.org/10.1093/genetics/iyaf047). Using large-scale simulations of known population histories, we found that exploratory screens using qpAdm can have high false discovery rates, sometimes exceeding 50%. Based on these findings, we have proposed a series of best practices—such as using larger SNP sets and enforcing temporal constraints—that dramatically improve the robustness and reliability of the method. This work provides a critical user guide for researchers and elevates the standard of evidence across the field of archaeogenetics.
