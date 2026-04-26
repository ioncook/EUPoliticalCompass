# EU Political Compass

A visualization tool for European political parties based on the Chapel Hill Expert Survey (CHES) dataset.

To use, simply visit the [website](https://ioncook.github.io/EUPoliticalCompass/). 

## Usage

- **Offline**: Download the ZIP, extract it, and run `index.html`. You can select the provided CSV or supply another in the CHES-EU format.
- **Local Server**: Create a Python server in the folder (`python -m http.server`) and it will automatically load the CSV.
- **Interaction**:
    - Click on any party dot to focus on it.
    - Use the **Groups** dropdown to toggle party families.
    - Use the **Wheel Scroll** on dropdown menus to quickly cycle through options.
    - Click **Reset** to return to the default view.

## Sources

- **Data**: [Chapel Hill Expert Survey (CHES)](https://www.chesdata.eu/) - The primary data source for party positions on economic and social axes.
- **Visualization**: [Chart.js](https://www.chartjs.org/)
- **Data Parsing**: [PapaParse](https://www.papaparse.com/)

## Note on Groups

Listed "groups" do not directly correlate to real EU Parliament groups but fit loosely; the groups in the CSV correspond mainly to party platform, which carries over groups. Names and descriptions can be easily edited in the `groupMapping` object within `index.html`.
