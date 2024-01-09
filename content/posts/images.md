+++
title = 'Images'
date = 2024-01-09T08:58:27-03:00
draft = false
+++


{{ $image := .Resources.GetMatch "sunset.jpg" }}
<img src="{{ $image.RelPermalink }}" width="{{ $image.Width }}" height="{{ $image.Height }}">

