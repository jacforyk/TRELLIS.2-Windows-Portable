# TRELLIS.2-Windows-Portable
One-Click Image-to-3D &amp; Texture Generation Windows Portable

Microsoft TRELLIS.2 is a state-of-the-art large-scale 3D generative model. It is designed to transform a single 2D image into high-quality 3D mesh files with ease. TRELLIS.2 can reconstruct and generate arbitrary 3D assets featuring complex topologies, sharp geometric details, and full PBR (Physically Based Rendering) materials.

Beyond 3D generation, this version also supports generating high-fidelity textures for existing untextured meshes based on a reference image. This is the second-generation release, offering significant improvements in detail and stability.

## Key Features

High Quality, Resolution & Efficiency: Our 4B-parameter model generates high-resolution fully textured assets with exceptional fidelity and efficiency using vanilla DiTs. It utilizes a Sparse 3D VAE with 16× spatial downsampling to encode assets into a compact latent space.

Arbitrary Topology Handling: The O-Voxel representation breaks the limits of iso-surface fields. It robustly handles complex structures without lossy conversion:

✅ Open Surfaces (e.g., clothing, leaves)

✅ Non-manifold Geometry

✅ Internal Enclosed Structures

Rich Texture Modeling: Beyond basic colors, TRELLIS.2 models arbitrary surface attributes including Base Color, Roughness, Metallic, and Opacity, enabling photorealistic rendering and transparency support.

## How to Use
1. Setup:
   
Download the software package to your local computer and extract the ZIP file.

2. Dual-Mode Launchers:
 
The package includes two dedicated executable files:

Image-to-3D.exe: For generating 3D models from images.

Texture-Generate.exe: For generating textures for existing mesh files.

<img width="686" height="443" alt="image" src="https://github.com/user-attachments/assets/3978fe6f-b395-4a1b-8899-fd1c326bf17c" />

I. Image-to-3D Function

Image Selection: Choose your source image. For best results, use a high-quality image with a single, clear subject and a transparent background.

Auto-Background Removal: You can toggle the "Auto Remove Background" feature. However, providing a pre-processed transparent PNG is highly recommended for maximum precision.

Quality Settings: Parameters like Resolution, Faces, and Texture Size affect the final quality. Higher values yield better results but require more powerful hardware. Please adjust these based on your GPU capabilities.

Export Formats: Supports GLB, OBJ, and STL formats.

Output: The final model will be saved automatically in your designated output directory.

<img width="779" height="443" alt="image" src="https://github.com/user-attachments/assets/d24f9fd2-5a11-4982-97a0-a5829f7a5c27" />


II. Texture Generation Function

This process is similar to Image-to-3D. Simply upload your untextured Mesh File and a reference image to generate high-quality textures mapped to your geometry.

Video Tutorials:https://www.youtube.com/watch?v=Ig6L0b5u81c

## System Requirements & Notes

Note: The TRELLIS.2-4B model files will be downloaded automatically during the first run. Please ensure you have at least 14.5GB of free disk space available.

To ensure a smooth experience, please verify that your hardware meets the following requirements:

OS: Windows 10 or Windows 11 (64-bit). Mobile devices and macOS are not supported.

GPU: NVIDIA GeForce RTX series with at least 6GB VRAM (More VRAM allows for higher resolution settings).

RAM: Minimum 32GB System Memory.

Path Requirements: Ensure that the software installation path, the source file names, and the output paths do not contain non-English characters or spaces. This is critical to avoid execution errors.

Download Link

https://www.patreon.com/posts/154995368
