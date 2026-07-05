WIP

Y2K Zones
Interactive Y2K Glam Video Effects Tool
Apply nostalgic Year 2000 aesthetic effects to your videos.

Features
- 5-Step Interactive Editor: Configure effects through OpenCV GUI
- Blur Zones: Gaussian blur with pink/lilavender/mint tints
- Animated Glitter: Twinkling sparkles with starburst effect
- Frosted Glass: Y2K-style matte glass with iridescence
- Vintage Dust: Film grain + desaturation + vignette
- Color Filters: Pink/Lilac/Emerald/Cyan/Gold overlays
- Audio Preservation: Auto-extracts and merges audio via ffmpeg

Installation
Prerequisites
Python dependenciespip install opencv-python numpy
For audio supportbrew install ffmpeg

Quick Install
git clone https://github.com/YOURUSER/y2k-zones.git
cd y2k-zones
chmod +x bin/y2k-zones install.sh
./install.sh

Usage
# Basic usage (output: input_y2k.mp4)
y2k-zones video.mov

# Custom output name
y2k-zones video.mov output.mp4

Interactive Workflow
Step 1 - Blur Zone: Paint areas → adjust strength/color → Enter
Step 2 - Glitter Zone: Paint areas → set density/glow/color → Enter
Step 3 - Glass Zone: Paint areas → adjust strength/transparency → Enter
Step 4 - Vintage Dust: Toggle on/off → set intensity → Enter (global)
Step 5 - Color Filter: Choose color swatch → set intensity → Enter (global)

