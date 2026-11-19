---
title: Build and flash the E8 application
description: Configure the image upscaling firmware, build it, and program the Alif Ensemble E8.
weight: 4

### FIXED, DO NOT MODIFY
layout: learningpathall
---

## Configure the E8 build

TODO: Add the tested CMake command selecting the board, RTSS-HP, upscaling use case, model, and matching Ethos-U85 settings.

## Allocate memory for inference

TODO: Explain the required model, planned-buffer, and temporary memory allocations, including PSRAM and any differences between the two models.

## Build the firmware

TODO: Add the build command and identify the executable and MRAM image produced.

## Prepare the SETOOLS images

TODO: Add image-copy and TOC-generation commands, using the device configuration that matches the board revision.

## Flash and restart the board

TODO: Add the tested SEUART programming sequence, UART4 switch setting, reset steps, and startup checks.

## What you've accomplished and what's next

TODO: Recap the flashed application and introduce sending an image for upscaling.
