<h3 align="center">Windows 11 Custom Setup</h3>

<p align="center">
My personal Windows 11 setup — tuned for a minimal, productive workflow with a clean, consistent look.  
Built around GlazeWM, YASB, and a few small tweaks that make the system feel smoother.  
Big shout-out to <a href="https://github.com/SleepyCatHey">SleepyCatHey</a> for sparking the idea.
</p>

---

🎨 **Theme:** [Catppuccin Mocha](#catppuccinmocha)  
🖋️ **Font:** [JetBrainsMono Nerd Font](#jetbrainsmononerdfont)

---

# Overview

## 📏 YASB

> [!NOTE]  
> Some parts of my config need your own setup — like the API key for the weather widget or the path to your wallpaper folder.

YASB (Yet Another Status Bar) is a customizable status bar for Windows written in Python. I use it to show system stats, media info, and some custom widgets.

**⚙️ Setup**
- Download and install [**YASB**](https://github.com/amnweb/yasb)
- Copy the files from my config folder  
- Adjust your API keys and wallpaper path  
- Restart YASB

---

## 🪟 GlazeWM + YASB

> [!NOTE]  
> My setup uses GlazeWM with YASB. If you want to use Zebar instead, you’ll need to re-add the two lines I’ve removed in the config.

GlazeWM is a tiling window manager for Windows — it keeps windows organized and keyboard-friendly. I use it together with YASB for a seamless layout and bar integration.

**⚙️ Setup**
- Install [**GlazeWM**](https://github.com/glzr-io/glazewm)
- Replace the default config with mine  
- Restart GlazeWM and fine-tune keybindings if needed

---

## 🦅 Windhawk

> [!NOTE]  
> My taskbar mod hides the Start menu and network icon by default.  
> If you prefer to keep them visible, check out  
> [this guide](https://github.com/ramensoftware/windows-11-taskbar-styling-guide).

Windhawk is a mod manager for Windows that lets you tweak system elements without heavy tools. I use it for subtle UI adjustments — mainly the taskbar and system tray.

---

## 👾 Terminal + Fastfetch

> [!NOTE]  
> If you see the error *“execution of scripts is disabled on this system”*, open PowerShell as admin and run:  
> `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser -Force`

Fastfetch is a fast, neofetch-style tool for showing system info. Combined with the Windows Terminal and a clean PowerShell profile, it creates a lightweight dashboard when opening a new shell.

**⚙️ Setup**
- Install [**Fastfetch**](https://github.com/fastfetch-cli/fastfetch/releases)
- Copy my PowerShell profile, terminal settings, and Fastfetch config  
- Place the Fastfetch config and ASCII art in  
  `C:\Users\<your-username>\.config\fastfetch`
- Update any file paths or usernames in the configs  
- Restart Terminal

---

This setup is built to stay clean — minimal visuals, fast workflow, and a consistent aesthetic across the system.
