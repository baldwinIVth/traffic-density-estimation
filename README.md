

# **Vehicle Detection Using YOLOv8: A Fine-Tuned Approach**  

This project aims to detect vehicles in top-view images using a fine-tuned YOLOv8 model. By leveraging transfer learning on pre-trained weights from the COCO dataset, the model achieves robust detection performance for cars, trucks, and other vehicles in aerial views.  

---

## **Project Details**  

- **Model Used**: YOLOv8  
- **Base Weights**: COCO pre-trained (`yolov8n.pt`)  
- **Learning Rate**: 0.0001  
- **Batch Size**: 16  
- **Epochs**: 10  
- **Image Size**: 480 pixels  
- **Optimizer**: AdamW  

### Key Features:  
1. Anchor-free architecture for faster and simpler inference.  
2. Distribution Focal Loss (DFL) for accurate bounding box localization.  
3. Fine-tuned for domain-specific object detection in challenging environments.  

---

## **Dataset Information**  

The dataset comprises aerial images of vehicles, curated to include diverse conditions such as lighting, vehicle sizes, and traffic scenarios.  

- **Source**: Pexels (custom annotations for object detection).  
- **Training Set**: 536 images.  
- **Validation Set**: 90 images.  

Annotation format includes bounding boxes and vehicle categories (e.g., car, truck).  

---

