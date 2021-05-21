# spidey-sense-js

Anomaly Detector in Javascript
Presented in a Jupyter Notebooks

https://github.com/rondagdag/spidey-sense-js/blob/main/SpideySense-Anomaly-js.pdf

----
Install tslab
https://github.com/yunabe/tslab#installing-tslab

Rename sample.env to .env
Get your api keys using Azure CLI, replace <your-resource-group-name> and <your-resource-name> with your own unique names:
``` 
az cognitiveservices account create --kind AnomalyDetector --resource-group <your-resource-group-name> --name <your-resource-name>
```

edit .env file specify

API_KEY=

ENDPOINT=

Run
``` 
npm install
```

Open Jupyter Notebook
