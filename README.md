# online hard examples mining  support for Fast R-CNN on caffe

# usage 

1. make caffe
2. cd lib
3. python setup.py

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