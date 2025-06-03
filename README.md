# VistaMPI

## Project Profile

This repository is used for demonstrations and testing based on the VistaMPI framework. We have uploaded 20 sample images along with their corresponding depth maps to illustrate the generation of novel views from single traditional Chinese paintings. These samples provide insight into our approach to stylized view synthesis.

## Method Overview

Recent advances in generative view synthesis have achieved remarkable progress with photorealistic imagery, but they often struggle when applied to traditional art domains such as classical Chinese landscape paintings. These paintings exhibit unique characteristics such as scattered-point perspective, broken ink-line edges, and highly stylized brushwork, which differ significantly from natural images. Existing view synthesis models, trained on large-scale real-world datasets, often fail to capture the spatial coherence and stylistic continuity required in such artistic domains.

To address these challenges, we present a multiplane image-based framework tailored for Chinese ancient paintings. Our method enhances geometric continuity and texture consistency through a two-stage strategy: depth estimation and novel-view generation. In the first stage, a hybrid depth estimation module predicts dense, painting-specific depth maps. A line-inpainting network is introduced to recover broken structural strokes, ensuring continuity of ink lines across synthesized views. In the second stage, our system utilizes a Bidirectional State-Space Modeling module (BiAMamba) to refine the MPI depth distribution, followed by a multi-scale ResMamba encoder that captures both local textures and global scene layouts.

This framework allows the model to produce multi-perspective images while preserving the artistic integrity of the original painting. Each synthesized view aligns with the aesthetic and compositional properties of traditional art, offering smooth parallax and layered depth transitions. Our dataset samples provide a practical demonstration of these capabilities and serve as a foundation for further exploration in stylized view synthesis and cultural heritage digitization.

## Code

We will upload the training scripts, testing code, and the complete dataset in future updates.
