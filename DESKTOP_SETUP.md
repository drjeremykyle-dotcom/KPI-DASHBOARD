# 🖥️ Desktop Setup - Quick Start

Get the KPI Dashboard running on your desktop in **30 seconds** or less.

---

## ⚡ Ultra-Quick Setup (All Platforms)

### Windows Users
1. Download the repo (Green `Code` → Download ZIP)
2. Unzip the folder
3. **Right-click `launch-dashboard.bat`** → Create shortcut
4. Move to Desktop
5. **Double-click to launch!** 🚀

### macOS Users
1. Download the repo (Green `Code` → Download ZIP)
2. Unzip the folder
3. **Open Terminal** in the folder
4. Run: `chmod +x launch-dashboard.sh`
5. **Right-click `launch-dashboard.sh`** → Open With → Automator
6. Drag to Dock (optional)
7. **Click to launch!** 🚀

### Linux Users
1. Download the repo (Green `Code` → Download ZIP)
2. Unzip the folder
3. **Open Terminal** in the folder
4. Run: `chmod +x launch-dashboard.sh`
5. Create desktop entry (see INSTALL.md) or **double-click file**
6. **Click to launch!** 🚀

---

## 🎯 My Preferred Methods (By Platform)

### 🪟 Windows - Desktop Shortcut (Easiest)

**Step 1: Create Shortcut**
- Right-click Desktop → New → Shortcut
- Enter: `C:\Users\YourName\Downloads\KPI-DASHBOARD\index.html`
- Name it: `KPI Dashboard`
- Finish ✓

**Step 2: Optional - Add Icon**
- Right-click shortcut → Properties
- Click `Change Icon...`
- Pick a professional icon
- OK ✓

**Done!** Click to launch anytime.

**Alternative: Use Batch File**
- Download/unzip repo
- Right-click `launch-dashboard.bat` → Create shortcut
- Move to Desktop
- Done! Click to launch.

---

### 🍎 macOS - Automator App (30 Seconds)

**Step 1: Create App**
1. Open **Automator** (Applications → Utilities)
2. Create new: **Application**
3. Search for and add: **Open Finder Items**
4. Click: Add... → navigate to `index.html` in your KPI-DASHBOARD folder
5. Save as: `KPI Dashboard 2.0` (Applications folder)

**Step 2: Add to Dock** (Optional)
1. Open Applications folder
2. Drag `KPI Dashboard 2.0` to your Dock
3. Done!

**Launch:** Click the Dock icon or find in Applications folder.

**Quick Alternative:** 
```bash
chmod +x launch-dashboard.sh
open launch-dashboard.sh
```

---

### 🐧 Linux - Desktop Entry (60 Seconds)

**Step 1: Create Desktop File**
1. Open Terminal in KPI-DASHBOARD folder
2. Run:
```bash
chmod +x launch-dashboard.sh

# Create desktop entry
mkdir -p ~/.local/share/applications
cat > ~/.local/share/applications/kpi-dashboard.desktop << 'EOF'
[Desktop Entry]
Version=1.0
Type=Application
Name=KPI Dashboard 2.0
Comment=Renovation KPI Intelligence Dashboard
Exec=$HOME/path/to/KPI-DASHBOARD/launch-dashboard.sh
Icon=document-properties
Categories=Office;
Terminal=false
EOF
```

**Step 2: Update File Path**
- Edit the file above and replace `$HOME/path/to/KPI-DASHBOARD` with your actual path

**Launch:** Search for "KPI Dashboard" in your app menu and click!

---

## 🌐 Alternative: Browser App Mode (All Platforms)

For the most "native app-like" experience:

### Chrome/Chromium
```bash
# Windows (PowerShell)
chrome "C:\path\to\KPI-DASHBOARD\index.html" --app

# macOS
open -a "Google Chrome" file:///path/to/KPI-DASHBOARD/index.html --args --app

# Linux
google-chrome file:///path/to/KPI-DASHBOARD/index.html --app
```

This removes the browser UI for a cleaner app-like interface.

---

## 📌 Recommended Setup by Use Case

| Use Case | Best Method | Time |
|----------|-------------|------|
| **Just want it running** | Browser shortcut | ⭐ 30 sec |
| **Want an app-like feel** | Batch/Shell launcher | ⭐ 1 min |
| **Want it always accessible** | Dock/Taskbar pinned | ⭐ 2 min |
| **Professional setup** | PowerShell (Win) / App Bundle (Mac) | ⭐⭐ 5 min |

---

## ✅ Verification Checklist

After setup, verify:
- [ ] Shortcut/App launches the dashboard
- [ ] Dashboard loads in your browser
- [ ] All 8 tabs are visible and interactive
- [ ] Charts display correctly
- [ ] Can click between tabs smoothly
- [ ] Data is visible

---

## 🆘 Quick Troubleshooting

| Problem | Solution |
|---------|----------|
| **"File not found"** | Check the path in shortcut properties. Use full path, not relative. |
| **Opens in text editor** | Right-click HTML → Open With → Choose browser |
| **Script permission denied** | Run `chmod +x launch-dashboard.sh` in terminal |
| **Windows Defender warning** | Click "More info" → "Run anyway" |
| **Slow loading** | Clear browser cache (Ctrl+Shift+Del or Cmd+Shift+Del) |

---

## 🚀 Pro Tips

1. **Pin to Taskbar/Dock** - Right-click shortcut → Pin to taskbar
2. **Set keyboard shortcut** - Windows: Right-click → Properties → Shortcut key
3. **Create multiple shortcuts** - One for each version (full, educational, launcher)
4. **Works offline** - No internet needed after initial launch
5. **Sync across devices** - Share shortcut via cloud storage or email

---

## 📚 See Also

- **Full Installation Guide:** [INSTALL.md](INSTALL.md)
- **Main README:** [README.md](README.md)
- **Usage Guide:** [README.md#how-to-use](README.md#-how-to-use)

---

**Questions?** Check INSTALL.md for detailed step-by-step instructions for your platform.

**Last Updated:** May 17, 2026
