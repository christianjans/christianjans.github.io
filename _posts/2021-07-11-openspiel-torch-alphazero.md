---
title: ":computer: OpenSpiel's LibTorch AlphaZero"
layout: post
date: 2020-07
tag:
image:
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "The LibTorch-based AlphaZero in Google DeepMind's OpenSpiel project."
category: project
author: christianjans
externalLink: false
---

The LibTorch-based AlphaZero in Google DeepMind's OpenSpiel project. Most of the
code is based off of the pre-existing C++ TensorFlow version of AlphaZero in
OpenSpiel.

There were multiple problems in getting the C++ TensorFlow version of AlphaZero
to work in the OpenSpiel's open-source version. The LibTorch version provides a
way to run a C++ AlphaZero in the open-source OpenSpiel framework.

---

Check out OpenSpiel [here](https://github.com/deepmind/open_spiel) and the
LibTorch-based AlphaZero [here](https://github.com/deepmind/open_spiel/tree/master/open_spiel/algorithms/alpha_zero_torch).
