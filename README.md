# Patents-and-Publications

This repository documents my filed patents and peer-reviewed publications in the domains of ADAS, autonomous systems, vehicle safety, and intelligent perception.

---

## 🧠 Patents

Filed **eight patents** at **Mercedes-Benz Research and Development India** as an **ADAS Engineer**, focused on advancing autonomous vehicle capabilities and critical safety systems.

### 1. Sectorial Direction Method for providing External Microphone Architecture for Emergency Vehicle Detection
**Application No:** 202411102439  

**Filed On:** December 24, 2024  

**Description:**  
The present disclosure provides a system and a method for positioning microphones around a vehicle. The method includes receiving one or more parameters from a user interface associated with the system and determining one or more sectors associated with the vehicle based on the one or more parameters. Further, the method includes determining a number of microphones for the one or more sectors based on the one or more parameters and positioning one or more microphones among the determined number of microphones in each of the one or more sectors. Therefore, the present disclosure eliminates the need for fixed microphone placements and an Artificial Intelligence (AI)/Machine Learning (ML) training, enabling flexible microphone positioning for specific vehicle sectors, which improves detection accuracy and adaptability in real-time.


---

### 2. System and Method for Enabling Real-Time Alerts for Sensory-Impaired Persons of Vehicle 
**Application No:** 202411099012  

**Filed On:** December 14, 2024  

**Description:**  
The present disclosure provides a system and a method for enabling real-time alerts for sensory-impaired persons in a vehicle. The system includes a controller which receives input data from one or more sensors corresponding to surrounding of the vehicle . The controller integrates the input data with one or more Advanced/Assisted Driver (AD) functions to enable one or more AD responses. The controller generates one or more real-time alerts based on the one or more AD responses and the input data. The controller provides the one or more real-time alerts to the one or more sensory-impaired persons using a preferred response mode comprising at least one of an interface unit , an audio unit, and a haptic feedback unit of the vehicle.

---

### 3. Automated Retract System for Outside Rear View Mirror (ORVM) in Vehicle and Method Thereof  
**Application No:** 202411101843  

**Filed On:** December 23, 2024  

**Description:**  
The present disclosure relates to automated retract system for outside rear-view mirror (ORVM) in vehicle, and method thereof. Image capturing unit is coupled to ORVM to capture real-time video feeds pertaining to vehicle’s surrounding. System detects one or more obstacles based on real-time video feeds. System measures longitudinal distance and lateral distance of vehicle corresponding to detected one or more obstacles. System identifies detection points based on longitudinal and lateral distance of vehicle corresponding to one or more obstacles. System applies pre-defined threshold constraint on detection points to determine target position of each of ORVM of vehicle. System automatically moves ORVM from an original position to target position based on pre-defined threshold constraints.


---

### 4. System and Method for Adjusting a Suspension Unit of a Vehicle 
**Application No:** 202511050515  

**Filed On:** May 26, 2025  

**Description:**  
The Automated Anti-Scraping Vehicular Adjustments integrates camera technology with radar sensors/ultrasonic sensors to enhance the durability and functionality in vehicles at the ramp up and ramp down maneuvering conditions. This system is designed to automatically lift and suppress the height of the vehicle underbody in response to the potential or expected scraping at the inclined ramps scenarios, reducing the risk of damage from frictional impacts from ground. Car is equipped with AD sensors such as Radars, Multipurpose Cameras, Surround view cameras and ultrasonic sensors which can have a complete overview of the surrounding road conditions. During normal driving maneuvers, the camera and radar sensors continuously scan the area around the vehicle. They detect vehicle position and measure their maneuvering conditions. Also, the inertial measurement sensors in the car will give information about the dynamic parameters such as yaw, pitch and roll conditions of vehicle. Based on the detection points and algorithm threshold constraints the car height adjusts its position to avoid any damage to the underbody and the bumpers. This can be done using the algorithm of vehicular plane adjustment which gives input to vehicle actuators.

---

### 5. System and Method for Emergency Vehicle Localization, and Lane Change Assistance for a Vehicle 
**Application No:** 202511050516  

**Filed On:** May 26, 2025  

**Description:**  
Usually in urban or highway scenario, it is important to isolate the noise of emergency vehicle from the rest of the vehicle honking/external sounds. It becomes difficult for the external microphones in such scenario as well to detect the siren location. To solve this problem we have developed a probabilistic algorithm to detect the siren and localize the siren lanes in such scenarios.

A system/method for Sound-Based Rear Localization of Emergency Vehicles, comprises:
A sound source detection unit, combined with an ANN-based frequency processing unit, is used for detecting siren audio and predicting its sector and range information

