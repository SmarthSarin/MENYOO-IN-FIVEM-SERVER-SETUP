Here is a **cleaned-up and UI-enhanced version** of your `README.md` for setting up **Menyoo in a FiveM server**, with improved readability, headings, and external links opening in new tabs:

---

# 🎮 MENYOO in FiveM Server Setup

A simple guide to enable and use **Menyoo** in your **FiveM server**, compatible with CFX, QBCore, and ESX frameworks.

---

## ✅ Step 1: Set Up Your FiveM Server

1. Install any server framework (CFX/QB-Core/ESX).
2. Open your server configuration file (`server.cfg`).
3. Add the following line:

```cfg
sv_scriptHookAllowed 1
```

> 🔐 **Note**: This setting allows players to use script hook-based plugins (like Menyoo or Lambda Menu). While it enables the use of such tools, it doesn't prevent unauthorized plugin usage.

📘 [Official Server Setup Docs](https://docs.fivem.net/docs/server-manual/setting-up-a-server-vanilla/){\:target="\_blank"}

---

## 🗂️ Step 2: Download and Install Menyoo

1. Download Menyoo from:

   * 🌐 <a href="https://www.gta5-mods.com/scripts/menyoo-2-0#comments_tab" target="_blank">GTA5-Mods - Menyoo 2.0</a>
2. Extract the downloaded ZIP.
3. Place the **`menyooStuff`** folder into the following path:

```
FiveM Application Data/data/cache/subprocess/menyooStuff
```

---

## ⚙️ Step 3: Customize Menyoo Settings

* Open `menyooStuff/menyooConfig.ini`.
* To change the menu toggle key, refer to the Virtual Key Codes table:

  * ⌨️ [View Key Codes](https://cherrytree.at/misc/vk.htm){\:target="\_blank"}

Example: Change the menu key from `F8` to `F7`.

```ini
openMenuKey = 118  ; VK_F7 = 118
```

---

## 📂 Step 4: Install Menyoo Plugin

1. Copy `Menyoo.asi` from the ZIP.
2. Paste it into:

```
FiveM Application Data/plugins
```

---

## ✅ You're All Set!

You can now launch your server and use **Menyoo** for in-game modifications.

> 🎉 Have fun customizing your world!

---

Would you like a downloadable `.md` file version or this integrated into a GitHub Pages-style website?
