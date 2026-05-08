# Final Project Files

This folder contains the technical task deliverables for the Senior WordPress Developer evaluation.

Implemented sections:
- **Project Steps**
- **Transformation Slider**

Implemented with:
- **Elementor (WordPress)**
- **Gutenberg (block-based/custom block approach via plugin)**

## Live Demo URLs (Pantheon)

- Elementor page: [https://dev-six2eight-technical-task.pantheonsite.io/exam-elementor/](https://dev-six2eight-technical-task.pantheonsite.io/exam-elementor/)
- Gutenberg page: [https://dev-six2eight-technical-task.pantheonsite.io/exam-gutenberg/](https://dev-six2eight-technical-task.pantheonsite.io/exam-gutenberg/)
- Root URL (optional navigation): [https://dev-six2eight-technical-task.pantheonsite.io/](https://dev-six2eight-technical-task.pantheonsite.io/)

> **NOTE:** **The site is hosted on a free/sandbox environment. If a warning/interstitial page appears, click _Continue_ once to access the demo pages.**

## Included Files

| File | Description |
|------|-------------|
| `six2eight-elements-main.zip` | Custom plugin containing the Elementor widgets and Gutenberg blocks used for this task. |
| `elementor-81-2026-05-08.json` | Elementor template export used for the Elementor implementation page. |
| `README.md` | Project documentation and setup instructions. |

## Requirements

- WordPress 6.x
- Hello Elementor theme
- Elementor (latest compatible version)
- PHP/MySQL or MariaDB environment compatible with WordPress

## Setup Instructions

1. Install WordPress on local or hosting environment.
2. Install and activate **Hello Elementor** theme from **Appearance > Themes > Add New**.
3. Install and activate Elementor.
4. Upload and activate `six2eight-elements-main.zip` from **Plugins > Add New > Upload Plugin**.
5. Import `elementor-81-2026-05-08.json` from Elementor templates/import tools.
6. Create/verify pages:
   - `Exam Elementor` (`/exam-elementor/`)
   - `Exam Gutenberg` (`/exam-gutenberg/`)
7. Re-assign media assets if any image URL is broken after import.

## Theme Note

This project is intended to run on **Hello Elementor**. The visual/styling layer also includes `theme.json`-based adjustments in the theme setup.  
If your environment uses a different active theme, typography/spacing may not match the expected result exactly.

## Submission References

- GitHub repository: [https://github.com/Md-Abu-Bakker-Siddik/Final_Project_Files](https://github.com/Md-Abu-Bakker-Siddik/Final_Project_Files)
- Loom process video: [https://www.loom.com/share/6c1870d6187d41348c722343eb30911f](https://www.loom.com/share/6c1870d6187d41348c722343eb30911f)
- Figma source file: [https://drive.google.com/file/d/1mlCe-f3cTjfHVvM1DZ1Im3_CDvsK3HfU/view?usp=sharing](https://drive.google.com/file/d/1mlCe-f3cTjfHVvM1DZ1Im3_CDvsK3HfU/view?usp=sharing)

## Design Note

The implementation follows the provided Figma layout, spacing, and responsiveness as closely as possible. If the exact original font is unavailable in the runtime environment, the closest matching web font is used while preserving visual hierarchy and structure.
