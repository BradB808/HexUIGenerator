HexUI Color Generator
A powerful, web-based tool for creating beautiful color palettes and design systems.
Show Image
Features

Interactive Color Selection: Choose colors using multiple input methods:

HSL and RGB sliders with numerical inputs
Visual color wheel with brightness control
Eyedropper tool for picking colors from anywhere on your screen
Hex code input for precise color selection


Comprehensive Color Scale Generator: Automatically generates a full color scale with 11 shades (from 50 to 950) for any selected color, perfect for design systems.
Real-time UI Previews: See how your color palette looks in real-world UI components:

Cards & Charts
E-commerce components
Maps & Location interfaces
Forms & Auth screens
Common UI components


Export Capabilities: Export your color palette as CSS variables for immediate use in your projects.

Getting Started

Open main.html in a modern web browser (Chrome, Edge, Firefox, or Safari).
Select a color using any of the available input methods:

Adjust HSL or RGB sliders
Click on the color wheel and adjust brightness
Use the eyedropper tool to pick colors from your screen
Enter a hex code directly


Click "Generate Color Scale" to create a complete color palette based on your selection.
Preview how your colors look in various UI components in the right panel.
Export your color palette as CSS variables by clicking the "Export" button.

Browser Compatibility

Fully supported: Chrome 95+, Edge 95+
Partially supported: Firefox, Safari (Eyedropper feature may not be available)

Technical Details
The Color Generator uses pure JavaScript, HTML, and CSS without any external dependencies. It includes the following key functionalities:

HSL to RGB and RGB to HSL color conversions
Hex to RGB and RGB to Hex color conversions
Canvas-based color wheel implementation
Native browser EyeDropper API integration (where available)
CSS custom properties (variables) for real-time UI updates

Color Science
The application generates a complete color scale based on the selected color by adjusting the lightness value while maintaining the hue and saturation. This creates a cohesive set of colors suitable for:

Primary/accent colors
UI element states (hover, active, disabled)
Background variations
Text colors with appropriate contrast

Project Structure
Copycolor-generator/
├── main.html      # Main HTML file with embedded CSS and JavaScript
├── README.md       # This file
└── assets/         # Optional folder for additional assets
Customization
For developers who want to extend or modify the Color Generator:

The color scale generation algorithm can be found in the generateColorScale() function
UI components for previewing colors are in the HTML structure under the .examples-grid classes
Color conversion utilities are available in the JavaScript section

Future Enhancements

Save multiple color palettes
Color accessibility evaluation (WCAG compliance)
Dark/light mode toggle
Color harmony suggestions (complementary, analogous, etc.)
Import from images or URLs
