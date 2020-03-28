## COVID-19 image data collection

We are building a database of COVID-19 cases with chest X-ray or CT images. We are looking for COVID-19 cases as well as [MERS](https://en.wikipedia.org/wiki/Middle_East_respiratory_syndrome), [SARS](https://en.wikipedia.org/wiki/Severe_acute_respiratory_syndrome), and [ARDS](https://en.wikipedia.org/wiki/Acute_respiratory_distress_syndrome). 

All images and data will be released publicly in this GitHub repo. Currently we are building the database with images from publications as they are images that are already available. 

## View current [images](images) and [metadata](metadata.csv)

Current stats. Labels 0=No or 1=Yes. Data loader is [here](https://github.com/mlmed/torchxrayvision/blob/master/torchxrayvision/datasets.py#L814)
``` 
{'ARDS': {0.0: 85, 1.0: 4},
 'Bacterial Pneumonia': {0.0: 83, 1.0: 6},
 'COVID-19': {0.0: 23, 1.0: 66},
 'MERS': {0.0: 89},
 'No Finding': {0.0: 88, 1.0: 1},
 'Pneumonia': {0.0: 2, 1.0: 87},
 'SARS': {0.0: 78, 1.0: 11},
 'Streptococcus': {0.0: 83, 1.0: 6},
 'Viral Pneumonia': {0.0: 12, 1.0: 77}}
 ```

## Contribute

 - We can extract images from publications. Help identify publications which are not already included using a GitHub issue (DOIs we have are listed in the metadata file). There is a searchable database of COVID-19 papers [here](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/global-research-on-novel-coronavirus-2019-ncov).
 
