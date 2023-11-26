# FA23-Beyond the Screen - AR Driven Insights

### Introduction
AR introduces a dynamic, three-dimensional platform for data visualization, making complex information more intuitive and accessible through interactive 3D plots, heatmaps, and bubble charts.This project leverages Augmented Reality (AR) to innovate the realm of data visualization by transforming traditional two-dimensional plots into interactive, immersive three-dimensional experiences. The aim is to significantly enhance users' comprehension and interaction with complex datasets, facilitating a more intuitive and engaging exploration of data in various domains such as education, business analytics, and scientific research. By doing so, we hope to provide a platform that allows for a more holistic understanding of information within a dynamic spatial context.

### Literature Review

Our project integrates the insights from previous studies that contrast VR data visualization with conventional 2D approaches, and extends the realm of static visualizations into the interactive domain using AR. By building upon foundational research, including pioneering works like VisAR, we aim to underscore and expand upon the benefits of immersive technologies in making data visualization more engaging and intuitive

### Project Implementation
The project is implemented for mobile devices, starting with data selection and preparation, followed by choosing the right AR development tools and integrating the data with the AR system for dynamic and accurate representation.So here we are basically using Plot-AR Python package with which we are using the Data Sets and Visualizing them in the 3D AR Environment. 

### Prototype Features
- AR Scatter Plots: Interactive 3D scatter plots in an augmented reality setting, allowing users to analyze correlations and outliers by navigating around and interacting with data points in a spatial context.
- AR Surface Plots: Augmented reality surface plots that offer a three-dimensional view of complex data landscapes, enabling users to explore interactions between variables and discern patterns in a more tangible form.
- AR Bubble Plots: 3D bubble plots in AR that represent data with bubbles of varying sizes, providing a visually engaging method to compare and contrast quantitative data, with the added depth and dimension enhancing the analysis of proportions and relationships.
- AR Line Plots: Interactive 3D line graphs that enable a temporal and trend-focused data analysis, enhancing the user's ability to track changes and patterns over time within an immersive AR environment.
- AR Differential Plots: 3D visualizations that highlight variations and changes between different datasets or over time, providing an intuitive and engaging way to compare and analyze differential data dynamically in AR.

- User Interface & Controls: Intuitive selection of plots and gesture controls for data interaction.
- Data Integration & Customization: Importing data and customizing visual elements.

### Hardware Compatibility
Ensures compatibility with various AR and mobile devices.

### How to Use

- Run the code in the Jupyter Notebook to generate a 3D data visualization.
- Upon execution, a barcode (QR code) is produced within the Notebook's output.
- Scan this barcode using a mobile device's camera to view the 3D plot in augmented reality.

Alternatively, if you prefer a static model for analysis:

- In the Jupyter Notebook code, ensure there is a line of code that triggers the conversion of the 3D plot into downloadable file formats: USDZ, GLB, and glTF.
- Run the code, and the conversion process will automatically begin.
- After the conversion, the files in USDZ (for iOS), GLB, and glTF (for Android) formats will be downloaded to your local machine.
- Transfer the downloaded files to your mobile device.
- Open the files on your mobile device to view and analyze the static 3D plot.

These steps provide two options for viewing 3D plots generated from the Jupyter Notebook—either interactively in AR or as static models in supported file formats on mobile devices.

### Quantitative Study

We evaluated the user interface's intuitiveness through manual logging of user interaction durations and actions within the AR environment, highlighting an average interaction duration of 10.5 minutes.

### Qualitative Study

Post-interaction, participants provided feedback on their experiences, indicating a general impression of increased data comprehension and the usefulness of features like data point highlighting and interactive legends.

### Team
- Suchith Reddy Vemula
- Rakshith Kumar Meesala
- Mani Deepak Telaprolu
