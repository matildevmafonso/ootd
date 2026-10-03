# OOTD! (Outfit of the Day)

> A desktop application built with Electron that lets you mix and match daily outfit combinations across three categories: Tops, Pants, and Shoes.

## Features

- Landing Screen: Interactive start screen leading into the outfit builder.
- 3-Tier Selector: Divided viewport featuring individual carousels for Tops, Pants, and Shoes.
- Smooth Navigation: Carousel controls to cycle through clothes in real time.

## Project Structure

```plaintext
├── assets/
│   ├── Tops/       # Top wardrobe images
│   ├── Pants/      # Pants wardrobe images
│   ├── Shoes/      # Shoes wardrobe images
│   └── miffy.png   # Main landing image
├── index.html      # Landing page
├── outfitpage.html # Main outfit selector screen
├── main.js         # Electron main process
├── script.js       # Carousel navigation logic
└── style.css       # App layout and styles
```

## Getting Started

### Prerequisites

Make sure you have Node.js installed on your machine.

### Setup & Installation

1. Initialize package.json (if you haven't already):

   ```bash
   npm init -y
   ```

2. Install Electron as a development dependency:
   ```bash
   npm install electron --save-dev
   ```
3. Ensure package.json specifies main.js:

   ```json
   {
     "name": "ootd-app",
     "version": "1.0.0",
     "main": "main.js",
     "scripts": {
       "start": "electron ."
     }
   }
   ```

4. Run the application:
   ```bash
   npm start
   ```
