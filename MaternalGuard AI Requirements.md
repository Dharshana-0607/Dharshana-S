# MaternalGuard AI – Requirements Document

## 1. Project Overview

MaternalGuard AI is an AI-based maternal health risk prediction system designed to assist frontline healthcare workers in identifying high-risk pregnancies at an early stage. The system uses routine pregnancy health parameters to classify maternal risk levels and generate timely alerts for medical intervention.

The project aligns with the objectives of the :contentReference[oaicite:0]{index=0} by focusing on affordable, accessible, and scalable healthcare solutions for rural and underserved regions of India.

---

## 2. Objectives

- Enable early detection of high-risk pregnancies.
- Assist ASHA and ANM workers with AI-based decision support.
- Reduce maternal mortality through timely medical referrals.
- Provide a simple and reliable system for low-resource settings.
- Support digital healthcare initiatives in rural India.

---

## 3. Functional Requirements

### 3.1 Patient Data Entry
- Health workers shall be able to enter maternal health details.
- Input parameters include age, blood pressure, hemoglobin, glucose, BMI, and pregnancy history.
- Data validation should prevent incorrect or missing entries.

### 3.2 AI Risk Prediction
- The system shall analyze input data using a trained ML model.
- The model shall classify pregnancy risk into:
  - Low Risk
  - Medium Risk
  - High Risk
- The system shall display risk results instantly.

### 3.3 Risk Explanation
- The system shall highlight key contributing factors for the predicted risk.
- Explanations should be simple and understandable for health workers.

### 3.4 Alerts and Recommendations
- The system shall generate alerts based on risk level.
- High-risk cases shall be marked for immediate medical referral.
- Medium-risk cases shall be flagged for closer monitoring.

### 3.5 Patient Record Management
- The system shall store patient records locally.
- Health workers shall be able to view past records and predictions.

### 3.6 Offline Support
- The application shall function without continuous internet access.
- Predictions shall work using locally stored models.

---

## 4. Non-Functional Requirements

- The system should run on low-end Android devices.
- Prediction results should be generated within 5 seconds.
- The user interface should be simple and intuitive.
- Data stored on the device should be secure.
- The application should be lightweight.

---

## 5. User Roles

### Health Worker
- Enters patient health data.
- Views risk predictions and alerts.
- Tracks patient history.

### Doctor / Medical Officer
- Reviews high-risk cases.
- Provides treatment recommendations.
- Monitors maternal health trends.

---

## 6. System Constraints

- Limited availability of internet connectivity.
- Limited digital literacy among users.
- Restricted access to advanced medical equipment in rural areas.
- Dependence on manually entered health parameters.

---

## 7. Assumptions

- Health workers are trained to collect basic maternal health data.
- Input data is entered accurately.
- The AI model is trained on medically valid datasets.

---

## 8. Future Enhancements

- Integration with wearable health monitoring devices.
- Voice-based data entry in regional languages.
- SMS alerts to doctors and family members.
- Integration with government maternal health portals.
- Continuous model improvement using regional data.
