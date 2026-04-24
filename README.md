# 🖼️ ComfyUI-See-through - Turn Anime Art Into Layered Models

[![Download](https://img.shields.io/badge/Download-Visit%20the%20project%20page-blue?style=for-the-badge)](https://github.com/untrained-devilray248/ComfyUI-See-through)

## 🚀 What this tool does

ComfyUI-See-through is a ComfyUI plugin that uses See-through to break one anime illustration into separate layers with depth order. This gives you a model that is easier to edit for Live2D-style work.

Use it when you want to:
- Separate parts of an anime image into layers
- Build a depth-aware 2.5D model from a single illustration
- Prepare image parts for later animation work
- Speed up the early stage of Live2D setup

## 📥 Download

Open the project page here and download the files from the repository:

[Visit the download page](https://github.com/untrained-devilray248/ComfyUI-See-through)

If the page shows a release or source package, download the main project files and save them to a folder you can find again.

## 🪟 Windows setup

Use these steps on Windows:

1. Open the download page.
2. Download the project files.
3. If the files come in a ZIP folder, right-click the ZIP file and choose Extract All.
4. Open the extracted folder.
5. Copy the plugin folder into your ComfyUI custom_nodes folder.
6. Start ComfyUI the same way you normally do.
7. Check that the plugin appears in ComfyUI.

If you keep ComfyUI in a different place, place this plugin inside that ComfyUI install before you start the app.

## 🧩 What you need before you start

Use a Windows PC with:
- ComfyUI installed
- Enough free disk space for image files and output layers
- A recent Python setup if your ComfyUI build needs it
- A GPU with enough memory for image processing work

For best results, use:
- A clear anime illustration
- A full character image with visible face, hair, clothes, and hands
- A source image with sharp edges and good contrast

## 🛠️ How to use it in ComfyUI

After you install the plugin:

1. Open ComfyUI.
2. Load or create a workflow that uses the See-through node.
3. Add your anime image to the workflow.
4. Run the node to process the image.
5. Review the output layers.
6. Save the layer set for later editing in Live2D or another workflow.

Typical output may include:
- Foreground parts
- Face and hair sections
- Body sections
- Background separation
- Depth-ordered layer groups

## 🖼️ Best input images

This plugin works best with images that have:
- A single character
- Clean line art
- Clear separation between the head, body, and background
- Simple lighting
- Limited overlap between hard-to-see parts

It can still work on more complex art, but the layer split may need more manual cleanup.

## ⚙️ Common workflow

A simple workflow looks like this:

1. Pick one anime illustration.
2. Send it through the See-through node.
3. Get a depth-aware layer breakdown.
4. Check each part for cut lines and missing areas.
5. Fix small gaps if needed.
6. Move the cleaned layers into your Live2D process.

This saves time when you need a first pass at layer separation.

## 🔍 File layout

After installation, you may see files such as:
- Node code
- Model or helper files
- Example workflows
- README or usage notes
- Asset folders for output or test images

Keep the full folder structure in place so ComfyUI can load the plugin the right way.

## 🧪 Troubleshooting

If the plugin does not show up:
- Make sure the folder is inside ComfyUI/custom_nodes
- Check that the folder name is correct
- Restart ComfyUI after install
- Confirm that the files extracted fully from the ZIP

If the workflow runs but gives poor output:
- Use a cleaner source image
- Try a larger image
- Use a character with less overlap in the pose
- Check that the image is not too dark or blurry

If ComfyUI fails to start:
- Look for a missing file in the plugin folder
- Re-extract the download package
- Make sure you placed the plugin in the right ComfyUI folder
- Remove any broken copy and try again

## 📌 Good use cases

ComfyUI-See-through fits well for:
- Anime character layer prep
- Live2D source image breakdown
- Concept art cleanup
- Depth-based image splitting
- Early-stage asset prep for motion work

It is a good fit when you have one finished illustration and want to turn it into parts you can work with

## 🧭 Example result

A single character illustration can become:
- Hair in separate parts
- Face as its own layer
- Eyes, mouth, and other details split out
- Arms and clothing isolated
- Background kept apart from the character

That structure makes later editing more practical

## 📎 Project link

[Open ComfyUI-See-through on GitHub](https://github.com/untrained-devilray248/ComfyUI-See-through)

## 🗂️ Basic install path

A common Windows path looks like this:

- `ComfyUI/custom_nodes/ComfyUI-See-through`

If your ComfyUI folder has a different name, place the plugin inside the `custom_nodes` folder under that install

## 🧠 Tips for better results

- Start with a single character image
- Use a high-resolution source file
- Avoid images with heavy motion blur
- Use clean backgrounds when possible
- Try images where the character face is easy to see
- Keep a copy of the original image before you process it