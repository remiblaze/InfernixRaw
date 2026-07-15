# Infernix Raw — one-knob live remix engine

![Infernix Raw](https://raw.githubusercontent.com/RemiBlaze/InfernixRaw/main/infernixraw-ui-screenshot.png)

**One knob. Turn it up and your track starts remixing itself.**

Infernix Raw is the free one-knob version of Infernix Pro. It listens to your last couple of bars and, as you open the knob, fires syncopated fills that chop and rearrange what you just played — from the occasional flourish to a full glitched breakbeat.

Fully **signed and notarized** for macOS as **AU, VST3, and Standalone**.

---

## 🚀 Download & Install
1. Go to the [latest release](https://github.com/RemiBlaze/InfernixRaw/releases/latest).
2. Download **`InfernixRaw_Installer.pkg`**.
3. Double-click it and follow the installer. Signed & notarized by Apple — installs cleanly, no security warnings.
4. Restart your DAW and rescan plug-ins.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ What It Does
- **REMIX** — the single macro knob. At zero, Infernix Raw passes your signal through dry (it's still quietly recording your last bars in the background). Turn it up and the engine self-arms: it free-runs a beat clock synced to your host tempo and fires remix fills more often and more aggressively as you open it. Each fill slices the buffered audio with two ghost playheads (a forward eighth-note and a reverse sixteenth), morphs the spectrum, adds rhythmic gating, then crossfades back to your dry signal. A 0 dBFS soft-clip ceiling keeps peaks in check.

That's the whole plug-in — one knob, always-on, tempo-aware.

---

## 💻 System Requirements
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- Any AU or VST3 host (your DAW of choice)

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/InfernixRaw/issues)** tab with your macOS version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.
