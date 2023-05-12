# Digitisation-2D-Sections-From-Scan-Images
Generally, we digitise legacy data in geosciences, such as interpreted geological or seismic sections. Digitisation is creating a computerised representation of a printed analogue.

Aim and Rationale
==================
ML techniques are a powerful tool that is being increasingly used in geology to extract valuable information from large amounts of data. Geological cross-sections from coal mines are a valuable source of information for building ML models that can aid in the exploration, exploitation, and management of mineral resources. However, the effectiveness of these models depends on the quality of the data used to train them. This chapter discusses the importance of scanning, georeferencing, and digitising interpreted geological cross-sections from coal mines data to build accurate and reliable ML datasets.

The aim of the scan, georeference, and digitising of multiple geological subsurface cross-sections of the Carboniferous Ruhr basin mining datasets is to create a high-quality dataset suitable for ML applications. The data, consisting of interpreted subsurface cross-sections from coal mines in the Ruhr basin, lower Rhine basin, Germany, is in the form of old hard copies that require digital transformation to be useful for modern ML algorithms. The rationale for these steps is the need to convert the data into digital formats that can be easily processed, analysed, and utilised for ML applications. These steps are essential for ML applications, as it enables the creation of more robust and accurate models that can be used for various geological analyses and predictions.

Scanning and georeferencing the hard copies enable the creation of accurate digital images that retain the spatial information of the original data. This information is crucial for creating accurate geological models that capture the subsurface geological structures and variations. These steps ensure the creation of accurate, high-quality data that can be used for various geological analyses and predictions. The data generated can enhance the efficiency and accuracy of geological exploration and resource management, making it a valuable resource for academia and industry.

The importance of these steps in generating a dataset for geological ML applications cannot be overemphasised. The accurate digital cross-sections and geological models provide a solid foundation for ML algorithms to extract relevant geological features, patterns, and trends. The data can be used for various ML applications, such as creating 2D and 3D models, guiding and validating subsurface interpretations, interpreting complex structures, identifying mineral deposits, predicting subsurface geological features, and characterising reservoirs for hydrocarbon exploration and production. In conclusion, scanning, georeference, and building multiple geological interpretation models of the Carboniferous Ruhr basin mining datasets are critical steps in generating a dataset for geological ML applications. 

Data and Materials
===================

The dataset has been divided into four sub-study areas labelled as Area -1, Area -2, Area -3, and Area -4. Area -1 covers the Tectonic map of the Emscher and Essener main field with 14 vertical sections, one legend, and no diagrams or sketches. This sub-study area is located in the Western Ruhr region, which is one of the main field areas for mining. Area -2 includes the Tectonic map of the Bochumer Hauptmulde, which contains 29 vertical sections, a legend, a diagram, and a sketch. This area is situated in the Eastern Ruhr region. Area -3 comprises the Tectonic map of the Emscher and Essener with 20 vertical sections, a legend, two diagrams, and two sketches. It is located in the Middle Ruhr region. 

1. Link to dataset https://drive.google.com/drive/folders/1j4PBXQyVx89rkVTvMS7Yjl7e7y5OTDrC?usp=sharing
2. Link to dataset https://drive.google.com/drive/folders/1EabQCWqC1JExdLTRCJRx8MDAGHAhHy5N?usp=sharing
3. Link to Google Models https://drive.google.com/drive/folders/1wgVieumdVUn99fagCtYHAmZTF2j5U-th?usp=sharing

Digitise Cross-sections
========================

In this study, a tool was built using Python to automatically digitise subsurface cross-sections. The tool was designed to improve the efficiency and accuracy of the data digitisation process, as well as to reduce the potential for human error. The use of this tool resulted in the successful digitisation of 8 maps, 131 cross-sections, 3 legends, 3 diagrams, and 3 sketches. Examples of cross-sections are shown in Figure 14, Figure 15 and Figure 16.The tool was found to be highly effective in digitising the data, with a high degree of accuracy and consistency. The tool developed in this study has demonstrated its potential as a valuable asset for the geology community, enabling the efficient and accurate digitisation of subsurface cross-sections. The results obtained from this study represent an important step forward in the development of automated tools for geological data analysis and visualisation.

The outcomes from this study demonstrate the potential of using automated tools in the field of geology to improve data analysis and visualisation. The use of Python in this study highlights the benefits of using programming languages to streamline and automate data analysis processes. Further research in this area could focus on expanding the capabilities of the tool to include additional data types, such as seismic or gravity data. Additionally, the use of ML algorithms could further improve the accuracy and efficiency of the data digitisation process.

![Example](https://i.imgur.com/prUy7Nn.jpg)

![Example](https://i.imgur.com/KEL7ltX.png)

![Example](https://i.imgur.com/gCNfPX3.png)

![Example](https://i.imgur.com/VFwnr8Z.png)

![Example](https://i.imgur.com/hrbY2t5.png)

![Example](https://i.imgur.com/Nl6gukX.png)

![Example](https://i.imgur.com/EOhNDS3.png)

![Example](https://i.imgur.com/mg2XY6o.png)

![Example](https://i.imgur.com/Tpakohx.png)

![Example](https://i.imgur.com/vSR3xWB.png)

![Example](https://i.imgur.com/gfiCROq.png)

![Example](https://i.imgur.com/szdOWvU.png)

![Example](https://i.imgur.com/BeGXWdJ.png)

Acknowledgements 
=================
The work contained in this repositories contains work conducted during a PhD study undertaken as part of the Natural Environment Research Council (NERC) Centre for Doctoral Training (CDT) in Oil & Gas funded 50% through its National Productivity Investment Fund grant number NE/R01051X/1 and 50% by the University of Aberdeen through its PhD Scholarship Scheme. The support of both organisations is gratefully acknowledged. The work is reliant on Open-Source Python Libraries, particularly numpy, matplotlib, plotly and pandas and contributors to these are thanked, along with Jovian and GitHub for open access hosting of the Python scripts for the study.

![University of Aberdeen](https://pbs.twimg.com/profile_images/1572172791801061377/UPSWmPyN_400x400.jpg)

![NERC-CDT](https://nerc-cdt-oil-and-gas.ac.uk/wp-content/uploads/news/2015-news-NERC-funding.jpg)

![NERC](https://auracdt.hull.ac.uk/wp-content/uploads/2019/11/UKRI_NER_Council-Logo_Horiz-RGB.png)

![CDT](https://i.imgur.com/QDOhcN3.png)
