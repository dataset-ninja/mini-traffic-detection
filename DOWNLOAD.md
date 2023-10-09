Dataset **Mini Traffic Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/j/R/j2/2waCkf9tOmhiHW1sMrzyqBrvkY9IHPe7KC4LQhqHz7g1GLooyvcbUVJv3dqBYH9Nib3AtJSzesWJ6zAzp05zC2ZGuhhMzzb0mjfn3WvAcvY5wtXlHlZ4NmTBt8Al.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Mini Traffic Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/zoltanszekely/mini-traffic-detection-dataset).