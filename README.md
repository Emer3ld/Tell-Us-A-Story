# Tell Us a Story

## 📚 About the project:
This project will use the capabilities of the Arduino Portenta H7 to create an interactive device that recognises (specific) artefacts using image recognition technology and responds by playing an audio story about the object. Using the Portenta Vision ShieldModule for real-time image capture and TensorFlow Lite for efficient image processing, the system can classify images into predefined categories. If successful in recognition, the system plays back a short audio story, corresponding to the identified object, creating a pocket size immersive and educational experience.<br>

My inspiration comes from a popularbroadcasting programmes such as BBC 4's 'In Our Time', books- Horrible Histories and the british museums app, where a factual account is given on 250 artefacts. I thought, how could I make looking at artefacts or a trip to the museum more engaging.
![BL](https://github.com/Emer3ld/Tell-Us-A-Story/assets/114082509/512cb0bc-6ec6-49a8-a291-e742dec46bda)
![hh](https://github.com/Emer3ld/Tell-Us-A-Story/assets/114082509/12f2e522-20ae-4e3b-815e-ba27214217dc) 
![bbc4](https://github.com/Emer3ld/Tell-Us-A-Story/assets/114082509/0b230912-9822-4211-850a-be80dc6a9aea)


## 📖 Features

Artefact Recognition: Utilizes advanced image recognition to identify museum artefacts.
Narrative Playback: Automatically plays a story related to the recognized artefact, providing historical and cultural context.
AIoT Integration: Combines AI with IoT (AIoT) for efficient processing and a seamless user experience.
Hardware Requirements

## 📖  Portenta H7
Vision Shield for Arduino Portenta
Optional: Additional components for user interaction (e.g., speakers or a display)
Software Requirements

Edge Impulse Studio account for machine learning model training.
Arduino IDE for programming the Portenta H7.
Setup and Installation

## 📖 Arduino Environment:
Install the Arduino IDE from Arduino's official website.
Set up your Arduino Portenta H7 with the Vision Shield according to the manufacturer's guidelines.
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/tell-us-a-story.git
cd tell-us-a-story

## 📖 Edge Impulse:
Create an account on Edge Impulse.
Follow the instructions on Edge Impulse to create and train your machine learning model for artefact recognition.

## 📖 Deploying the Model:
Download the trained model from Edge Impulse and load it onto your Arduino Portenta H7.

## 📚 Running the Application:
Upload the Arduino sketch provided in the repository to the Portenta H7.
Power up the device and test it by showing it images of artefacts to see it recognise and narrate their stories.
