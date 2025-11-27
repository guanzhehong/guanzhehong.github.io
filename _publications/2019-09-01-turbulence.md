---
title: "Rethinking Atmospheric Turbulence Mitigation"
collection: publications
category: manuscripts
permalink: /publication/2019-09-01-turbulence
excerpt: 'Nicholas Chimitt, Zhiyuan Mao, **Guanzhe Hong**, Stanley Chan'
date: 2019-05-17
venue: 'arXiv Preprint'
paperurl: 'https://arxiv.org/abs/1905.07498'
---

State-of-the-art atmospheric turbulence image restoration methods utilize standard image processing tools such as optical flow, lucky region and blind deconvolution to restore the images. While promising results have been reported over the past decade, many of the methods are agnostic to the physical model that generates the distortion. In this paper, we revisit the turbulence restoration problem by analyzing the reference frame generation and the blind deconvolution steps in a typical restoration pipeline. By leveraging tools in large deviation theory, we rigorously prove the minimum number of frames required to generate a reliable reference for both static and dynamic scenes. We discuss how a turbulence agnostic model can lead to potential flaws, and how to configure a simple spatial-temporal non-local weighted averaging method to generate references. For blind deconvolution, we present a new data-driven prior by analyzing the distributions of the point spread functions. We demonstrate how a simple prior can outperform state-of-the-art blind deconvolution methods.

[Paper link](https://arxiv.org/abs/1905.07498)
