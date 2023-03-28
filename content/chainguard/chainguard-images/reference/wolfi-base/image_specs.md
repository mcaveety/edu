---
title: "wolfi-base Image Variants"
type: "article"
description: "Detailed specs for wolfi-base Chainguard Image Variants"
date: 2023-03-07T11:07:52+02:00
lastmod: 2023-03-07T11:07:52+02:00
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
menu:
  docs:
    parent: "wolfi-base"
weight: 550
toc: true
---

This page shows detailed information about all available variants of the Chainguard **wolfi-base** Image.

## Variants Compared
The **wolfi-base** Chainguard Image currently has one public variant: 

- `latest`

The table has detailed information about each of these variants.

|              | latest        |
|--------------|---------------|
| Default User | `root`        |
| Entrypoint   | not specified |
| CMD          | `/bin/sh -l`  |
| Workdir      | not specified |
| Has apk?     | yes           |
| Has a shell? | yes           |

## Image Dependencies
The table shows package distribution across all variants.

|                          | latest |
|--------------------------|--------|
| `ca-certificates-bundle` | X      |
| `wolfi-base`             | X      |
| `wolfi-baselayout`       | X      |