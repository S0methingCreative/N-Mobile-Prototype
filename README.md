# N // The Vector Ray

> A 1D oscilloscope rogue-lite rhythm brawler built in pure HTML5 Canvas and the Web Audio API.

Before an image can have an area, it must have length. **N** is the linear, one-dimensional prequel to **n²** ($\sqrt{n^2} = N$). You exist along a single phosphorescent CRT trace beam, intercepting and deflecting voltage pulses from the Linear Sovereign. Reaching $N=10$ folds the 1D wire at a 90-degree angle, tearing open the second dimension and initiating the 2D matrix.

---

### Core Gameplay Mechanics

* **Analog Slide Positioning:** Navigate along the 1D ray using mouse wheel (Desktop) or the tactile thumb-slider pad (Mobile).
* **Polarity Parity Clashing:** Match incoming signal frequencies by toggling between **Crest (+)**, **Ground (0)**, and **Trough (-)** at the moment of impact.
* **Zonal Risk vs. Reward:**
  * **Attenuation Zone (Left ~35%):** Safe sector. Incoming pulses slow down; yields 1x resources.
  * **Harmonic Slit (Center ~35%):** Balanced sector; yields 2x resources.
  * **Emitter Maw (Right ~30%):** Hazardous high-speed sector; yields 3x to 5x resources.
* **The 3 Triadic Signal Patches:**
  * **[A] Resonant Choke (2 Hz + 1 V):** Slows incoming pulses across the trace for 3 seconds.
  * **[S] Overdrive Bias (1 Hz + 2 V):** Reflected pulse travels with 2x velocity and amplitude, dealing massive damage to the Sovereign.
  * **[D] Carrier Mod (1 V + 2 BD):** Deploys a ghost buffer that auto-parries your next timing error.
* **Rogue-Lite Carrier Vault:** 60% of all gathered signal data (Hertz, Volts, Baud) persists across defeat in `localStorage`, boosting starting hull integrity and accelerating progression on subsequent runs.
* **Dimensional Breach:** Slaying the Sovereign at $N=10$ triggers the orthogonal fold, unlocking the 4×4 canvas of $n^2$.

---

### Tech Stack
* Single-file zero-dependency HTML5 Canvas.
* Procedural real-time sound synthesis via Web Audio API.
* Haptic feedback via the Web Vibration API.
* Responsive, PWA-ready mobile viewport scaffolding.
