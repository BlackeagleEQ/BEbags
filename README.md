![BEbags Banner](./screenshots/banner.png)

# 👜 BEbags

**BEbags** is a powerful inventory manager for **EQEmu Servers using MacroQuest / E3N** that combines all your bags into one clean, easy-to-use interface.

No more opening bags one by one. Everything is in one place.

---

## ✨ What It Does

- 📦 Combines all your bags into a single window
- 🏦 Lets you view your bank anywhere after syncing
- ⚡ Adds quick actions like deposit, destroy, and drop
- 🖱️ Improves item interaction with smart click behavior
- 🎨 Includes multiple UI themes
- ⚙️ Fully customizable layout and behavior

---

## 🖼️ Screenshots

### Quick Actions Menu
![Quick Actions](./screenshots/quick_actions.png)

### Configuration Menu
![Config](./screenshots/config_menu.png)

### Help / Field Manual
![Help](./screenshots/field_manual.png)

### Inventory / Adventurer's Pack
![Inventory](./screenshots/inventory.png)

---

## 🚀 Installation

1. Download this repository or the latest release
2. Place `BEbags.lua` into your MacroQuest `lua` folder:

```text
MacroQuest/lua/BEbags.lua
```

3. In game, run:

```text
/lua run BEbags
```

---

## 🎮 How It Works

### 👜 Main Window
- Displays all items from your inventory in one place
- Use the top buttons to:
  - Switch between **Inventory** and **Bank**
  - Sort items
  - Deposit items quickly

### 🖱️ Mouse Controls

| Action | Result |
|--------|--------|
| Left Click | Pick up item |
| Double Left Click | Inspect item |
| Right Click | Use item |
| Ctrl + Right Click | Sell item (merchant required) |
| Middle Click (icon) | Open quick actions |

### ⚡ Quick Actions

Accessed via middle-click on the launcher icon:

- Toggle packed mode
- Reset sorting
- Toggle value bar
- Open help
- Hide launcher

### ⚙️ Configuration

Open config by:
- Right-clicking the launcher icon
- Or using:

```text
/BEbags config
```

From here you can:
- Adjust layout and sizing
- Toggle UI elements
- Enable/disable features
- Choose your theme

### 🎨 Theme Presets

- Classic
- Diablo
- Emerald
- Frost

### 🏦 Bank System

- Open a banker once to sync your bank
- After syncing, you can view your bank anywhere

**Behavior:**
- Bank open → live view
- Bank closed → cached snapshot

---

## 💡 Pro Tips

- 🔥 Use Packed Mode  
  Keeps your inventory clean and compact

- ⚡ Deposit is your best friend  
  Quickly places items without showing empty slots

- 💰 Sell faster  
  Ctrl + Right Click items while at a vendor

- 🏦 Bank anywhere  
  Sync once, access anytime

- 🧹 Clean junk instantly  
  Destroy removes items permanently (no confirmation!)  
  Drop places items on the ground

- 🎯 Sort before selling  
  Value sorting helps identify high-value items quickly

- 🎨 Try themes  
  Diablo = high contrast  
  Emerald = easy on the eyes  
  Frost = clean and minimal

---

## 📜 Commands

```text
/BEbags           → Toggle main window
/BEbags config    → Open config
/BEbags help      → Open help menu
/BEbags destroy   → Destroy item on cursor
/BEbags drop      → Drop item on ground
```

---

## 👤 Author

BlackeagleEQ

---

## ❤️ Credits

Built for the AscendantEQ community using MacroQuest Lua.

---

## 🔥 Why BEbags?

Because once you use it, you’ll never go back to opening bags manually again.
