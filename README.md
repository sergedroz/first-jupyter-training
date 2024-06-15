# first-jupyter-training

Training: Jupyter Notebooks, Data Analysis and Incident Response


This is a gentle introduction to the use of [Jupyter](https://jupyter.org/) Notebooks in Incident Response and Digital Forensics. It's part of the FIRST.org training curriculum. The notebooks are generic enough to run on a modest infrastructure. 


Authors: Serge Droz and Éireann Leverett

License: This material is available under the [Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license. This course includes GeoLite2 Data created by MaxMind, available from  [https://www.maxmind.com](https://www.maxmind.com/).

There are currently four modules available:

 - Lesson_01: A more systematic introduction, suitable for self study
 - Lesson_02: Builds on the previous notebook and looks at the use of APIs to enrich an analysis. This will not run in Jupyterlite.
 - Lesson_03: An example focusing on data analysis and statistics

## Requirements

We recommend [micromamba](https://mamba.readthedocs.io/en/latest/user_guide/micromamba.html) to setup your environments

Besides Jupyterlab the following modules are needed:
 
 pandas httpx matplotlib lifelines scipy squarify gcc gxx dnspython geoip2 folium firefox
 
 pip: pysubnettree
 
## Coming soon

 - Tutorial: A simple notebook demonstrating how data can be analyzed
 - Cowrie: A somewhat more involved notebook to analyze honeypot logs

