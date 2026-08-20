[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://github.com/chris1111/Workshop-Layered-Image-Studio/blob/main/LICENSE) [![pages-build-deployment](https://github.com/chris1111/Workshop-Layered-Image-Studio/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/chris1111/Workshop-Layered-Image-Studio/actions/workflows/pages/pages-build-deployment)
# Workshop Layered Image Studio

## Start using ➢ [Workshop Layered Image Studio](https://chris1111.github.io/Workshop-Layered-Image-Studio/)

### The Workshop is a lightweight, privacy-first, browser-based image compositing tool designed for stacking and manipulating transparent images (like PNGs) with pixel-perfect precision.
    A Mini Photopshop free 🫶🏻

## Its core purposes are:

- Layering: Stack multiple images on top of each other, managing their front-to-back order effortlessly.
- Precise Transformation: Move, resize, and rotate layers visually with the mouse or manually via exact X/Y coordinates and W/H pixel inputs.
- Perfect Exports: Uses a "smart-crop" feature to export the final composition exactly to the size of the visible content—meaning no unwanted background canvas, just a perfectly fitted, transparent PNG.
- 100% Local Processing: Everything happens directly in the user's browser. No data is ever uploaded to a server, ensuring complete privacy and instant performance.

#### A free easy way for those who have virtually no knowledge of graphic design. they are the perfect tools for creating themes icons sets for OpenCore or Clover ➦ Combined with this tools ➥ [Icon-Studio](https://chris1111.github.io/Icon-Studio/) ➥ [Image Resizer](https://chris1111.github.io/Image-Resizer/) 


## List Update: ⬇︎
<details> 
  <summary>View Update</summary>


### Updated 20 Aug 2026

        1       Adds an Export Padding slider to the UI and wires it into export state, reset behavior, and live value display. 
        2       Export rendering now expands the output canvas by padding on all sides while clipping content to the original selected bounds, enabling transparent or background-colored margins around exported images. 
        3       Also includes minor wording/comment cleanups in document and history hints.

---------------------------------

### Updated 19 Aug 2026

	1	Redo — button + Ctrl+Shift+Z / Ctrl+Y
	2	Flip H/V — rail buttons, resize math corrected for flipped corners
	3	Arrow-key nudge — 1px per press, 10px with Shift
	4	Rename layer — pen icon ✏️ or double-click the name (Enter saves, Esc cancels)
	5	Ctrl+D — duplicate shortcut
	6	Checkerboard — transparency checker behind the document
	7	Blend modes — 16 modes, baked into export
	8	Adjustments — Brightness / Contrast / Saturation / Blur / Grayscale / Sepia, non-destructive, in export & saved projects
	9	Export panel — PNG / JPEG / WebP · 1×/2×/3× · quality slider · transparent toggle + background color · custom filename
	10	Merge Down + Flatten — bakes blend/rotation/shadows/adjustments into one layer
	11	Align tools — Left / Right / H-Center / Top / Bottom / V-Middle, rotation-aware
	12	Pan the view — Space + drag or middle-mouse drag
	13	Grid + snapping — toggleable grid, snap for drag and arrow nudge, adjustable size
	14	Crop tool — screen-space overlay with live size label, floating Apply/Cancel, Enter/Esc, guides shift with crop, document auto-clips content, export always matches (the fix we just polished)
	15	Text layers — T key or "A" rail button; content, 9 fonts, size, color, bold/italic; double-click text on canvas to edit; full transform/blend/shadow/adjustment support; saved in projects
	16	Layer masks — non-destructive; Brush hides (or shows), Eraser reveals; Apply bakes / Remove discards; survives undo, duplicate and Save/Load
	17	Custom document size — presets (Instagram, Story/Reel, YouTube thumbnail, Full HD…) + custom W/H + Center All; oversized images auto-enlarge the document instead of spilling
	18	Rulers & guides — drag from rulers to create cyan guides; drag back into ruler or double-click to delete; layers snap edges/centers while dragging or nudging; Clear All Guides button


---------------------------------
	
### Updated 17 Aug 2026

	1	Shadow Settings  🌑
	◦	You now have full control over drop shadows! You can adjust the Offset X/Y, Blur, Opacity, and Color of the shadow for any selected layer.
	◦	These custom shadows are perfectly baked into your final exported PNG!
	2	Drawing & Painting Tools 🖌️
	◦	Brush Tool (B): Freehand draw with any color. You can switch between a Circle or Square brush tip, and adjust the size with a slider.
	◦	Shape Tool (S): Click and drag to draw perfect Rectangles or Ellipses in your chosen color.
	3	Gradient Tool 🌈
	◦	Pick two colors, choose Linear or Radial, and click a button to generate a brand new, fully transformable gradient layer! (The radial gradient now draws a perfect circle with transparent corners).
	4	Eraser Tool 🧽
	◦	Erase parts of any image with a circular brush. Comes with an "Undo" button and a "Restore Layer" option to bring back the original image if you make a mistake.
	5	Smart Templates 📂
	◦	Save Template: Saves your layout (positions, sizes, rotations) without the image data as a tiny .json file.
	◦	Load Template: Rebuilds your layout with "Empty Slots". Just drag in new images, and they will automatically snap into the exact positions of your template!
	6	Precision Position & Size 🔢
	◦	Added numeric input boxes for exact X, Y, W, and H pixel values so you can position layers perfectly.
	◦	Added an Aspect Ratio lock toggle to prevent stretching when resizing manually.
	7	Perfect PNG Export 🖼️
	◦	True to Size: Exported images are now exactly the size of the visible content (no more 900x560 background canvas!).
	◦	100% Transparent: The brown background is completely gone in the exported file.
	◦	Every new layer will now start with no visible shadow, and the panel sliders will show 0px blur and 0% opacity on selection.

---------------------------------
	
	

</details>

	
