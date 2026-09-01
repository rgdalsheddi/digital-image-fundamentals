# digital-image-fundamentals
# Digital Image Fundamentals Lab

A Python-based image processing lab exploring fundamental concepts in digital image processing, including image sampling, quantization, arithmetic operations, and logical/set operations.

## Overview

This project was completed as part of the ARTI407 Image Processing course.

The lab demonstrates how digital images can be represented and manipulated using Python and common image-processing libraries.

## Topics Covered

### 1. Image Sampling
Explored the effect of different sampling factors on spatial resolution.

Sampling factors tested:
- 2
- 4
- 8
- 16

Increasing the sampling factor reduces the number of pixels and therefore decreases spatial resolution.

### 2. Image Quantization
Explored the effect of reducing the number of grayscale intensity levels.

Quantization levels tested:
- 256
- 64
- 16
- 4

Reducing the number of quantization levels decreases intensity resolution and produces more visible transitions between grayscale levels.

### 3. Image Arithmetic

Implemented arithmetic operations on grayscale images, including:

- Image addition
- Image subtraction
- Adding a constant intensity value
- Pixel-value clipping to the valid grayscale range

### 4. Logical / Set Operations

Implemented pixel-wise logical operations:

- Union
- Intersection
- Set Difference
- Symmetric Difference

Examples:

```text
Intersection         A & B
Set Difference       A & ~B
Symmetric Difference A ^ B
Union                A | B
