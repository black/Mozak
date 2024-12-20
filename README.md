# Mozak

An EEG Visualizer built with Node.js that connects to any headband using the Neurosky TGAM chip for EEG data recording. This application captures real-time brainwave data from the EEG device and visualizes it through interactive graphs and charts. Users can monitor their mental state, such as focus or relaxation, with live updates, providing insights into brain activity. The app is designed for easy integration with compatible headbands and can be customized for various neurofeedback applications.

### Features

- Visualize EEG Raw Signals: Display real-time raw EEG signals captured from the headband.
- EEG Bands Analysis: View data segmented into EEG frequency bands (Delta, Theta, Alpha, Beta, Gamma) for deeper insights into brain activity.
- Attention and Meditation Values: Monitor calculated metrics like attention and meditation levels for neurofeedback or mindfulness tracking.
- Local Data Storage: Save recorded EEG data to a local file for further analysis or record-keeping.

## Instructions

1. Install and Run ThinkGear Connector
   - Download and install the ThinkGear Connector provided by Neurosky.
   - Start the ThinkGear Connector to create a WebSocket server that streams EEG data from the headband.


1. Install the required packages
````
npm install
````  
3. Run the server -

````
node server.js
````

![alt](https://github.com/black/mozak/blob/master/screencapture-localhost-3000-1520233749921.png)
