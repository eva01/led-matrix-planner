# **LED Matrix Display Simulator**

A web-based tool to simulate text on configurable LED matrix panels. This simulator allows sales teams and customers to preview how messages will appear on different panel layouts and resolutions without needing physical hardware. It includes a real-time cost estimator to provide quick quotes.

## **Live Demo**

You can run this project directly by opening the index.html file in your browser. For a live version, you can host it on any static web hosting service like GitHub Pages or Cloudflare Pages.

## **Features**

* **Real-Time Preview**: Instantly see how your text will look on a realistic LED grid.  
* **Configurable Panel Layout**: Set the number of panel rows and columns.  
* **Multiple Panel Types**: Choose between P10 (32x16) and P5 (64x32) resolutions.  
* **Flexible Font Options**:  
  * Classic 5x7 Segment bitmap font for a retro feel.  
  * Modern web-based pixel fonts (VT323, Press Start 2P, Pixelify Sans, Silkscreen).  
* **Customizable Appearance**: Adjust font size, LED color, and line spacing.  
* **Display Modes**:  
  * **Static**: Centers the message on the display.  
  * **Scroll**: Smoothly scrolls the message horizontally with adjustable speed.  
* **Dynamic Cost Estimator**:  
  * Set custom unit prices for panels, power supplies, and drivers.  
  * Get an instant total estimated cost in MYR based on your configuration.  
* **Export to PNG**: Save a high-quality screenshot of the current display with a single click.  
* **Responsive Interface**: A clean, modern UI with a pop-up settings panel that works on desktop and tablets.

## **How to Use**

1. **Open index.html** in your web browser.  
2. Click the **settings icon** (⚙️) in the top-right corner to open the configuration panel.  
3. **Enter your message**, including multiple lines if needed.  
4. **Configure the display**: Adjust panel columns, rows, and type.  
5. **Customize the look**: Choose a font, set the size (for web fonts), and pick an LED color.  
6. **Select a display mode**: Choose between Static and Scroll, and set the scroll speed if applicable.  
7. **Estimate the cost**: Enter the unit prices for hardware components to see the total price update in real-time.  
8. Click **"Export as PNG"** to save an image of your preview.

## **Deployment**

This is a self-contained, single-file web application with no dependencies besides Tailwind CSS and Google Fonts, which are loaded from a CDN.

You can easily deploy it to any static hosting provider:

* **GitHub Pages**: Create a new repository, upload index.html, and enable GitHub Pages in the repository settings.  
* **Cloudflare Pages**: Connect your GitHub repository to Cloudflare Pages for continuous deployment.

## **License**

This project is released under the MIT License. See the LICENSE file for details.
