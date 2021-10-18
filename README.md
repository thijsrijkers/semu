<p align="center"><img src="https://i.imgur.com/Bb6kZIH.png" width="260" height="110"> </p>

<h3 align="center">SeMu</h3>

## Introduction

SeMu is a little open source project that is targeted to emulate the orignal Nintendo Switch (before the revision). The target of the project as a hole is to learn to emulate the switch in a C++ enviroment and leaviing enough room to expand on the application. 

## Installation

Once you have Node.js installed:

```shell
# Get the project:
git https://github.com/thijsrijkers/semu.git
```

## Hardware

These are the leaked hardware specs of the switch:

<table>
<thead>
<tr>
<th>Item</th>
<th>Hardware specification</th>
<th>Functionality</th>
</tr>
</thead>
  
<tbody>
  
<tr>
<td>CPU</td>
<td>Four ARM Cortex-A57 cores, max 2 GHz
L2 cache, 2 MB
64-bit ARMv8
Crypto-extensie on</td>
<td>three cores</td>
</tr>
  
<tr>
<td>GPU</td>
<td>Nvidia second gen Maxwell-architecture
256 cuda-cores, max 1 GHz
1024 FLOPS/cyclus
Texture: 16 pixels/cyclus
Fill: 14.4 pixels/cyclus</td>
<td>TBD</td>
</tr>
  
<tr>
<td>Video Decoder</td>
<td>H.265 (3840×2160 60 fps)
H.264 (3840×2160 60 fps)
VP9 (3840×2160 60 fps)
VP8 (3840×2160 60 fps)
Mpeg4 (1920×1080 120 fps)
Mpeg2 (3840×2160 60 fps)</td>
<td>Supports H.264, VP9, VP8.</td>
</tr>

<tr>
<td>Main Memory</td>
<td>Capacity: 4 GB, Bandwidth: 25.6 GB/s, VRAM: Shared</td>
<td>Capacity: 3,25GB</td>
</tr>

  
<tr>
<td>System Memory</td>
<td>Capacity: 32 GB, Max transfer rate: 400 MB/s</td>
<td>Used as location for saving save data</td>
</tr>
  
</tbody>
</table>
<p><b><a href="https://assets.vg247.com/current//2017/02/switch_specs_leak_feb_1.png" target="_blank">Specifications</a></b></p>
