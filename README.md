# Radio Traders Skin Maker

Make your own paint job for the walkie and ham radio screens in **Radio Traders** (Project Zomboid, Build 42).

## Download

**[Download the Skin Maker (.zip)](https://github.com/ironlungs8519/RadioTraderSkinCreator/archive/refs/heads/main.zip)**

Unzip it and open `RadioTraderSkinCreator/RadioTraders_SkinMaker.html` in Chrome, Edge or Firefox.

## Is it safe?

- **It's a single web page (.html), not a program (.exe).** Nothing installs and nothing runs outside your browser.
- **It works offline.** The page makes no internet requests and loads no outside scripts. You can unplug your network and it still works.
- **It only touches files you choose.** It reads the image you drop in, and writes a skin mod either as a normal download (.zip) or into a folder you pick yourself.
- **You can read every line.** Right-click the file → Open with → Notepad. It's all plain text.

## How to use it

1. Drop in an image for the walkie, the ham radio, or both.
2. Position and zoom it. Keep **"Keep the radio's frame, screens, buttons and knobs"** ticked so the controls stay visible.
3. Name your skin and pick which of the 8 built-in skins it replaces.
4. Export: **Download skin mod (.zip)** and unzip it into `C:\Users\<you>\Zomboid\mods\`, or use **Save straight into my Zomboid/mods folder** (Chrome/Edge).
5. **From the main menu** Mods screen, enable **Radio Traders** and your new skin mod.
6. **Fully restart the game**, then go to Mod Options → Radio Traders → Radio skin and pick the slot you replaced.

Skins are client-side. For multiplayer, add the skin's ID after Radio Traders in your server's mod list, for example `Mods=\RadioTraders;\RT_Skin_Bloody`. To share a skin, give a friend your skin's folder from `Zomboid/mods`.

`RadioTraderSkinCreator/README.txt` has a step-by-step walkthrough with screenshots, and `RT_Skin_Bloody` is a finished example skin.

## Not showing up?

- The skin mod must be enabled from the **main menu**, then the game fully restarted.
- Mod Options → Radio skin must be set to the slot your skin replaces.
- The "classic" tickbox in the same menu must be **off**.
- A walkie-only skin won't change the ham radio, and a ham-only skin won't change the walkie.