The system provides an emergency vehicle sound-based localization, comprises:
- Utilizes a probabilistic algorithm to detect the siren and localize the siren lanes.
- Probabilities are assigned to lanes based on sound direction, refined with repeated impulses.
- Vehicles are localized to lanes, and their yaw is calculated to adjust probabilities.
- Linear convolution combines these probabilities to determine the emergency vehicle’s lane, guiding the ego vehicle’s actions.
- A histogram refines localization once the emergency vehicle is detected.

The system provides an Automatic Lane Change and path planning.
- The relative velocity of the emergency vehicle is used to estimate the Time to Approach (TTA).
- Automatic Lane Change Initiation Confidence is calculated using the TTA and the relative velocity of the emergency vehicle.
- If the initiation confidence exceeds a threshold, the system uses the lane with the maximum score and emergency vehicle lane localization to initiate an automatic lane change to the target lane, displaying this on the user interface.
- Camera and LiDAR-based Lane detection is used to determine the distance to the lane.

Usually in urban or highway scenario, it is important to isolate the noise of emergency vehicle from the rest of the vehicle honking/external sounds. It becomes difficult for the external microphones in such scenario as well to detect the siren location. To solve this problem we have developed a probabilistic algorithm to detect the siren and localize the siren lanes in such scenarios. A system/method for Sound-Based Rear Localization of Emergency Vehicles, comprises: A sound source detection unit, combined with an ANN-based frequency processing unit, is used for detecting siren audio and predicting its sector and range information The system provides an emergency vehicle sound-based localization, comprises: 
- Utilizes a probabilistic algorithm to detect the siren and localize the siren lanes.
- Probabilities are assigned to lanes based on sound direction, refined with repeated impulses. - Vehicles are localized to lanes, and their yaw is calculated to adjust probabilities. - Linear convolution combines these probabilities to determine the emergency vehicle’s lane, guiding the ego vehicle’s actions.
- A histogram refines localization once the emergency vehicle is detected. The system provides an Automatic Lane Change and path planning.
- The relative velocity of the emergency vehicle is used to estimate the Time to Approach (TTA).
- Automatic Lane Change Initiation Confidence is calculated using the TTA and the relative velocity of the emergency vehicle.
- If the initiation confidence exceeds a threshold, the system uses the lane with the maximum score and emergency vehicle lane localization to initiate an automatic lane change to the target lane, displaying this on the user interface.
- Camera and LiDAR-based Lane detection is used to determine the distance to the lane.

---

### 6. System and Method for Emergency Vehicle Detection and Ranging 
**Application No:** 202511060282  

**Filed On:** June 24, 2025  

**Description:**  
The present disclosure provides a system and a method for emergency vehicle detection and ranging. The system detects one or more objects in proximity to the vehicle. The system transmits one or more signals to the one or more objects and determines one or more time delays associated with the one or more signals received from the one or more objects. The system classifies, via a machine learning engine, the one or more objects into one or more static objects and one or more dynamic objects based on the determined one or more time delays and positioning of the one or more static objects and the one or more dynamic objects with respect to the vehicle. The system identifies one or more emergency vehicles from the one or more dynamic objects with minimal interference from the one or more static objects.

---

### 7. LLM Based Re-routing Based On Complex Sign Board Text Recognition
**Application No:** 202511094930  

**Filed On:** October 3, 2025  

**Description:**  
Developed an LLM-driven navigation system that interprets complex, unstructured road sign text in real time using a BERT-based language understanding model. The system was trained using parameter-efficient fine-tuning techniques on a compact, task-specific dataset, enabling low-latency inference and robust generalization. Integrated the text understanding module with live traffic constraints to dynamically re-route vehicles under evolving road, regulatory, and congestion conditions.

---

### 8. System and Method For Reconstructing Obstructed Traffic Signs Under Adverse Visibility Conditions
**Application No:** 202511126353

**Filed On:** December 13, 2025  

**Description:**  
Developed a GAN-based system to reconstruct traffic sign images obstructed by snow, sun glare, and dust, significantly enhancing the reliability of multiple ADAS functions.

---

## 📄 Publications

### SSTV Based IoT Data Acquisition and Analytics for Remote Regions  
**Published:** February 2023  
**Authors:**  
Anshuman Phadke, Arvind N, Anirudh Karnik, Dr. Arvind Kumar  

**Conference:** INDICON 2022  
**DOI:** [10.1109/INDICON56171.2022.10039956](https://doi.org/10.1109/INDICON56171.2022.10039956)

**Abstract:**  
This paper presents an SSTV-based IoT data acquisition framework for reliable communication and analytics in remote and infrastructure-limited regions, enabling low-bandwidth sensing and monitoring solutions.

---

## ⚠️ Disclaimer

Patent details are shared for informational and academic purposes only.  
All intellectual property rights remain with **Mercedes-Benz Group AG / Mercedes-Benz R&D India**, where applicable.

---

## 👤 Author

**Anshuman Phadke**  
Autopilot Developer | ADAS Engineer | Autonomous Systems | Vehicle Safety & Perception

