# Infernix Raw: one-knob live remix engine

![Infernix Raw free one-knob live remix engine UI](https://raw.githubusercontent.com/RemiBlaze/InfernixRaw/main/infernixraw-ui-screenshot.png)

**One knob. Turn it up and your track starts remixing itself.**

Infernix Raw is the free one-knob version of Infernix Pro. It listens to your last couple of bars and, as you open the knob, fires syncopated fills that chop and rearrange what you just played, from the occasional flourish to a full glitched breakbeat.

**macOS** (Apple Silicon and Intel): AU, VST3, CLAP, AAX, Standalone. Signed and notarized by Apple.

**Windows** 10 and 11, 64-bit: VST3, CLAP, Standalone. Authenticode signed.

AAX ships on macOS only.

---

## 🚀 Download & Install

Go to the [latest release](https://github.com/RemiBlaze/InfernixRaw/releases/latest) and pick your platform.

**macOS**
1. Download **`InfernixRaw_Installer.pkg`**.
2. Double-click it and follow the installer. It is signed and notarized by Apple, so it installs cleanly with no security warnings.
3. Restart your DAW and rescan plug-ins. Infernix Raw appears under **Remi Blaze**.

**Windows 10 and 11, 64-bit**
1. Download **`InfernixRaw_Installer.exe`**.
2. Run it and follow the installer. It is Authenticode signed.
3. Restart your DAW and rescan plug-ins. Infernix Raw appears under **Remi Blaze**.

No dongle and no extra account on either platform.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ What It Does
- **REMIX**: the single macro knob. At zero, Infernix Raw passes your signal through dry (it's still quietly recording your last bars in the background). Turn it up and the engine self-arms: it free-runs a beat clock synced to your host tempo and fires remix fills more often and more aggressively as you open it. Each fill slices the buffered audio with two ghost playheads (a forward eighth-note and a reverse sixteenth), morphs the spectrum, adds rhythmic gating, then crossfades back to your dry signal. A 0 dBFS soft-clip ceiling keeps peaks in check.

That's the whole plug-in: one knob, always-on, tempo-aware.

---

## 💻 System Requirements

**macOS**
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- An AU, VST3, CLAP or AAX host

**Windows**
- Windows 10 or Windows 11, 64-bit
- A VST3 or CLAP host

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/InfernixRaw/issues)** tab with your macOS or Windows version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Plugin page:** [remiblaze.com/plugins/infernix-raw/](https://remiblaze.com/plugins/infernix-raw/).
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.

AAX, Avid, and Pro Tools are trademarks or registered trademarks of Avid Technology, Inc. in the U.S. and other countries.

Microsoft and Windows are trademarks of the Microsoft group of companies.
