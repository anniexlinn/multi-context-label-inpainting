# Multi-Label Context-Aware Image Inpainting

A hybrid approach combining segmentation, classification, and specialized inpainting models for high-quality image completion.

## Overview

This project implements a context-aware image inpainting pipeline that:

1. Segments images using MobileSAM
2. Classifies regions using EfficientNet
3. Applies specialized inpainting based on region type:
- Faces: GFPGAN/ESRGAN
- Structures: EdgeConnect
- Natural textures: Diffusion models
4. Blends results with Poisson blending

## Features
- MobileSAM integration for efficient segmentation
- Region-specific inpainting with appropriate models
- Hybrid architecture combining best-of-breed approaches
- CPU/GPU compatible implementations
