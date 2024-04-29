# Vision project with updated tensorflow

## Environment setup with conda

```bash
conda create -n tf python=3.11 numpy pandas
```

Note requeriments.txt version were made to match Google Colab environment in the moment of the development of this project to facilitate development.

Note: Keras 3 will not function with TensorFlow 2.14 or earlier.

## Colab versions

Python 3.10.12

## Models used

### Keras YOLOv8

https://www.kaggle.com/models/keras/yolov8

https://www.kaggle.com/models/keras/yolov8/keras/yolo_v8_l_backbone

Guide:

https://colab.research.google.com/github/keras-team/keras-io/blob/master/guides/ipynb/keras_cv/object_detection_keras_cv.ipynb#scrollTo=o3SFnISHdIzw

### Google mobilenet-v2

https://www.kaggle.com/models/google/mobilenet-v2

## References

Roboflow Datasets: https://public.roboflow.com/object-detection

Tensorflow Datasets: https://www.tensorflow.org/datasets/catalog/overview#object_detection

