# IoShroom

## 🔗 Live Page (https://ahdessa-perez.github.io/IoShroom/)

### IoShroom Mobile Application

#### Project Title: IoShroom Mobile Application

#### **Description:**  
The IoShroom mobile application is a user-friendly, innovative system designed to monitor and manage mushroom farming processes efficiently. This application integrates seamlessly with IoShroom's hardware components, enabling users to control and automate colonization and harvesting activities through an intuitive interface.

The app leverages Firebase Realtime Database for real-time updates, ensuring that all activities, including timer-based processes and environmental monitoring, are synchronized. IoShroom combines technology with sustainable agriculture, providing mushroom farmers with a reliable and scalable solution to optimize their production.

#### **Key Features:**  
1. **Process Automation:**  
   - Colonization and harvesting processes are automated with predefined durations (14 days for colonization, 7 days for harvesting).  
   - Timers continue to run even when the app is closed.

2. **Real-Time Monitoring:**  
   - Displays timer countdowns in the format `00 days:00 hours:00 minutes:00 seconds`.  
   - Real-time status of colonization and harvesting switches.  

3. **Hardware Integration:**  
   - Connected to IoShroom hardware components, including SHT20 sensors, humidifying boxes, and incubation cabinets.  
   - Supports multiple system layers (Layer 1A and Layer 1B) for scalability.  

4. **Fail-Safe Design:**  
   - Colonization and harvesting switches are interdependent to prevent simultaneous activation.  

5. **Firebase Database Structure:**  
   ```plaintext
   user_uid:
     layer1A:
       col1A ("on" or "off")
       har1A ("on" or "off")
       col1A_timer (14 days)
       har1A_timer (7 days)
   ```

#### **Prototyping and Real-Life Application:**  
The IoShroom mobile application was developed following a rapid prototyping approach, ensuring the system was aligned with real-world needs. The process included:  
1. **UI/UX Design:**  
   - The interface was designed using **Kodular**, prioritizing simplicity and ease of use for farmers with limited technical experience.  

2. **Hardware Integration Testing:**  
   - Conducted extensive testing with the physical IoShroom prototype, which included components like Raspberry Pi, SHT20 sensors, and a humidifying system.  
   - Validated real-time communication between the mobile app and hardware via Firebase.

3. **Functional Prototyping:**  
   - Developed a complete working prototype integrating timers, switches, and environmental monitoring systems.  
   - Demonstrated reliability in automating colonization and harvesting processes during live testing in an actual mushroom farming environment.

#### **Achievements:**  
The IoShroom project, including this mobile application, was recognized in the **IPOPHIL SRT competition**, securing 2nd place due to its innovative approach and practical implementation. The complete prototype showcased the potential of IoShroom as a modern solution to agricultural challenges.

