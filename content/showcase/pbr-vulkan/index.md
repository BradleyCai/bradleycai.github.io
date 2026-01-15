+++
template = 'artwork.html'

title = "PBR in Vulkan"

description = """Physically based rendering implementation in Vulkan with IBL. Able to load PBR authored gltf files and display them.

My PBR implementation is based off of [leanopengl's](https://learnopengl.com/PBR/Theory) guide, and uses radiance and irradiance maps generated from [cmft](https://github.com/dariomanesku/cmft). The precomputed BRDF integration map was calculated in the vulkan engine.

This project uses my previous project ["Vulkan Engine"](/showcase/vulkan-engine) as a base.

GitHub page:  
[https://github.com/BradleyCai/pbr-vulkan](https://github.com/BradleyCai/pbr-vulkan)
"""
date = 2025-12-18

[extra]
lang = 'en'
short_description = """Physically based rendering implementation in Vulkan with IBL. Able to load PBR authored gltf files and display them."""
thumbnail = 'thumbnail.png'

[taxonomies]
tags = ["Graphics", "Vulkan", "Shaders"]
+++

{{ artwork_video(src="demo-1.mp4", text="Full demo of project with background sky shader, model selector, model viewer with controls, and PBR material shading with IBL and 4 point lights") }}
{{ img(src="engine-vs-godot.jpg", text="Helmet model viewed in custom vulkan engine (left) vs viewed in the Godot game engine (right)") }}
