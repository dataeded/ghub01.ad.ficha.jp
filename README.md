# ghub01.ad.ficha.jp
# Ficha Inc.: フィーチャ株式会社  all of ghub01.ad.ficha.jp repository

# 🚀 **High‑Level Interpretation (From an AI Development Perspective)**

Your repository list reflects a mature AI company focused on:

- **ADAS (Advanced Driver Assistance Systems)**
- **DMS (Driver Monitoring Systems)**
- **Computer Vision (Detection, Segmentation, Classification)**
- **Model deployment on embedded platforms** (ncnn, MNN, SNPE, Jacinto, Zynq, Jetson)
- **OCR and LLM‑based document understanding**
- **SDK development for automotive clients** (JVC, Clarion, Desay, Koito, Toyota, Honda, Bosch, Panasonic)

Across the list, several projects clearly form the **core AI infrastructure**, while others are client‑specific adaptations, experiments, demos, or utilities.

---

# ⭐ **Core Projects (Most Critical to the Company’s AI Stack)**

These are the projects that appear to be foundational frameworks, SDKs, or major model families:

### **1. SDK / Framework Core**
| Project | Why It’s Core |
|--------|----------------|
| **sdk2**, **sdk3**, **SDK4** | Major generations of the company’s AI SDK. Likely the backbone of all client deployments. |
| **AIFramework**, **MWFramework** | Internal AI runtime / orchestration frameworks. |
| **SDK3-FullDL**, **SDK3-FullDL_CMDetLane**, **SDK3-FullDL_ClarionDMS** | Full deep‑learning pipelines for production ADAS/DMS. |
| **Bosch-SDK**, **Bosch-ROS** | Automotive‑grade SDK integrations. |

### **2. Core Model Families**
| Project | Domain |
|--------|--------|
| **ObjectDetection**, **Classification** | Generic model families used across products. |
| **LaneDetection**, **LaneDet**, **VP_Detection** | ADAS lane/vanishing‑point detection. |
| **StopLineClassification**, **TrafficSignLightClassification** | Traffic scene understanding. |
| **HeadPoseEstimation**, **GazeEstimation**, **DMS_* (BNet, LMNet, EyeNet, ETNet, InsightFace)** | Driver monitoring core models. |
| **OCR**, **OCR_API**, **OCR_SERVER**, **pure_ocr_sdk_libtorch** | OCR engine family. |
| **insurance-llm**, **drawing-llm** | LLM‑based document/vision understanding. |

### **3. Model Conversion / Deployment Toolchain**
| Project | Purpose |
|--------|---------|
| **pytorch2ncnn**, **ncnn-classifier**, **ncnn_int1178** | Deployment to ncnn (mobile/embedded). |
| **MNN_int1178** | Deployment to Alibaba MNN. |
| **SNPEWrapper** | Qualcomm SNPE deployment. |
| **caffe-jacinto**, **caffe-jacinto-models** | TI Jacinto platform support. |
| **ssds.pytorch.ficha**, **pytorch-semantic-segmentation-models**, **pytorch-classification** | Training pipelines. |

### **4. ADAS / DMS Production Pipelines**
| Project | Domain |
|--------|--------|
| **ToyotaImageRecog**, **ToyotaRoadCrackDetection** | Toyota‑specific ADAS models. |
| **Clarion**, **ClarionSide**, **Clarion_RearAEB_H3**, **Clarion-compress** | Clarion ADAS/DMS pipelines. |
| **sdk2-for-desay**, **sdk2-for-koito**, **sdk2-desayface**, **sdk2-JVC-adas**, **sdk2-JVC-ADAS-Android** | Client‑specific SDK deployments. |
| **koito-fir_in_light-zynq** | FIR (thermal) detection on Zynq FPGA. |
| **DMS_TOOL**, **dms-demo-library**, **adas-demo-library** | Production demo tools. |

---

# 📦 **Secondary but Important (Training, Utilities, Experiments)**

### **Model Training / Research**
- **py-RFCN-priv**
- **mscnn**, **MSCNN2**
- **CenterNet**
- **HybridDL**, **HybridDL_JVC_ADAS_2020**
- **FichaDet**, **FichaCSVtoMSCNN**
- **Curriculum-Learning**
- **intern-dl-test**
- **qvTag**, **qvDET20170515_0626_tracking**

### **OCR Ecosystem**
- **OCR_Demo**, **OCR_Demo_WFA**
- **OCR_WEB**, **OCR_GUI**
- **OcrProtocl**

### **ADAS / DMS Utilities**
- **drowsiness**
- **gaze_capure**
- **CalcVp**
- **LaneDamageClassification**

