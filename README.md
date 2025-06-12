# wild_boar_human
yolo

!git clone https://github.com/ultralytics/yolov5
%cd yolov5
!pip install -r requirements.txt


#after training

25 epochs completed in 0.822 hours.
Optimizer stripped from runs/train/wildboar_human_detector/weights/last.pt, 14.4MB
Optimizer stripped from runs/train/wildboar_human_detector/weights/best.pt, 14.4MB

Validating runs/train/wildboar_human_detector/weights/best.pt...
Fusing layers... 
Model summary: 157 layers, 7015519 parameters, 0 gradients, 15.8 GFLOPs
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 9/9 [00:05<00:00,  1.54it/s]
                   all        262        817      0.916      0.851       0.92      0.573
             wild_boar        262        280      0.932      0.875      0.941        0.7
                 human        262        537      0.901      0.827      0.899      0.446
Results saved to runs/train/wildboar_human_detector
