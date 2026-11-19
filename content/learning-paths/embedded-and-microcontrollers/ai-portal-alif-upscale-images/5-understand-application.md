---
title: Understand the application and switch models
description: Trace image preprocessing, ExecuTorch inference, and output handling, then switch the upscaling model.
weight: 6

### FIXED, DO NOT MODIFY
layout: learningpathall
---

## Follow the image through the application

TODO: Outline the path from the host image through preprocessing, inference, and postprocessing to the retrieved image and optional display.

## Inspect input preprocessing

TODO: Point to the code that converts image pixels into the model's input tensor and explain its layout and normalization.

## Understand ExecuTorch and Ethos-U85 execution

TODO: Show where the PTE is embedded, how the Cortex-M55 runs ExecuTorch, and which work is delegated to Ethos-U85.

## Inspect output postprocessing

TODO: Point to the tensor-to-image conversion and explain how host output and a smaller display preview are produced.

## Switch between QuickSRNetSmall and SESR-M5

TODO: List the model-path, input/output, and memory changes required, then add rebuild and validation steps for the second model.

## What you've learned and what's next

TODO: Recap the reusable image upscaling workflow and identify the compatibility checks needed before trying another model.
