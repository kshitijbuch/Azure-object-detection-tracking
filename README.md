# Azure-object-detection-tracking
Developed as part of Deakin University’s Engineering AI Solutions module. Combines Azure Computer Vision, Custom Vision, and OpenCV for small-object tracking in video frames.

# Object Detection & Tracking with Azure Computer Vision and Custom Vision

This project demonstrates a complete pipeline for object detection and tracking using Microsoft Azure's Computer Vision and Custom Vision APIs. It was developed as part of the SIG788 - Engineering AI Solutions module at Deakin University.

##  Overview

The solution is divided into two parts:

### Part 1: Object Detection (Static Images)
- Utilizes **Azure Computer Vision REST API** to detect objects in user-uploaded images.
- Extracts bounding box coordinates and classification labels.
- Visualizes results using Python libraries: `PIL`, `matplotlib`, and `ipywidgets`.

### Part 2: Object Tracking (Video Frames)
- Uses **Azure Custom Vision** to track objects across video frames.
- Trained a custom model using manually labeled images.
- Annotates bounding boxes and tracks object trajectories.
- Reconstructs annotated video and exports movement data to CSV.

---

##  Technologies Used

- Python (Jupyter Notebooks)
- Azure Computer Vision API
- Azure Custom Vision SDK
- OpenCV
- PIL (Python Imaging Library)
- Matplotlib
- ipywidgets
- CSV export

---

##  Key Features

- Interactive image upload and detection via Jupyter Notebook.
- REST API integration for object recognition.
- Bounding box annotation with confidence scores.
- Frame-by-frame video analysis using a trained Azure Custom Vision model.
- Trajectory plotting and CSV export for movement analytics.
- Final video reconstruction with annotated frames.

---

##  Performance Metrics

From Azure Custom Vision portal:
- **Precision**: 100%
- **Recall**: 84.6%
- **mAP**: 95.2%

---

##  Sample Outputs

- Annotated images with bounding boxes and labels.
- JSON response parsing for object metadata.
- Trajectory plots showing object movement across frames.
- Final video output: `tracked_output.mp4`

---

##  Documentation

Full methodology, evaluation, and screenshots are available in the [report.pdf](./report.pdf).

---

##  References

- [Azure Computer Vision Documentation](https://learn.microsoft.com/en-us/azure/cognitive-services/computer-vision/)
- [Azure Custom Vision Documentation](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/)
- [OpenCV](https://docs.opencv.org/)
- [Pillow (PIL)](https://pillow.readthedocs.io/)

---

## Contact

**Author**: Kshitij Buch  
**LinkedIn**: [linkedin.com/in/kshitij-buch-609752181](https://www.linkedin.com/in/kshitij-buch-609752181)

---

