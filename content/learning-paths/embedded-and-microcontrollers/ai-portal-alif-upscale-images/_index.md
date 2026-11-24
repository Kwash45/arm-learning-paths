---
title: Run Arm AI Portal Image Upscaling models on Alif E8

description: Run Arm AI Portal image upscaling models on the Alif Ensemble E8 using ExecuTorch and Ethos-U85.

minutes_to_complete: 35

who_is_this_for: Use this Learning Path if you want to run optimized image upscaling models locally on the Arm Ethos-U85 NPU.

learning_objectives:
    - Download QuickSRNetSmall and SESR-M5 from the Arm AI Portal.
    - Build and flash an ExecuTorch image upscaling application for the Alif E8.
    - Send an image to the board, run inference on Ethos-U85, and retrieve the result.
    - Verify the upscaled output and switch between the supplied models.

prerequisites:
    - Experience with C or C++, CMake, and embedded baremetal development concepts
    - A Linux development environment, including WSL 2 on Windows
    - An Alif Ensemble E8 DevKit and a USB-C data cable
    - Git installed on the development machine
    - Python 3 with the `venv` and `pip` modules on the machine
    - A tool for downloading files and a tool for extracting ZIP archives on the machine

author: Kwashie Andoh

generate_summary_faq: false
rerun_summary: false
rerun_faqs: false

### Tags
skilllevels: Introductory
subjects: ML
armips:
    - Cortex-M
    - Ethos-U
tools_software_languages:
    - ExecuTorch
    - CMake
    - GCC
    - Python
    - Arm AI Portal
    - Hugging Face
operatingsystems:
    - Baremetal
    - Linux
    - Windows

further_reading:
    - resource:
        title: Arm AI Portal
        link: https://developer.arm.com/ai
        type: website
    - resource:
        title: Alif ML Embedded Evaluation Kit
        link: https://github.com/alifsemi/alif_ml-embedded-evaluation-kit/tree/main
        type: repository
    - resource:
        title: Alif Ensemble E8 DevKit Support Page
        link: https://alifsemi.com/support/kits/ensemble-e8devkit/
        type: website
    - resource:
        title: ExecuTorch Arm Ethos-U NPU Backend Tutorial
        link: https://docs.pytorch.org/executorch/stable/tutorial-arm-ethos-u.html
        type: documentation

### FIXED, DO NOT MODIFY
# ================================================================================
weight: 1
layout: "learningpathall"
learning_path_main_page: "yes"
---
