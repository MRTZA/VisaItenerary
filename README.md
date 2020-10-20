# VisaItenerary

Visa Itinerary is a suite of predictive machine learning scores related to a cardholder’s travel behavior that can help you provide marketing campaigns to cardholders already flagged by the travel predict API. This add-on will allow you to provide a “route” at the cardholders' travel destination with geographical locations and/or merchant categories that they are most likely to spend at. This will allow you to guide travelers to merchants they might be interested in and provide incentives to purchase goods and services there. 

## Local Setup Instructions

### Prequisites:

* Install Anaconda from self service
    * Use this to configure: https://devel.visa.com/environment/tools.html#configuration
    
### Create conda env and run jupyter lab:

```bash
conda env create -f environment.yml
conda activate VisaItenerary
jupyter-lab
```

### Alternative setup:

```bash
conda create --name VisaItenerary python=3.5
conda activate VisaItenerary
conda install -c conda-forge jupyterlab
conda install pandas
conda install -c conda-forge folium
jupyter-lab
```