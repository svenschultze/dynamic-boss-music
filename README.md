````markdown
# 🎵 Dynamic Boss Music Designer

**Live Demo:** [svenschultze.github.io/dynamic-boss-music](https://svenschultze.github.io/dynamic-boss-music/)

An interactive web app for designing **adaptive boss battle music** scenes — inspired by *Dark Souls*, *Elden Ring*, and other games with multi-phase combat music.
<img width="2485" height="1255" alt="image" src="https://github.com/user-attachments/assets/c32871c4-4f0c-4bed-b6a1-9f5ae8618d42" />

---

## ⚙️ Features

- 🎬 **Scene + Phase Editor**  
  Create multiple scenes, each with multiple boss fight phases.

- ⏱️ **Intro + Loop Segments**  
  Each phase has:
  - **Start** — where the phase begins.  
  - **Loop Start / Loop End** — where it loops seamlessly until you advance.

- 🎧 **YouTube Integration**  
  Play any YouTube track and define timecode segments for each phase.

- 🎨 **Direct Manipulation Timeline**  
  Drag handles and playhead directly on a visual timeline like in a DAW.

- 💾 **Save, Export, Import**  
  Your data is saved to `localStorage` and can be exported/imported as JSON.

- 🪄 **Smooth Transitions**  
  Automatic crossfades between loops and phases for seamless playback.

---

## 🧠 How It Works

The app embeds YouTube audio and allows you to mark different **phase loops** that correspond to boss fight states.  
When a phase reaches its loop end, it restarts from the loop start until you press “Next Phase”, just like adaptive game music systems.

---

## 🕹️ Controls

| Action | Shortcut |
|--------|-----------|
| Play / Pause | `Space` |
| Next Phase | `]` |
| Previous Phase | `[` |
| Drag Playhead | Scrub timeline |
| Drag Handles | Adjust phase markers |

---

## 🚀 Local Setup

You can also run it locally:

```bash
git clone https://github.com/svenschultze/dynamic-boss-music.git
cd dynamic-boss-music
# open index.html in your browser - maybe you'll have to start a web server because of the youtube API
````

---

## 🧙‍♂️ Credits

* **Developer:** [Sven Schultze](https://github.com/svenschultze)
* **Concept & Design:** Inspired by adaptive boss music systems in *FromSoftware* games.

---

## 🧩 License

Apache 2 License © 2025 Sven Schultze

---

> ⚔️ “Prepare yourself, for the music shall adapt to your fate.”

