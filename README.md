# Using Google Maps My Maps to Draw Polygons, Customize, and Export

This guide explains how to use Google Maps My Maps to draw polygons, customize them (name, color, description), and export them as CSV for further use.

---

## Prerequisites
- A Google account.
- Access to [Google My Maps](https://www.google.com/mymaps).

---

## Steps to Use Google Maps My Maps

### 1. **Create a New Map**
1. Go to [Google My Maps](https://www.google.com/mymaps).
2. Sign in with your Google account.
3. Click **"Create a New Map"**.

---

### 2. **Draw a Polygon**
1. In the toolbar, click the **Draw a Line** icon (zigzag shape).
2. Select **"Add a Line or Shape"**.
3. Click on the map to place the vertices of the polygon:
   - Each click adds a corner of the shape.
   - Double-click to close the shape and finish drawing.
4. A dialog box will appear. Enter:
   - **Name**: The colour for the polygon (e.g., red).
   - **Description**: A description for the polygon (e.g., "Runway, Taxiway").

---

### 3. **Export the Map**
1. Once your map is ready, click the three vertical dots (**More Options**) in the left panel next to the map title.
2. Select **"Download as CSV"**.
3. A CSV file will be generated containing:
   - Name (colour of the polygon).
   - Description (Details about the polygon, such as "Runway").
   - Coordinates in WKT format (Well-Known Text).

---

### 4. **Use the Exported File**
- The exported CSV file can be:
  - Imported/Copy into the respective bases csv found in the csv folder.
  - Follow `TAB.csv` if you are unsure of the format.

---

## How the File is Read
- **WKT for Coordinates**: The exported file contains WKT (Well-Known Text) defining the geometry of the polygons for input into web or software tools.
- **Name Column**: The "Name" column in the CSV determines the color of the polygon, limited to:
  - `red`
  - `orange`
  - `green`
  - `blue`
  - `yellow`
  - `purple`
  - `pink`
- **Description Column**: The "Description" column specifies the label or function of the polygon (e.g., "Runway").

---

## Audio Integration
- **Audio File**: The audio plays from a file named `warning.mp3` located in the `audio` folder.
- **Customization**: Replace the `warning.mp3` file with another audio file of your choice remeber to name it as warning.mp3 . Ensure the replacement file is stored in the `audio` folder with the same name or update the reference accordingly.

---

## Tips
- Use satellite view for precise polygon placement.

---

Enjoy mapping! 🚀
