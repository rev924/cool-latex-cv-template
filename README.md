# cool-latex-cv-template
A customizable and easy LaTeX template for academic and technical CVs

Custom LaTeX CV Template

A customizable LaTeX template for creating clean, professional academic and technical CVs.

The template features a custom header and footer, a background watermark, Font Awesome icons, configurable contact information, and a structured multi-page layout.

Features
Custom page header and footer
Background watermark on every page
Configurable colors and branding
Font Awesome icons for section headings
Customizable contact information
Multi-page CV layout
Clickable email and GitHub links
Example content for academic and technical CVs

## Preview

![CV Preview](preview/cv-preview.png)

[📄 Download the full PDF](preview/cv-example.pdf)

## Requirements
A LaTeX distribution, such as TeX Live or MiKTeX
XeLaTeX or LuaLaTeX
The TeX Gyre Heros font
The LaTeX packages used by the template, including TikZ, Font Awesome, and fontspec
Getting Started
Clone or download this repository.
Make sure the images/ directory contains all required image assets.
Edit main.tex to customize your personal information, education, experience, skills, and other sections.
Update NAstyle.sty to customize the colors, header, footer, watermark, and visual layout.
Compile the document using XeLaTeX or LuaLaTeX.

For example, using XeLaTeX:

xelatex main.tex

## Project Structure
.
├── main.tex
├── NAstyle.sty
├── images/
│   ├── na_header.png
│   ├── footer.png
│   ├── na_logo_background.png
│   └── example_avatar.png
├── preview/
│   └── cv-example.pdf
├── README.md
├── LICENSE
└── .gitignore

## Customization
Contact Information

Edit the following commands in main.tex:

\providecommand{\CVEmail}{your.email@example.com}
\providecommand{\CVPhone}{+00 000 000 0000}
\providecommand{\CVGitHubURL}{https://github.com/yourusername}
\providecommand{\CVGitHubLabel}{GitHub Profile}

Background and other University pictures

Edit the following commands in NAstyle.sty:
\newcommand{\CVHeaderImage}{images/na_header.png}
\newcommand{\CVFooterImage}{images/footer.png}
\newcommand{\CVWatermarkImage}{images/na_logo_background.png}



Colors and Branding

Edit the color definitions and image paths in NAstyle.sty to customize the appearance of the CV.

Content

Replace the example information in main.tex with your own education, experience, technical skills, languages, and other relevant sections.

## License

See LICENSE for information about permitted use and redistribution.

## Contributing

Suggestions, bug reports, and improvements are welcome. Feel free to open an issue or submit a pull request.
