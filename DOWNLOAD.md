Dataset **Aerial Cows** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/h/7/nl/ub8YopkOzIHTURYIpZ0uEG5VqDk4hVU7fOxwkLMCdxFMMqbrbsYcMkwsdO1bKszf7hcTUG8Qm2y1ucnXV7eULaZJHgFOML205yiMbXYvDtpC4bklxBtmhrCF92SG.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Aerial Cows', dst_path='~/dtools/datasets/Aerial Cows.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/roboflow-100/aerial-cows/dataset/2/download)