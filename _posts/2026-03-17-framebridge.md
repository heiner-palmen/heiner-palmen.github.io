---
layout: post
title: "FrameBridge — Real-time Pixel Analysis for OBS"
date: 2026-03-17 12:00:00 +0100
categories: project obs lua automation
---

As part of exploring automation and real-time data processing, I built **FrameBridge**, an OBS plugin that allows Lua scripts to access pixel data from any source or scene, even if it’s not currently on-air.

It hooks directly into OBS’s render pipeline and exposes a thread-safe API for:

- Per-pixel queries
- Region average colors
- Color matching
- Template matching against reference images
- On-demand screenshots

This project showcases ideas I’m passionate about: automation, data analysis, and building tools that make workflows smarter.

[GitHub Repo](https://github.com/heiner-palmen/obs-framebridge)