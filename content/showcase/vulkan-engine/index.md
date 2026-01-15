+++
template = 'artwork.html'

title = "Vulkan Engine"

description = """Made based off the [vkguide.dev](https://vkguide.dev/) guide. The engine is able to load and display models from gltf files and fly around to view them.
"""
date = 2025-09-22

[extra]
lang = 'en'
short_description = """Made based off the vkguide.dev guide. The engine is able to load and display models from gltf files and fly around to view them."""
thumbnail = 'thumbnail.jpg'

[taxonomies]
tags = ["Graphics", "Vulkan"]
+++

{{ artwork_video(src="demo-1.mp4", text="Demo of the engine") }}
{{ img(src="first-triangle.jpg", text="First triangle in Vulkan") }}
{{ artwork_video(src="first-model.mp4", text="The first model loaded from a .gltf file") }}
{{ img(src="performance.png", text="Engine before and after optimizing how often materials rebinded resources and after adding frustum culling. Pipelines, descriptor sets, and index buffers were changed to only rebind when needed and the scene's materials are sorted to keep alike materials together. Frustum culling works by skipping rendering objects that are not in the camera's view frustum which is demonstrated by the before and after triangle count") }}
{{ img(src="mipmaps.png", text="Engine before and after generating mipmaps for textures") }}
