
Zino.css

Zino.css is a lightweight, utility-first CSS framework designed to accelerate web development by providing a clean, simple, and modern set of predefined classes for layout, typography, spacing, colors, and more.

Installation
Using npm
npm install @sina-raisi/zino.css
Using CDN
You can also use Zino.css directly via CDN:


<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Sina-Raisi/zinocss@main/Zino.css" />
Usage
Import the CSS file in your project:

@import "~@sina-raisi/zino.css";
Or include it in your HTML:

<link rel="stylesheet" href="zino.css" />
Then use utility classes in your HTML:

<button class="btn btn-primary">Primary Button</button>
<div class="p-4 bg-success text-white rounded shadow-md">
  Success message box
</div>
Features
Utility-first CSS classes for rapid UI development

Responsive design with breakpoint prefixes (sm:, md:, lg:, xl:)

Extensive color palette and typography utilities

Spacing, layout, borders, shadows, buttons, and more

Dark mode support ready

No JavaScript dependency

File Structure
/project-root
├── Zino.css          # Core CSS framework file
├── example.html      # Example usage page
└── README.md         # This file
Example

<div class="p-5 bg-primary text-white rounded-lg shadow-lg text-center">
  Welcome to Zino.css!
</div>
<button class="btn btn-outline">Click Me</button>
See full demo in example.html.

Author
Created by Fardex
GitHub: https://github.com/Sina-Raisi

License
MIT License — Free to use, modify, and distribute.