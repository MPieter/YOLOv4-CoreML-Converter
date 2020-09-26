# keras-yolo4

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Introduction

A Keras implementation of YOLOv4 (Tensorflow backend) inspired by [allanzelener/YAD2K](https://github.com/allanzelener/YAD2K) and [qqwweee/keras-yolo3](https://github.com/qqwweee/keras-yolo3) that is exported to CoreML via coremltools.


---

## Quick Start

```
python convert.py yolov4.cfg yolov4.weights model_data/yolov4.mlmodel --keras_output_path model_data/yolov4.h5
```

To also export the intermediate Keras model use the argument `--keras_output_path`.

## Tested with

    - Python 3.7.3
    - Keras 2.2.4
    - tensorflow 2.2.0
    - coremltools 4.0b3
