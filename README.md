## Home Assistant Lovelace Card for Everything Presence Lite

This repository contains a custom Home Assistant Lovelace card for visualizing zones and presence of up to 3 targets. 

**Card Functionality:**

The `everything_presence_lite_map_chart.yaml` file defines a Lovelace card that displays a map-based visualization showing 3 zones and up to 3 active targets.

**Installation Instructions:**

1.  **Install Plotly Graph Card:** This card requires the <a href="https://github.com/dbuezas/lovelace-plotly-graph-card">Lovelace Plotly Graph Card</a> from HACS in Home Assistant.
2.  **Copy & Paste Code:** Add a manual lovelace card to your dashboard and copy content of the <a href="https://github.com/KiefDelicious/ha-utils/blob/main/everything_presence_lite_map_chart.yaml">everything_presence_lite_map_chart.yaml</a>
3.  **Replace Sensor Names:** Ensure to replace the placeholder of 2 sensor names (`everything_presence_lite_name`) with the actual names of your sensors in Home Assistant.
4.  **Optional:** Remove zones that are not used to avoid error message

**Image Example:**

<img width="480" alt="Screenshot 2024-08-18 at 22 31 45" src="https://github.com/user-attachments/assets/d973cd46-70c6-44b7-ba62-2a769ecc7838">



***Notes** Based on the code of <a href="https://github.com/athua">athua</a> and <a href="https://github.com/smarthomejunkie">smarthomejunkie</a>*

As an addition with the help of [iamwyza](https://github.com/iamwyza) I've added the `everything_presence_lite_map_chart-rotation-support.yaml`. This does the same as `everything_presence_lite_map_chart.yaml`, but allows for grid rotation, making it easier to place sensors in corners).



