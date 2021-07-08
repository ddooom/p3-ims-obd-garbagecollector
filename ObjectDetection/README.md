# Wrap-Up Report
- 실험 과정 및 회고 : [Wrap-Up Report](https://github.com/ddooom/p3-ims-obd-garbagecollector/blob/DongWoo/ObjectDetection/Det_Warp_Up_Report.pdf)

<br>

# How to use

### Check dataset
``` bash
python dataset.py --config [config]
```

### Check the model
``` bash
python model.py --config [config]
```

### Train
1. train.ipynb
2. change config 
3. run all


### Inference
``` bash
python inference.py --config_name [config]
```

### Ensemble
1. k-fold.ipynb
2. TTA.ipynb
3. ensemble_nms.ipynb
