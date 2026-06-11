<img width="100%" alt="banner" src="https://github.com/user-attachments/assets/ee15c5c6-e9f4-49de-a6f7-c18970e839bc" />

# Song Tag

**An MP3 tag editor 🎵 for Windows and Linux that automatically edits ID3 metadata for audio files. It helps organize and modernize your music collection. ⚡**

Modernize and organize your music collection by fixing and enhancing song tags automatically.

This tool acts as a music metadata editor that processes MP3 files while you play 🎧 them. Features include:

<table>
  <tr>
    <td valign="top" width="220">
      <p align="center">
        <img width="165" alt="cover" src="https://github.com/user-attachments/assets/765fd3cf-e9e7-4f2e-b6fc-228fe92e7b2f" />
      </p>
    </td>
    <td valign="top">
      <ul>
        <li>Convert or create ID3v2.4 tags 🏷️ for files with missing or outdated metadata </li>
        <li>AI-powered filename parsing 🤖 to detect artist, album, and title </li>
        <li>etch album art 🖼️, lyrics 🎤, genre 🎼, and year 📅 from online sources</li>
        <li>Built-in MP3 tag editor ✏️ for manual metadata editing</li>
      </ul>
      <p>Unprocessed songs are shown in red 🔴, while processed songs appear in bold dark green. 🟢</p>
    </td>
  </tr>
</table>

## 🖼️ Screenshots

| Conversion to latest metadata version, AI's prediction | Metatag Editor |
| :-: | :-: |
| <img width="450" alt="screenshot 1" src="https://github.com/user-attachments/assets/5f13788c-7de3-4db4-84aa-97325b5b1fce" /> | <img width="450" alt="screenshot 2" src="https://github.com/user-attachments/assets/0fd539af-4fe8-49d0-91c5-6e7598caa908" /> |
| Statistics | File Explorer thumbnails before & after Song Tag |
| <img width="450" alt="screenshot 3" src="https://github.com/user-attachments/assets/ec158e2d-d803-41a8-a018-cb185309bd06" /> | <img width="450" alt="screenshot 4" src="https://github.com/user-attachments/assets/66f31342-b773-4027-b554-918363e40bfb" /> |

## 📥 Download

Song Tag is distributed as a secure, standalone binary. Click the link below to download the latest version for Linux or Windows:

👉 **[Download Filepath Hunter on itch.io](https://na-soft-dev.itch.io/song-tag)**

## 🛠️ Setup & Usage

### How to Install and Run (Windows)

1. Extract the compressed file to a portable folder.
2. Run SongTag.exe

### How to Install and Run (Linux)

Open your terminal and run the following commands in sequence:

1. Extract the downloaded archive:

```bash
tar xzf SongTag-Linux.tar.gz
```

2. Run the installer script:

```bash
./install.sh
```

3. Right-click icon on sidebar or taskbar, pin or add to favorites

## Linux Requirements

* Any modern 64-bit Linux capable of running Java 21 (JRE included, so no need to install Java).
* Other utilities that might be useful like a way to view mp3 thumbnails in file explorer:

```bash
sudo apt install gstreamer1.0-plugins-base gstreamer1.0-plugins-good ffmpeg ffmpegthumbnailer gstreamer1.0-libav totem
```

## 📋 Changelog

To view the full history of releases, bug fixes, and performance updates, check out the raw release log directly in this repository:

👉 **[Read the complete changelog.txt](changelog.txt)**