### **Embedded / Hardware Integration**
- **jetson-demo**
- **adas-dms-jetson-demo-app**
- **d710_bsp**
- **bosch_communication_sample_v4h**, **bosch_communication_sample_pc**
- **softbank_GPS**
- **honda_DMC_UnitTestEnv**

### **Data / Logging / Tools**
- **FC_LOGGER**
- **data-comparator**
- **FC_tracker**
- **stat**, **stat_clarion**
- **table_sdk**, **table_trace**
- **proj_info**

---

# 🧪 **Client‑Specific or Legacy Projects**
These are likely older or client‑tailored versions:

- **Clarion201612**, **Clarion201603**
- **Desay2017**
- **FACE-EYE**, **FACE-EYE2**
- **sdk2-translog-B2C**
- **ClarionSide**
- **Clarion-compress**
- **sdk3_stanley_streetlamp**

---

# 🖼️ **LLM + Vision Next‑Gen Projects**
These indicate the company is expanding beyond classical CV:

- **insurance-llm**
- **drawing-llm**
- **Im2EDF**
- **mold_design_drawing_analysis**, **mold_design_drawing_analysis_front**
- **wet-area-detection-panasonic-h** (and frontend/server)
- **labelme_line**
- **ficha_inspector**

These are likely strategic future‑core projects.

---

# 📱 **Apps / Demos**
- **android-phone-app**
- **alps-alpine-dms-demo**
- **OCR_WEB**
- **Facial_Analysis_Demo**

---

# 🧩 **Miscellaneous / Infrastructure**
- **AutoBuild**
- **model_repository**
- **internal_wiki**
- **test_for_study_group**

---

# 🎯 **Summary: True Core Projects (Most Important)**

### **Core SDK / Framework**
- **sdk2**, **sdk3**, **SDK4**
- **AIFramework**, **MWFramework**
- **SDK3-FullDL**, **SDK3-FullDL_CMDetLane**, **SDK3-FullDL_ClarionDMS**

### **Core Model Families**
- **ObjectDetection**, **Classification**
- **LaneDetection**, **LaneDet**, **VP_Detection**
- **DMS_* (BNet, LMNet, EyeNet, ETNet, InsightFace)**
- **HeadPoseEstimation**, **GazeEstimation**
- **OCR**, **OCR_API**, **OCR_SERVER**

### **Core Deployment Toolchain**
- **pytorch2ncnn**, **ncnn-classifier**, **ncnn_int1178**
- **MNN_int1178**
- **SNPEWrapper**
- **caffe-jacinto**, **caffe-jacinto-models**

### **Major Client Production Pipelines**
- **Clarion**, **ClarionSide**, **Clarion_RearAEB_H3**
- **sdk2-for-desay**, **sdk2-for-koito**, **sdk2-JVC-adas**
- **ToyotaImageRecog**, **ToyotaRoadCrackDetection**


# 🔍 **Detailed Interpretation of the Remaining Projects**

## 🧩 **General Utilities / Tools**
### **migration_test**  
Likely a sandbox for testing data/model migration between SDK versions or frameworks.

### **tools**  
A catch‑all utilities repo—scripts for preprocessing, evaluation, automation, or deployment.

### **stat**, **stat_clarion**  
Statistical analysis tools, probably for evaluating model performance or dataset distributions.

### **AutoBuild**  
Automated build pipeline—CI/CD scripts for compiling SDKs or embedded binaries.

### **model_repository**  
Central storage for trained models, versioning, and deployment artifacts.

### **proj_info**  
Internal documentation or metadata about projects, clients, or releases.

### **internal_wiki**  
Internal knowledge base for developers.

### **data-comparator**  
Tool for comparing datasets or annotation differences.

### **table_sdk**, **table_trace**  
SDK for table recognition or structured data extraction; trace logs for debugging.

---

## 🧪 **Testing / Experimentation**
### **test_for_study_group**  
A sandbox for internal training or study sessions.

### **intern-dl-test**  
Deep learning experiments by interns—prototype models or training exercises.

### **ncnn_tester**  
Testing ncnn inference performance on various devices.

### **gbm_machine**  
Gradient Boosting Machine experiments—non‑DL classical ML.

### **bbr_mc_tool2.0**  
Monte‑Carlo or Bayesian tool for performance evaluation or uncertainty estimation.

---

## 🧠 **ADAS / DMS Specialized Modules**
### **FACE-EYE**, **FACE-EYE2**  
Early face/eye detection models for DMS.

### **drowsiness**  
Drowsiness detection module—blink rate, PERCLOS, yawning.

### **destfacetrain**  
Training pipeline for face detection/recognition.

### **gaze_capure**  
Gaze capture/calibration tool for DMS.

