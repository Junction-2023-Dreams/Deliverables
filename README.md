## Table of Contents
- [Introduction](#introduction)
  - [Functionalities](#functionalities)
    - [SmartWatch App Functionalities](#smartwatch-app-functionalities)
    - [Patient Doctor App Functionalities](#patient-doctor-app-functionalities)
      - [Patient Page](#patient-page)
      - [Doctor Page](#doctor-page)
- [Patient \& Doctor App Testing](#patient--doctor-app-testing)
  - [Credentials](#credentials)
      - [Patient](#patient)
      - [Doctor](#doctor)
- [SmartWatch App Testing](#smartwatch-app-testing)
  - [Android Installables](#android-installables)
    - [Provided Files:](#provided-files)
    - [.apk Installation](#apk-installation)
- [Important Information](#important-information)

# Introduction
Our ecosystem provides **3** apps:
1. Smart Watch Application
2. Patient Application
3. Doctor Application

## Functionalities
### SmartWatch App Functionalities
* Initial Default-Health-State-Measurement
* Heart-Rate-Measurement
* Achievements Page
  * Shows Health and Non-Medication-Successes
  * Shows gamified level experience
  * Shows history
* SOS Page
  * Sends SOS-Message to Emergency-Contacts
* Analytics-Page
  * Heart-Measurements
  * Drug intakes 
  * Substitution successes
* Button "*I feel Pain*"
  * Drug substitution methods via "*Relax*" button
    * Suggests different alternative methods that could work
    * Provides a **psychological health assessment** after every substitution to try to measure **effectiveness**
  * Drug intake button
    * Suggests effective alternative subtitution methods
    * On Pill-Intake: Measures heart rate in following time period to measure effects for users analytics
  * Passive Health Data Collection 
    * Private for personal analytics
    * Used for collecting data about
      * regular pains
      * effectiveness of drug substitutions

### Patient Doctor App Functionalities
#### Patient Page
* Differenciated Login
* Interactive User-Pain-Map
* Heart-Rate-History sharing with doctor
  * Share history with Doctor to request assistance (Optionally & Encrypted)
* Display medications (drugs), dosis and time to take in
* Health User-Pain-Map to actively edit and display pain points to doctors
* Add Medications
* Activities to substitute pain creators

#### Doctor Page
* Table with Patients with shared data
  * Sortable after addiction risk, names, etc.
  * Searchable
* Warn-O-Meter
  * Warns of addiction risk at patients
  * Sortable & Searchable
  * Banner with most important notifications
    * Notification for immediate attention (high priority)
    * Notification for later attention 


# Patient & Doctor App Testing
Please, test the **Patient** & **Doctor** **App** online.   
[Here](https://app.simonbrebeck.de/)  
Credentials are provided below.

## Credentials
#### Patient  
Email: patient@email.com   
Password: patient   
#### Doctor   
Email: doctor@email.com    
Password: doctor  

# SmartWatch App Testing
In this section the installables and the installation process for the SmartWatch App are described. 

## Android Installables
The installables are debug-builds and for testing purposes only.  
**They do not contain medical or any kind of advice!**

### Provided Files:
+ [watch-app.apk](./watch-app.apk)

### .apk Installation
1. Install Android Studio
2. Create an emulator for a watch 
3. Drag and drop the watch-app.apk file to the emulator
4. The app will be installed and can be used by opening it

# Important Information
This folder contains files related to the submission of our Junction Hackathon project.    

**They do not contain medical or any kind of advice!**  
We do **not** take any responsibility for the content of the files.  
The files are provided as-is and **without** any **warranty**.

The installables are debug-builds and for testing purposes only.  
**They do not contain medical or any kind of advice!**