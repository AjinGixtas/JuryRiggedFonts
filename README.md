# JuryRiggedFonts

A misc collection of partially modified fonts for my own projects — particularly useful in coding/scripting games and terminal-based visualizations.

These fonts are customized for better visual alignment, symbol usage, and stylistic consistency when working with monospaced UIs or game engines like **Godot**.

---

## 🔧 MonoJetBrains + Full Width/Height-Filled Glyphs

![image](https://github.com/user-attachments/assets/0c2bc292-cf63-47d4-abee-0ed323484889)


(Rendered in Godot UI, excuse the weird color line please! ^^)

The text used are:
```
▲▴▶▸▼▾◀◂█◆◢◣◥◤
               ▴
 ▴  ▲         ◢█◣
◂█▸◀█▶       ◂███▸
 ▾  ▼         ◥█◤
               ▾
qwertyuiopasdfghjklzxcvbnm
qwertyuiopasdfghjklzxcvbnm
 ```

(Does look a lot nicer init?)

This variant is based on **JetBrains Mono**, with modifications to specific characters for precise visual alignment. The following characters have been altered:
▲ ▴ ▶ ▸ ▼ ▾ ◀ ◂ █ ◆ ◢ ◣ ◥ ◤

These glyphs now fully occupy the **half-character block space** (either triangular or square fill), which is useful for:

- Terminal-based visual output
- Custom CLI art
- Pseudo-graphical UI in coding/simulation games
- Godot or similar engine text rendering where alignment is critical

---

## ✍️ Font Modifications

- Based on: [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
- Edited using: [FontForge](https://fontforge.org/)
- EM size aligned to grid for pixel-perfect triangle/square fill
- Exported to `.ttf` for game engine compatibility
- Maintains monospaced metrics

---
## 📄 License

Modifications to JetBrains Mono are provided under the [original font's license](https://github.com/JetBrains/JetBrainsMono/blob/master/OFL.txt) (SIL Open Font License v1.1). You are free to use, modify, and redistribute under those terms.

---

## 💡 Notes

This is not intended for general-purpose use. The modifications serve niche rendering or visualization use cases — especially in games, simulations, or pseudo-GUI rendering within a text grid.

Use with care. Or not. JuryRig it as you wish.
