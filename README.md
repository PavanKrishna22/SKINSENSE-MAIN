
#SkinSense 

is an Android-based mobile application designed to detect and provide preliminary insights into common skin diseases using **Machine Learning (ML)** and **Image Recognition**.  
It leverages **MobileNetV2** trained on dermatology datasets and deployed with **TensorFlow Lite**, ensuring real-time, offline predictions even on mid-range smartphones.

---
OUTPUT:

Register Page	

<img width="568" height="1263" alt="image" src="https://github.com/user-attachments/assets/f65c5e9d-5871-4983-add9-5964c50a4277" />


Login Page

<img width="478" height="1063" alt="image" src="https://github.com/user-attachments/assets/235ba756-c53e-4470-9425-a95bf2800dc2" />
	 

Home Page 	 				

<img width="584" height="1299" alt="image" src="https://github.com/user-attachments/assets/fff86f74-1622-4244-8557-8125db0ac5aa" />


Camara Fragment

<img width="547" height="1216" alt="image" src="https://github.com/user-attachments/assets/46134ed4-3333-45c5-903d-8f22e4107c35" />


Storage of records

<img width="484" height="1076" alt="image" src="https://github.com/user-attachments/assets/8e593416-5008-4b93-9c88-aaed6cec4864" />
<img width="446" height="1060" alt="image" src="https://github.com/user-attachments/assets/ad9b4402-b55c-44ac-b411-d70eb42a8ba0" />


Medication page

<img width="548" height="1205" alt="image" src="https://github.com/user-attachments/assets/cc5ea22e-f6c4-4754-9a9f-f6c9b353b0eb" />


Profile page

<img width="529" height="1176" alt="image" src="https://github.com/user-attachments/assets/e7c93112-829c-4b77-b762-f05ba48cc3fb" />


---


## 📌 Features
- 📷 **Skin Disease Detection** – Upload/capture an image and get predictions with confidence scores.  
- 💊 **Basic Medication Suggestions** – Provides non-prescription recommendations for common conditions.  
- 🗺 **Find Dermatologists Nearby** – Integrated with Google Maps API to locate nearby specialists.  
- 📂 **History Tracking** – Saves user’s scan history with Firebase Realtime Database.  
- 🔒 **User Privacy** – Data is stored locally unless user opts for history tracking.  
- 🌐 **Offline Support** – AI model works without internet access.  
- 🌍 **Accessibility** – Multi-language support, clean UI, and future-ready voice assistance.  

---
---
DEVELOPMENT:

activity_home.xml
 <img width="940" height="616" alt="image" src="https://github.com/user-attachments/assets/b4b36ad4-ca6b-4bcb-b43b-2959abd3a539" />

activity_login.xml
 <img width="940" height="620" alt="image" src="https://github.com/user-attachments/assets/14c51987-7813-4657-b481-bb3bb937bce8" />

activity_register.xml
 <img width="940" height="620" alt="image" src="https://github.com/user-attachments/assets/eb7b61a9-209c-4ec4-b53b-ce8e145ae62b" />

fragment_camera.xml
 <img width="940" height="623" alt="image" src="https://github.com/user-attachments/assets/f4f2bced-dff4-4cec-b1aa-5fe5112bdbac" />


fragment_home.xml
 <img width="940" height="622" alt="image" src="https://github.com/user-attachments/assets/8c48e7e8-9c20-44cc-8e84-221c08147e3c" />

Fragment_history.xml
 <img width="940" height="621" alt="image" src="https://github.com/user-attachments/assets/f578cc46-1dc4-4c14-950a-6949dadfeca7" />

fragment_medic.xml (medicines scrollview)
 <img width="940" height="622" alt="image" src="https://github.com/user-attachments/assets/96438744-65bd-46fb-9c8b-316c517abe08" />

fragment_profile.xml
 <img width="940" height="623" alt="image" src="https://github.com/user-attachments/assets/8967dcf4-8ba7-43fd-b5a3-d3a3660f6b10" />

<img width="786" height="404" alt="image" src="https://github.com/user-attachments/assets/e5b902bf-a7cc-4f36-9ee7-aff15028a4f7" />
---

## 🛠 Tech Stack
- **Android Studio (Java/Kotlin, XML)**  
- **Firebase Authentication & Realtime Database**  
- **TensorFlow Lite (MobileNetV2 CNN model)**  
- **Google Maps API**  

---

## 📂 Project Structure
- `CameraFragment.java` → Captures and classifies skin images  
- `MedicFragment.java` → Displays medication recommendations  
- `MapsFragment.java` → Dermatologist locator  
- `HistoryFragment.java` → Shows scan history  
- `LoginActivity.java` / `RegisterActivity.java` → Firebase Auth integration  
- `HomeActivity.java` / `HomeFragment.java` → Main app navigation  
- `profileFragment.java` / `GetDetailsActivity.java` → User profile management  

---

## 🚀 Getting Started
### Prerequisites
- Android Studio (latest version)
- Android device/emulator (API 21+)
- Google Maps API key

