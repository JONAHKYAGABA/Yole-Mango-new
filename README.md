# Yolo-Mango-new
YOLOMANGO_NEW: Mango Damage Dataset Processing &amp; Augmentation This project prepares, augments, and balances a YOLO-format mango damage dataset
📦 Project Structure
Dataset Input: YOLOv11-format dataset with mango and damage annotations

Segmentation & Cropping: Extracts mangoes using polygon or bounding box annotations

Overlay & Filtering: Identifies damage types within each mango region

Label Rewriting: Rewrites annotations in YOLO format with remapped class indices

Augmentation: Applies controlled augmentations to minority classes

Balancing: Rebalances dataset with custom target sizes

Re-splitting: Applies stratified train/val/test splitting with class preservation
