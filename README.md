# Implant Placement Software (IPS) - Surgical Guide CAD System
We design a novel and simple-to-use CAD system to assist the dentists to design the guide plate, which can accurately locate the position of implant on the guide plate by the automatic detection of metal anchors in CBCT images and registration of the detected metal anchors and target anchors on the reference coordinate system. 

## Project Overview
**IPS** is an intelligent dental implant planning software that automates surgical guide design by:
1. **Support for Importing and Processing DICOM and STL Files**
   - The software can import and process both DICOM and STL files, enabling synchronized viewing of Multi-Planar Reconstruction (MPR) and dynamic adjustment of window width and level.
2. **Measurement and Annotation Tools**
   - It offers tools for measuring length and angles, real-time bone density reading, as well as brush and line annotation tools, supporting image dragging and resetting.
3. **Virtual Placement and Fine-tuning of Implants**
   - The system supports the virtual placement and fine-tuning of various implant models.
4. **Automatic Detection and Interactive Adjustment of Metal Anchors**
   - It automatically detects metal anchors in CBCT images and allows for interactive adjustment of the correspondence between detected anchors and guide plate anchors, achieving automatic registration.
   - 
![image](https://github.com/user-attachments/assets/640eb391-03c2-4511-9e4e-a47a61f08eca)

## Technical Specifications

### Development Stack
| Component | Technology |
|-----------|------------|
| GUI Framework | PyQt5 5.15 |
| 3D Rendering | VTK 9.2 |
| Medical Imaging | SimpleITK 2.2 |
| Geometry Processing | NumPy 1.24, SciPy 1.10 |
| DICOM I/O | pydicom 2.3 |

```bash
# Quick install dependencies
pip install pyqt5 vtk simpleitk numpy scipy pydicom