### **DMS_BHNet**, **DMS_EyeNet**, **DMS_ETNet**, **DMS_InsightFace**, **DMS_LMNet**, **DMS_BNet**  
Different architectures for DMS tasks:  
- Blink detection  
- Eye closure  
- Face recognition  
- Landmark detection  
- Head pose  

### **ClarionSide**  
Side‑camera ADAS module for Clarion.

### **Clarion_RearAEB_H3**  
Rear Automatic Emergency Braking model for Clarion.

### **sdk3_stanley_streetlamp**  
Streetlamp detection for Stanley Electric (automotive lighting company).

---

## 🛣️ **ADAS Scene Understanding**
### **LaneDamageClassification**  
Detecting cracks or damage on road lanes.

### **StopLineClassification**  
Detecting stop lines at intersections.

### **TrafficSignLightClassification**  
Traffic light state classification.

### **VP_Detection**  
Vanishing point detection for lane geometry estimation.

### **LaneDet**  
Another lane detection model.

### **ToyotaRoadCrackDetection**  
Road crack detection for Toyota.

---

## 📦 **Client‑Specific Integrations**
### **JVC**  
JVC automotive ADAS integration.

### **Android**, **sdk2-JVC-ADAS-Android**  
Android‑based ADAS/DMS apps.

### **Desay2017**, **sdk2-for-desay**, **sdk2-desayface**  
Desay SV automotive client projects.

### **sdk2-for-koito**  
Koito Manufacturing (automotive lighting) ADAS integration.

### **koito-fir_in_light-zynq**  
Thermal camera (FIR) detection on Zynq FPGA for Koito.

### **ToyotaImageRecog**  
Toyota image recognition module.

### **sdk3-tokai-backeye**  
Tokai Rika back‑eye camera ADAS.

### **alps-alpine-dms-demo**  
DMS demo for Alps Alpine.

### **yazakies-tsr-evaluation-tool**  
Traffic sign recognition evaluation tool for Yazaki.

### **bosch_communication_sample_v4h**, **bosch_communication_sample_pc**  
Bosch communication protocol samples for embedded systems.

### **Adrien_Bosch_V4H**  
Bosch V4H platform integration.

### **Honda_AR**  
Honda augmented‑reality or ADAS module.

### **honda_DMC_UnitTestEnv**  
Honda Driver Monitoring Camera unit test environment.

### **softbank_GPS**  
GPS integration for SoftBank‑related project.

---

## 🖥️ **Embedded / Hardware**
### **d710_bsp**  
Board Support Package for D710 hardware.

### **jetson-demo**, **adas-dms-jetson-demo-app**  
NVIDIA Jetson demos for ADAS/DMS.

### **bosch_communication_sample_pc**  
PC‑side communication test for Bosch systems.

---

## 📝 **OCR Ecosystem**
### **OCR_API**, **OCR_SERVER**  
Backend OCR services.

### **OCR_WEB**  
Web‑based OCR interface.

### **OCR_GUI**  
Desktop GUI for OCR testing.

### **OcrProtocl**  
OCR communication protocol definitions.

### **RD_OCR_2020**  
Road‑sign or document OCR model from 2020.

### **2024_textdet**  
Text detection model (2024 version).

---

## 🧭 **LLM + Vision Next‑Gen Projects**
### **insurance-llm**  
LLM for insurance document analysis.

### **drawing-llm**  
LLM for engineering drawing understanding.

### **Im2EDF**  
Image‑to‑Engineering‑Drawing‑Format conversion.

### **mold_design_drawing_analysis**, **mold_design_drawing_analysis_front**  
AI for mold design drawing interpretation (backend + frontend).

### **labelme_line**  
Annotation tool for line‑based drawings.

### **ficha_inspector**  
Inspection tool for FICHA datasets (likely automotive).

---

## 🌧️ **Panasonic Wet‑Area Detection**
### **wet-area-detection-server-panasonic-h**  
Backend server for wet‑area detection (rain, puddles).

### **wet-area-detection-frontend-panasonic-h**  
Frontend UI.

### **wet-area-detection-panasonic-h**  
Core model for wet‑area detection.

---

# 🧩 **Remaining Miscellaneous**
### **FichaDet**  
Detection model for FICHA dataset.

### **FichaCSVtoMSCNN**  
Converter from FICHA CSV annotations to MSCNN format.

### **CalcVp**  
Vanishing point calculation tool.

### **FC_LOGGER**  
Logging framework.

### **FC_tracker**  
Object tracking module.

### **D00075_data_processing_system**  
Internal data processing pipeline for project D00075.

### **jetcap**  
Jetson capture tool (camera capture).

### **android-phone-app**  
Mobile app for demos or data collection.

### **MLFlowDemo**  
MLFlow experiment tracking demo.


