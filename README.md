 this is unoffical version : online hard examples mining  support for Faster R-CNN end to end on caffe

 Training Region-based Object Detectors with Online Hard Example Mining
 http://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Shrivastava_Training_Region-Based_Object_CVPR_2016_paper.html
 
 the offical version on fast rcnn(not end to end):
 https://github.com/abhi2610/ohem



# usage 

1. cd caffe
2. mdkir build
3. cmake ..
4. make all
5. cd lib
6. python setup.py

the model.prototxt is in

```
models\pascal_voc\VGG16\FP_Net_end2end\train.prototxt
```

train:
```
./experiments/scripts/FP_Net_end2end.sh 1 VGG16 pascal_voc
```
test:
```
./test.sh 1 VGG16 pascal_voc

```
1 is your gpu index