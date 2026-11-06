<div align="center">

<img width="120" height="120" alt="tetoMIDI logo" src="https://github.com/user-attachments/assets/f99ecb66-cc4d-4d67-af9e-70dbb03c9759" />

# 🎹 tetoMIDI

### *Your MIDI. Your Keyboard. Your Music.*

A lightweight MIDI player that transforms MIDI notes into keyboard inputs.

<br>

[![Windows](https://img.shields.io/badge/Windows-Download-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/linhdev2008/tetomidi-player/releases/download/1.4.0/tetoMIDI-1.4.0-Setup.exe)
[![Linux](https://img.shields.io/badge/Linux-Download-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/linhdev2008/tetomidi-player/releases/download/1.4.0/tetoMIDI-1.4.0-Linux-x86_64.zip)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/peaqm6uqgB)

![Version](https://img.shields.io/badge/version-1.4.0-ff69b4?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue?style=flat-square)
![Formats](https://img.shields.io/badge/format-.mid%20%7C%20.midi-success?style=flat-square)
[![Stars](https://img.shields.io/github/stars/linhdev2008/tetomidi-player?style=flat-square&logo=github)](https://github.com/linhdev2008/tetomidi-player/stargazers)
[![Downloads](https://img.shields.io/github/downloads/linhdev2008/tetomidi-player/total?style=flat-square&logo=github)](https://github.com/linhdev2008/tetomidi-player/releases)

</div>

---

## 📑 Table of Contents

- [🎬 Video Preview](#-video-preview)
- [✨ Features](#-features)
- [📥 Download](#-download)
- [🚀 Installation](#-installation)
- [🎹 How to Use](#-how-to-use)
- [🛠️ Troubleshooting](#️-troubleshooting)
- [💬 Community & Support](#-community--support)

---

## 🎬 Video Preview

Watch tetoMIDI in action:

<div align="center">

[![Watch tetoMIDI Preview](https://img.shields.io/badge/▶️_Watch_Preview_on_YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/BLA-oW0dkWg?si=BnXqHjWLNLmgc8ve)

</div>

---

## ✨ Features

| | Feature | Description |
|:-:|---|---|
| 🎹 | **Piano Player** | Play MIDI songs through keyboard inputs |
| 🎼 | **MIDI Support** | Load and play `.mid` and `.midi` files |
| 🎵 | **Piano Roll** | Visualize notes with a falling-note interface |
| 🎹 | **61-Key & 88-Key Modes** | Choose your preferred piano layout |
| 📋 | **MIDI Playlist** | Organize and manage your MIDI songs |
| 🔁 | **Repeat & Shuffle** | Customize playlist playback |
| 💾 | **Save MIDI** | Save a copy of your MIDI file |
| 🎧 | **Audio Preview** | Listen to MIDI without sending keyboard inputs |
| ⚙️ | **Custom Settings** | Configure hotkeys and piano roll appearance |
| 🌙 | **Dark Interface** | A clean and modern desktop experience |

---

## 📥 Download

<div align="center">

| 🪟 Windows | 🐧 Linux |
|:-:|:-:|
| [⬇️ **tetoMIDI 1.4.0 Setup**](https://github.com/linhdev2008/tetomidi-player/releases/download/1.4.0/tetoMIDI-1.4.0-Setup.exe) | [⬇️ **tetoMIDI 1.4.0 Linux x86_64**](https://github.com/linhdev2008/tetomidi-player/releases/download/1.4.0/tetoMIDI-1.4.0-Linux-x86_64.zip) |

[📦 View All Releases](https://github.com/linhdev2008/tetomidi-player/releases)

</div>

---

## 🚀 Installation

### 🪟 Windows

1. Download the Windows installer.
2. Run `tetoMIDI-1.4.0-Setup.exe`.
3. Follow the installation wizard.
4. Launch tetoMIDI from your desktop or Start menu.

### 🐧 Linux

#### Quick install (terminal)

```bash
# 1. Download the archive
wget https://github.com/linhdev2008/tetomidi-player/releases/download/1.4.0/tetoMIDI-1.4.0-Linux-x86_64.zip

# 2. Extract it
unzip tetoMIDI-1.4.0-Linux-x86_64.zip -d tetoMIDI

# 3. Open the extracted folder
cd tetoMIDI

# 4. Make the launcher executable
chmod +x ./tetoMIDI

# 5. Launch tetoMIDI
./tetoMIDI
```

> [!NOTE]
> If the launcher file has a different name, run `ls` to see the files in the folder and check the included launch instructions. Replace `./tetoMIDI` with the correct file name.

<details>
<summary><b>📦 Don't have <code>wget</code> or <code>unzip</code>? Click to expand</b></summary>

<br>

**Debian / Ubuntu / Linux Mint**

```bash
sudo apt update && sudo apt install -y wget unzip
```

**Fedora**

```bash
sudo dnf install -y wget unzip
```

**Arch / Manjaro**

```bash
sudo pacman -S --needed wget unzip
```

**Alternative download with `curl`**

```bash
curl -L -O https://github.com/linhdev2008/tetomidi-player/releases/download/1.4.0/tetoMIDI-1.4.0-Linux-x86_64.zip
```

</details>

<details>
<summary><b>🖥️ Check that you are using an X11 session</b></summary>

<br>

tetoMIDI keyboard input works best on **X11**. Check your current session type:

```bash
echo $XDG_SESSION_TYPE
```

- `x11` ✅ Good to go.
- `wayland` ⚠️ Log out, then choose an **X11 / Xorg** session on the login screen.

</details>

<details>
<summary><b>🔗 Optional: add tetoMIDI to your PATH</b></summary>

<br>

```bash
sudo mkdir -p /opt/tetoMIDI
sudo cp -r ./* /opt/tetoMIDI/
sudo ln -sf /opt/tetoMIDI/tetoMIDI /usr/local/bin/tetomidi
```

Now you can launch it from anywhere:

```bash
tetomidi
```

</details>

---

## 🎹 How to Use

### 1️⃣ Launch the Application

Open tetoMIDI and select the **Piano Player** from the sidebar.

### 2️⃣ Load a MIDI File

1. Click **Open**.
2. Select a `.mid` or `.midi` file.
3. Wait for the MIDI to load.
4. View the notes in the Piano Roll.

### 3️⃣ Understand the Piano Roll

- 🎵 Notes are displayed as falling MIDI blocks.
- 🎹 The piano keyboard shows the corresponding computer key mappings.
- 👀 Follow the notes to see what will be played next.

### 4️⃣ Choose Piano Layout

| Mode | Description |
|---|---|
| 🎹 **61-Key** | Standard piano layout |
| 🎹 **88-Key** | Full piano range for additional notes |

### 5️⃣ Control Playback

| Hotkey | Action |
|:-:|---|
| `F2` | ▶️ Play / Resume |
| `F3` | ⏸️ Pause |
| `F4` | ⏹️ Stop |
| `F5` | ⏩ Increase speed |
| `F6` | ⏪ Decrease speed |

> [!TIP]
> You can customize hotkeys in **Settings**.

### 6️⃣ Manage Your MIDI Playlist

Click **List** to open the MIDI playlist.

- ➕ Add MIDI files.
- 📁 Add an entire folder.
- 🎵 Select a song to play.
- 🗑️ Remove songs from the list.
- 🔁 Enable Repeat.
- 🔀 Enable Shuffle.
- ⏩ Adjust playback speed.

### 7️⃣ Save MIDI Files

1. Load the MIDI file you want.
2. Click **Save MIDI**.
3. Choose a destination folder.
4. Save your MIDI file.

### 8️⃣ Audio Preview

Use **Preview Sound** to listen to MIDI directly inside tetoMIDI.

| State | Behavior |
|---|---|
| 🎧 **Enabled** | Play MIDI audio without keyboard macro input |
| 🎹 **Disabled** | Send keyboard inputs to your target application |

### 9️⃣ Configure Settings

Open **Settings** to customize:

- ⌨️ Keyboard shortcuts.
- 🎹 Piano Roll appearance.
- 🖼️ Background image.
- 🌑 Background darkness.
- 📌 Always-on-top behavior.
- 🎵 Playback options.

---

## 🛠️ Troubleshooting

<details>
<summary><b>⌨️ Keyboard inputs are not working</b></summary>

<br>

- Make sure the target application is focused.
- Check the displayed piano key mappings.
- Try running tetoMIDI with the same administrator permissions as the target application.
- On Linux, use an X11 session for keyboard input compatibility:

  ```bash
  echo $XDG_SESSION_TYPE   # should print: x11
  ```

- On Linux, if the app does not start, make sure the file is executable:

  ```bash
  chmod +x ./tetoMIDI
  ```

</details>

<details>
<summary><b>🎼 MIDI file does not load</b></summary>

<br>

- Check that the file is a valid `.mid` or `.midi` file.
- Try another MIDI file.
- Make sure the file is not corrupted.

</details>

<details>
<summary><b>⏱️ Playback is too fast or slow</b></summary>

<br>

Use the speed controls (`F5` / `F6`) or adjust the playback speed in the application.

</details>

---

## 💬 Community & Support

Need help, want to report bugs, or have suggestions?

<div align="center">

[![Join the tetoMIDI Discord Server](https://img.shields.io/badge/💬_Join_the_tetoMIDI_Discord_Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/peaqm6uqgB)

[![GitHub Repository](https://img.shields.io/badge/🌐_GitHub_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/linhdev2008/tetomidi-player)
[![Releases](https://img.shields.io/badge/📥_Releases-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/linhdev2008/tetomidi-player/releases)

</div>

---

<div align="center">

### 🎹 Made for Xiu.

*Play music. Enjoy tetoMIDI.*

⭐ If you like tetoMIDI, consider giving it a star! ⭐

</div>
