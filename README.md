<h1 align="center">Windows Rice</h1>

<p align="center">
<i>A personal, ever-evolving Windows customization project.</i>
<br>

> [!NOTE]
>This repository contains my personal Windows rice: a collection of applications, tools, configurations, and visual tweaks that come together to create my ideal desktop experience.
The setup is heavily inspired by the customization and ricing communities, with a focus on aesthetics, functionality, and a comfortable workflow.
It's a continuous work in progress. Things will change, new tools will be added, and old ones might eventually be replaced.

</p>

<p align="center">
<img src="https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows" alt="Platform: Windows">
<img src="https://img.shields.io/badge/Status-Evolving-9cf?style=for-the-badge" alt="Status: Evolving">
<img src="https://img.shields.io/badge/Made%20with-The%20Power%20Of%20Friendship-brown?style=for-the-badge" alt="Made with the power of friendship">
</p>

---

### ℹ️ Whole System Info

Here is all the information about my setup:

<details>
	
<summary>🪟 <b>System</b></summary>

<br>

| 📚 Entry              	 | ✨ App                  |
|--------------------------|--------------------------|
| **OS** 				 				   | [Windows 11](https://www.microsoft.com/en-in/windows/windows-11) + [WSL2](https://learn.microsoft.com/en-us/windows/wsl/) |
| **WSL Distro**           | [Arch btw](https://wiki.archlinux.org/title/Install_Arch_Linux_on_WSL) |
| **Window Manager** 			 | Fork of [GlazeWM](https://github.com/glzr-io/glazewm) |
| **Bar** 				 				 | [Animated YASB](https://github.com/darco-ctrl/AnimatedYasb) |
| **Mods** 				 				 | 💖 [Windhawk](https://windhawk.net/) |
| **App Launcher**         | [Flow Launcher](https://github.com/Flow-Launcher/Flow.Launcher) and/or [wisp](https://github.com/SumirSeth/wisp)|
| **Dock**                 | [Wisp](https://github.com/SumirSeth/wisp) |

</details>

<details>
	
<summary>🖥️ <b>CLI/TUI Apps</b> </summary>

<br>

Configs for these can be found in [**dotfiles**](https://github.com/96raf1/Windows-rice/tree/main/.config)

| 📚 Entry                           	 | ✨ App                  |
|----------------------------------------|--------------------------|
| **Shell**                              | 💖 [Powershell 7] |
| **Terminal Emulator**                  | [Windows Terminal](https://github.com/microsoft/terminal) |
| **Shell Prompt**                       | [Starship](https://github.com/starship/starship) |
| **Text Editor**                        | [VSCodium](https://vscodium.com/) |
| **File Manager**                       | [File Pilot](https://filepilot.tech/) |
| **Git**                                | [git](https://git-scm.com/) [⚙️](https://github.com/ashish0kumar/dotfiles/tree/main/.config/git) |
| **Git TUI**                            | [lazygit](https://github.com/jesseduffield/lazygit) |
| **System Monitor**                     | [Rice-dash](https://github.com/HonourableAF/rice-dash) and [btop4win](https://github.com/aristocratos/btop4win)|
| **System Fetch**                       | [fastfetch](https://github.com/fastfetch-cli/fastfetch) |
| **Audio Visualizer** 			 		         | [cava](https://github.com/karlstav/cava) |

</details>

<details>
	
<summary>🖱️ <b>GUI Apps</b></summary>

<br>

| 📚 Entry                           	 | ✨ App                  |
|----------------------------------------|--------------------------|
| **Web Browser**               	 	     | [Helium](https://github.com/imputnet/helium) and [Zen-Browser](https://zen-browser.app) |
| **Helium Startpage**
| **Office Apps**                     	 | [LibreOffice](https://www.libreoffice.org/) |

</details>
 
<details>
	
<summary>🔍 <b>Other</b></summary>

<br>

| 📚 Name | ✨ Source |
|-------------------------|------------|
| **Color scheme**        | [Matugen](https://github.com/InioX/matugen) |
| **Wallpaper**           | Mostly from [Youtube](https://youtube.com) |
| **Fonts**               | [JetbrainsMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip) |

</details>
 
# ⚡ Details

## 📏 YASB
> [!NOTE] 
> Some stuff in my config might not work if you just copy and paste it. Be sure to add your wallpaper folder location for the wallpapers widget.
> Furthermore, this is a fork of YASB. If you simply want Amnweb's YASB, go [Here](https://github.com/amnweb/yasb).
> None of the colors of my YASB CSS are hardcoded; rather, matugen extracts from the wallpaper.

A highly configurable Windows status bar written in Python. 

**⚙️ Installation:**  
You can follow the steps below, or jump to Sam's [**setup video**](https://www.youtube.com/watch?v=YVCK3z-eLvk).
- Install [**Animated YASB**]([(https://github.com/darco-ctrl/AnimatedYasb)])   
- Copy the config files from [**here**]().
- Remove the codes from **your** YASB config and paste the one you just copied.
- Restart **YASB** for the changes to take effect. YASB should automatically restart, so you shouldn't worry on that.

---

## 🪟 GlazeWM + YASB
> [!NOTE] 
> If your using my config then Zebar won't work as I use GlazeWM with YASB. I recommend adding those 2 lines of code back which I had deleted if you wanna use Zebar.
> I do not use the default GlazeWM, rather, my friend Radiant Moth has provided me with his fork.
> If you notice anything different between your GlazeWM and mine, it's probably because I'm using a fork.

GlazeWM lets you easily organize windows and adjust their layout on the fly by using keyboard-driven commands.  

**⚙️ Installation:**  
You can follow the steps below, or jump to Sam's [**setup video**](https://youtu.be/b57zFm3nVxA).
- Install [**GlazeWM**](https://github.com/glzr-io/glazewm)   
- Copy the config file from [**here**]().
- Remove the codes from **your** GlazeWM config and paste the one you just copied.
- Restart **GlazeWM** for the changes to take effect.

---

<p align="center">
The rest of the applications and CLIs should have simple and easy to follow guides, so just follow them. Besides, Sam (Sleepycathey) already made tutorials on this, so you shouldn't struggle too hard.
</p>

---

 many of the applications, configs, and inspiration have been provided to me by and/or inspired by my friends, so check them out!
of course, I did make some stuff myself, like most of the matugen templates, though Bullet helped me initially.

<details>
	
<summary>🪟 <b>Credits</b></summary>

<br>

Credit and special thanks to the friends I made along the way:
- 🐜 Bullet Ant
- 🐈 [Sam](https://github.com/SleepyCatHey)
- 🦋 [Radiant Moth](https://github.com/v0id-joker)
- [Darklore Aether](https://www.youtube.com/channel/UCEbNE-5Hwgr_IyNroER2NpA)
- Yamii
- [Nonamenguyen](https://github.com/NonameNguyeen)
- [Nephren](https://github.com/NephVx2)
- [Livesyedd](https://github.com/NitroBeast76)
- [Ben](https://github.com/bobpyyylz)
- Histy
- HighCaillou
- Cesium
- [Frost](https://github.com/Shadowniko1)
- Karma
- Haiku
- [Pivux](https://x.com/PivuxD)
- Derivative
- [Nobody](https://github.com/xfa3k)
- Jack Hex
- Darius
- Froggo
- E
- L
- Penguin
- 7丁卄_卩尺ㄖ丁ㄖ匚ㄖㄥ
and the rest of the [Sleeping Cult](https://discord.gg/sustkTynuB)!!!

<br>

Credit also goes to:
- Random people on Reddit
- Random people on Youtube
- 


</details>

---
## PS: This README is a fork lol
