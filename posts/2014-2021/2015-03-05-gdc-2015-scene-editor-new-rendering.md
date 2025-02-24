---
title: 'Scene Editor and Advanced Rendering presented at GDC'
author: silicon-studio
image: /images/blog/GDC2015/xenko_gdc.png
image_thumb: /images/blog/GDC2015/xenko_gdc_thumb.png
---

We have been quiet for the past two months working hard on many new features in Xenko that we are presenting this week at GDC 2015.

---

<ul>
	<li>A new scene editor</li>
	<li>A new layered material system with physically based rendering quality</li>
	<li>A new live scripting system, with a smart compilation reloading and hot-swapping of running scripts, using the Roslyn compiler</li>
	<li>A simple and powerful PostEffects API coming along many builtin effects (Depth Of Field, Bloom, Lens Flare, Glare, ToneMapping, Vignetting, Film Grain, Antialiasing...)</li>
	<li>A scene rendering compositor, a new way to define precisely how to render scenes in your game, apply post effects...etc.</li>
</ul>

<p>All these features will be available in a new version in the coming weeks. We will need a bit more work after GDC to polish things, write proper documentation and add new samples so that you will embrace more easily all these new APIs. As this release is bringing some major changes, we had no choice than breaking some of the existing API, mostly related to the Entities and components, but you will see that It is coming with much greater benefits!</p>

<p>In the meantime, we are presenting some sessions here at GDC, but you can also grab our presentations here:</p>

<ul>
	<li>An overview of Xenko: A brief introduction of what is Xenko, new features and what is coming next (Download link <a href="http://stride3d.net/images/blog/XenkoSession1-Overview.pptx">here</a>)</li>
	<li>Advanced Rendering: Some details about the new Material System, the Post Effects API and the Scene Rendering Compositor (Download link <a href="http://stride3d.net/images/blog/XenkoSession2-AdvancedRendering.pptx">here</a>)</li>
	<li>Beyong Uber Shaders: A sneak peek about the Xenko Shading Language (Download link <a href="http://stride3d.net/images/blog/XenkoSession3-BeyonUberShaders.pptx">here</a>)</li>
</ul>

<p>We will also release shortly a video showing the rendering of a Robot with the new PBR material system and post effects that we presented here at GDC.</p>

{% img-click 'Materials Physically Based Rendering' '/images/blog/GDC2015/pbr_robot_thumb.jpg' '/images/blog/GDC2015/pbr_robot.jpg' %}