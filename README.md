# Vertical Spacious Refresh

**A sleek, modern Discord facelift for Vencord.**  
Focused on spacing, hover-driven UI, compact layouts, and subtle color polish — without gimmicks or abandoned features.

---

## 🔌 Requirements

This theme is designed for **Vencord** and works best with the **Visual Refresh UI** enabled.

### Recommended (Required) Plugins

These are optional but integrate well with the styling present in the CSS:

- `ThemeAttributes`
- `ShowConnections`
- `ReadAllNotificationsButtons`

---

## 🚀 Installation

### 🌐 Online (Auto-Updates)

Paste this URL into  
**Vencord → Themes → Online Themes**




```
https://madmaxgrey.github.io/Vertical-Spacious-Refresh/vencord/Vertical-Spacious-Refresh.css
```
### 💾 Offline (Manual)

Download from:
[GitHub Releases](https://github.com/madmaxgrey/Vertical-Spacious-Refresh/releases)
Place the `.css` file into your Vencord `themes` folder and enable it.

---

### 💾 Offline (Manual)

1. Download the CSS from GitHub  
2. Place the file into your Vencord `themes` folder  
3. Enable it in Vencord

---

## ✨ Features at a Glance

| Feature | Description |
|------|------------|
| 🧭 **Floating Panels** | Panels and UI elements rely on hover-based visibility to reduce constant clutter. |
| ✂️ **Compact Message Actions** | Message buttons collapse and only appear when relevant. |
| ↔️ **Compact Member List** | Member list spacing is reduced with smooth width transitions. |
| 🧼 **Panel Cleanup** | Reduced padding and visual noise across sidebars and popouts. |
| ⚙️ **Hidden Action Icons** | Channel and toolbar icons remain hidden until hovered. |
| 💬 **Styled Chat Bars** | Read All, Jump to Present, and New Message bars are rounded and recolored. |
| 🧾 **Refined Embeds** | Cleaner embeds with subtle borders and reduced visual weight. |
| 🧱 **Simplified Panel Area** | Bottom user area is cleaner and less intrusive. |
| 🖼️ **Rounded UI Elements** | Avatars, buttons, embeds, and folders use consistent rounding. |
| 🎨 **Accent-Based Coloring** | UI elements inherit the main accent color for a cohesive look. |
| 🧭 **Compact Search** | Search bar visuals are simplified and scale smoothly. |
| 📁 **Folder Styling** | Server folders use flat, pastel-style coloring. |
| 🎚️ **Reduced Context Menus** | Context menus are tighter with less padding. |
| 🧩 **Snippet-Based Architecture** | Built from modular snippets that can be easily removed or replaced. |

---

## 🎨 Theme Variables & Toggles

Custom root variables control colors, animation speeds, and layout toggles. Key variables include:
```
:root {
    --custom-app-top-bar-height: 48px;
    --mc: #8d2036;
    --backgroundColor01: #1e2731;
    --gradientColor01: var(--mc);
    --gradientColor02: #eea60b;
    --craat-popout: 1; /* Default = 0 */
    --craat-popout: 1; /* Default = 0 */
    --craat-border-radius: 16px; /* default: 16px */
    --compact-member-list-transition-definition: 0.45s ease-out 0.08s;
}
```
You can customize the layout using the following toggles:
```
:root {
- --\--irc-compact-chats: true;
- --\--compact-input-box: true;
- --\--hide-nameplates: true;
- --\--compact-message-actions: true;
- --\--username-bubbles: true;
- --\--codeblock-enhanced: true;
}
```
---

## 🌀 Embrace the Vertical

Let your UI breathe. No distractions — just a sleek, modern Discord experience.
_Minimal. Responsive. Refreshed._

---
