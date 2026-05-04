# Final Project Files

This folder contains deliverables for a WordPress site built with **Elementor** and custom widgets from the **Six2Eight Elements** plugin.

## Contents

| File | Description |
|------|-------------|
| `hello-elementor.zip` | [Hello Elementor](https://wordpress.org/themes/hello-elementor/) theme — a lightweight starter theme optimized for Elementor. |
| `six2eight-elements-main.zip` | Custom Elementor plugin (widgets such as project steps and before/after transformation sliders). Install and activate **after** Elementor. |
| `elementor-400-2026-05-04.json` | Elementor template export for the page titled **Exam Elementor** (layout, sections, and widget data). |
| `plugin.avif` | Image asset included with the project files. |

## Requirements

- WordPress 6.x (or version compatible with your Elementor build)
- **Elementor** (and Elementor Pro if your template relies on Pro features — check your export)
- PHP and MySQL/MariaDB per WordPress hosting standards

## Installation overview

1. **WordPress**  
   Install WordPress on your host or local environment (e.g. Local, XAMPP, or your provider’s installer).

2. **Theme**  
   In **Appearance → Themes → Add New → Upload Theme**, upload `hello-elementor.zip`, install, and activate.

3. **Elementor**  
   Install and activate the **Elementor** plugin from the WordPress plugin directory (or your licensed Pro package).

4. **Six2Eight Elements**  
   In **Plugins → Add New → Upload Plugin**, upload `six2eight-elements-main.zip`, install, and activate. This plugin supplies custom widgets referenced in the exported template.

5. **Import the page template**  
   In Elementor, use **Templates → Saved Templates** (or **Tools → Import/Export**, depending on your Elementor version) to import `elementor-400-2026-05-04.json`.  
   Alternatively, create a new page, edit with Elementor, open the library/hamburger menu, and use **Import** if your workflow uses JSON from the editor.

6. **Media and URLs**  
   The JSON export references images from a local development URL (for example paths under `wp-content/uploads/...`). After import, **re-assign images** in the Media Library or in each widget so links point to your live site. Broken images until you replace them are expected.

## Version notes

- The Elementor export file reports `"version":"0.4"` in its metadata; your Elementor version should be recent enough to import this format.
- If import fails, update WordPress, Elementor, and the Six2Eight plugin to their latest compatible versions and try again.

## Repository

Line endings for text files are normalized per `.gitattributes` (`* text=auto`).

---

If you add more themes, plugins, or exports, extend the **Contents** table so the bundle stays easy to hand off or deploy.
