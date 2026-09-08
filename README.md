# node-red-tab-manager

A powerful and intuitive vertical tab manager for Node-RED, built into the sidebar panel. It offers a clean overview of your workspace flows, allowing you to manage, reorder, and rename your tabs with ease—perfect for large projects with numerous flows.

---

## Repository Structure

This repository is split into two separate versions to accommodate different Node-RED architectures:

- **`/v4`**: Tailored for the classic `workspaceTabs` layout in **Node-RED v4**.
- **`/v5`**: Optimized for the modern header-nested architecture in **Node-RED v5** (includes the precise `mouseup.tabmanager` two-way synchronization engine).

---

## Features

- ↕️ **Bi-directional Drag & Drop:** Reorder your tabs vertically inside the sidebar. The top tabs in Node-RED will sync instantly, and vice versa!
- ↔️ **Bi-directional Navigation:** Click on any tab listed in the sidebar and the focus will change to the corresponding tab in Node-RED. Vice versa works also!!
- ✏️ **Full Two-Way Inline Renaming:** Double-click any flow tab in the sidebar to rename it, or change it via Node-RED properties. Names sync perfectly in both directions.
- 👁️ **Visual Status Indicators:** Disabled flows are styled with lower opacity, italic text, and a `fa-eye-slash` icon to easily separate active routines from muted ones.
- 🎨 **Native Theme Integration:** Fully adopts your active Node-RED editor colors and CSS variables for a seamless native look.
- 💾 **Persistent Deploys:** Reordering activates the native Node-RED `Deploy` button, ensuring your layout is saved securely.

---

## Installation

Install via the Node-RED palette manager, or from the command line:

   ```bash
cd ~/.node-red
npm install @krambriw/node-red-tab-manager-v5

   ```
Restart your Node-RED instance and force-refresh your browser (`Ctrl + F5` or `Cmd + Shift + R`).

---

## License

Licensed under the **MIT License** - feel free to share, modify, and distribute!
