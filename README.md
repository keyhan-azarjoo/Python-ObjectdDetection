# Object Detection with YOLOv8

A real-time object-detection project built on the YOLOv8 deep-learning model.

## What it does
Detects and classifies multiple object types in real time — people, cars, bicycles, buses, trucks, motorcycles — drawing bounding boxes and class labels on live video / image input.

## How it works
YOLOv8 performs single-pass detection: the image is processed once by the network, which simultaneously predicts bounding boxes and class probabilities, achieving real-time frame rates suitable for edge devices.

## Role within my work (MyOTGO)
This is the basis of the **real-time people- and vehicle-counting system I deployed on Raspberry Pi edge devices** — used for crowd monitoring, traffic analysis and (combined with GPS / Bluetooth) advertisement-impression estimation. Object detection is a core building block of MyOTGO's edge-AI camera nodes.

## Tech
Python · YOLOv8 (Ultralytics) · OpenCV.

Author: **Keyhan Azarjoo**.
