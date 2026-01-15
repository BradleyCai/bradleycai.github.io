+++
template = 'artwork.html'

title = "Snow Shader in Godot"

description = """A snow ground effect in the Godot game engine that reacts to objects when they're close to the ground.

I wrote about my process of creating this project here:  
[First Steps in Snow Shader](/posts/first-steps-in-snow-shader/)
"""
date = 2025-05-20

[extra]
lang = 'en'
short_description = """A snow ground effect in the Godot game engine that reacts to objects when they're close to the ground."""
thumbnail = 'thumbnail.png'

[taxonomies]
tags = ["Graphics", "Shaders", "Godot"]
+++

{{ artwork_video(src="parallax.mp4", text="Snow shader on ground reacting to object movement using parallax mapping. The effect is done in the fragment shader and doesn't depend on any specific ground geometry") }}
{{ img(src="orthographic-cameras.jpg", text="A drawing of how depth information is captured. Two orthographic cameras are used to capture actor and snow ground height which is used to compare their distance. By doing this, the ground terrain geometry can be uneven and still keep the desired effect") }}
{{ artwork_video(src="close-to-snow-surface.mp4", text="An intermediate texture that holds distance information is kept in gpu memory and used for the visual effect") }}
{{ artwork_video(src="demo-1.mp4", text="Demo of the final result") }}
