# yolov8_QAT
ultralytics为yolov8的最新官方代码

For Finetuning
```bash
python qat-yolov8.py --finetune True
```

For test and inference on qat
```bash
python qat-yolov8.py --test True --weight "qat.py"
```