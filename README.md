
<h1  style="line-height:2;"><p  align="center"><a  href="https://www.onnetsystems.net/contact.html"  target="_blank"><img  src="./resources/demo.png"  width="23%"  height="10%"  alt="Unity video player"  align="right"></img></a>

<a  align=right  href="https://www.onnetsystems.net/contact.html"  target="_blank"><img  src="./resources/onnet_systems.png"  width="100%"  height="100%"></a>

  

</br>

# OnnPlayer - Video streamig Player for Unity WebGL

<p  style="margin-left:auto;margin-right:auto"  width="300px"  align="left"> OnnPlayer™ for Unity is a Adaptive bit rate video streaming player for WebGL based Unity games and apps supported on Chome and Safari on Android, iOS, Windows and macOS. OnnPlayer's Unity video plugin also supports <b>Widevine DRM-protected</b> HLS & DASH streaming on <b>Chrome</b> and <b>Fairplay DRM-protected</b> HLS streaming on <b>Safari</b>.

  

This repository contains the OnnPlayer™ Unity  WebGL video streaming player plugin features list as well as an installation guide. If you want to get a copy of our fully working demo, contact us at [Onnet Systems](https://www.onnetsystems.net/contact.html).</p>

  

## Demo Examples

  

<p  style="margin-left:auto;margin-right:auto"  width="300px"  align="left">Our Unity video plugin allows the introduction of new exciting scenes within your Unity projects. With our plugin, you can use in-game actions and objects to modify video content.</p>

<p  align="center"  style="border-style:solid"><a  rel="noopener noreferrer"><img  src="./resources/render.png"  width="95%"  height="95%"></a>

  

## [Our Unity Use Cases](https://d1j2x89u6hjw6s.cloudfront.net/)


<img  src="./resources/metaverse.gif"  width="95%"  height="95%"> WebGL: Browser-based metaverses|

  

## Table of Contents

  

*  **[Features](#features)**

  

*  **[Supported Platforms](#supported-platforms)**

  

*  **[Demo Installation Guide](#demo-installation-guide)**

<br>

  

## Features

  

The OnnPlayer™ for Unity WebGL video streaming player plugin contains the latest features. As our Unity video plugin is developed entirely in-house, we can implement any desired functionalities.

  

We support the following features:

  

<table>

<tbody  style="text-align:center;">

<tr>

<td  valign="top"  style="text-align:center;">

<p  style="max-width:100%;"><b>Overview</b></p>

</td>

<td>

<ul>

<li>mp4 download and playback</li>

<li>HLS & DASH Streaming with ABR (Adaptive Bitrate)</li>

<li>AES-128 HLS</li>

<li>Widevine DRM for Streaming</li>

<li>Fairplay DRM for Streaming</li>

<li>Up to 8K (UHD) Resolution</li>

<li>Rendering Videos on 2D & 3D Objects</li>

</ul>

</td>

<tr>

<td  valign="top"  style="text-align:center;">

<p  style="max-width:100%;"><b>Basic Features</b></p>

</td>

<td>

<ul>

<li>Auto Playback</li>

<li>Play / Pause</li>

<li>Seek</li>

<li>Audio Volume Adjustment</li>

<li>Loop Playback</li>

<li>Configurable Aspect Ratio</li>

<li>Portrait / Landscape Orientation</li>

</ul>

</td>

</tr>


</tbody>

</table>

  

## Supported Platforms

| Platform | Supported Graphics APIs | HLS | DASH | Fair Play | Widevine |
| :-----:| :-----:| :-----:| :-----:| :-----:| :-----:|
| Android chrome | WebGL 2.0 | :heavy_check_mark: | :heavy_check_mark: | | :heavy_check_mark: | :heavy_check_mark: |
| iOS Chrome | WebGL 2.0 | :heavy_check_mark: | :heavy_check_mark: |  | :heavy_check_mark: | :heavy_check_mark: |
| Windows Chrome | WebGL 2.0 | :heavy_check_mark: | :heavy_check_mark: |  | :heavy_check_mark: |
|macOS Chrome|WebGL 2.0|:heavy_check_mark:|:heavy_check_mark:||:heavy_check_mark:|
|iOS Safari|WebGL 2.0|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|
|macOS Safari|WebGL 2.0|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:||
  

## Demo Installation Guide

###  In a new Unity metaverse application,  
- **Assets > Import package > Custom Package and select OnnetVideoPlayer.package**
<img  src="./resources/1-1.png"  width="95%"  height="95%">
<img  src="./resources/1-2.png"  width="95%"  height="95%">
<img  src="./resources/1-3.png"  width="95%"  height="95%">

### Create New Quad Object and assign a name to the quad object
<img  src="./resources/2-1.png"  width="95%"  height="95%">
<img  src="./resources/2-2.png"  width="95%"  height="95%">

### Attach a box collider component to the quad game object and set IsTrigger property to true.
<img  src="./resources/3-1.png"  width="95%"  height="95%">
<img  src="./resources/3-2.png"  width="95%"  height="95%">

### Add New component to the quad object and select Onnet Video Player script.
<img  src="./resources/4.png"  width="95%"  height="95%">

### Fill the details in Player component
<img  src="./resources/5.png"  width="95%"  height="95%">

### Set the metaverse application to use the custom webgl template by following the step below.
    

-   In Unity 2019.4.30f1 Editor, Go to Player settings  
    (menu: Edit > Project Settings > Player), and set the platform-specific settings to WebGL.
    
-   Open Resolution and Presentation.
    
-   Under WebGL Template Select Onnet Template

<img  src="./resources/6.png"  width="95%"  height="95%">

### Create a new material with shader property as Unlit/texture and assign this material to the new quad object’s mesh renderer
<img  src="./resources/7-1.png"  width="95%"  height="95%">
<img  src="./resources/7-2.png"  width="95%"  height="95%">
  
  

## Contact

[Onnet Systems](mailto:contact@onnetsystems.net)
