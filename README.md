The **Gesture Controlled Virtual Mouse** project described here is an innovative way of enhancing human-computer interaction, enabling users to control various aspects of the computer through hand gestures and voice commands, eliminating the need for direct contact with the computer.

### **Key Features:**
1. **Gesture Recognition:**
   - **Neutral Gesture**: Stops all action.
   - **Move Cursor**: Move the cursor by moving your hand.
   - **Left Click**: Perform a left mouse click.
   - **Right Click**: Perform a right mouse click.
   - **Double Click**: Perform a double-click action.
   - **Scrolling**: Scroll through pages or documents using hand gestures.
   - **Drag and Drop**: Drag items and drop them using gestures.
   - **Multiple Item Selection**: Select multiple items using hand gestures.
   - **Volume Control**: Adjust the volume through hand movements.
   - **Brightness Control**: Adjust the screen brightness using gestures.

2. **Voice Assistant (Proton):**
   - **Launch/Stop Gesture Recognition**: Voice commands to start or stop gesture control.
   - **Google Search**: Use voice commands to search on Google.
   - **Find Location on Google Maps**: Use voice to get directions or locations.
   - **File Navigation**: Navigate through files on your system with voice commands.
   - **Current Date and Time**: Get the current date and time via voice.
   - **Copy and Paste**: Use voice to copy and paste content.
   - **Sleep/Wake Up**: Put the computer to sleep or wake it up via voice commands.
   - **Exit**: Exit or shutdown the application with a voice command.

### **Technology Used:**
- **Machine Learning and Computer Vision**: Utilizes state-of-the-art algorithms to recognize hand gestures and voice commands.
- **MediaPipe Hand Detection**: Provides hand gesture recognition without requiring additional hardware.
- **CNN (Convolutional Neural Networks)**: Used for recognizing hand gestures and enabling interaction with the system.
- **pybind11**: A lightweight header-only library that binds Python and C++ code, used for integrating the models.
- **Windows Platform**: Currently, the system works only on Windows.

### **Working Mechanism:**
1. **Gesture Recognition Module:**
   - **MediaPipe Hand Detection**: Detects hand gestures and recognizes different static and dynamic hand movements.
   - **Glove-Based Gesture Recognition**: In addition to hand gestures, the system can recognize gestures made with gloves of a uniform color, providing a versatile approach to interaction.

2. **Voice Assistant (Proton):**
   - The voice assistant listens for commands, processes them, and executes actions like launching applications, performing searches, navigating files, and even controlling system functions like sleep or wake-up.

### **Target Platform:**
- The project works specifically on **Windows**, utilizing tools compatible with the Windows operating system.


