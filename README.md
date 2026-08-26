# Hi there 👋

<h3 align="left">Software Developer | Embedded & IoT Student</h3>
<h3 align="left">About Me</h3>

I’m 30 years old and based in Stockholm. I’m focused on problem solving, curious about technology and committed to continuous learning.  

I’m currently studying **Software Developer - Embedded Systems and IoT**, where I build solid foundations in **Embedded C, C++, systemintegration and architecture with Java and .NET**.  
I enjoy exploring how hardware and software interact and experimenting with my own projects in order to broaden my knowledge in the vast world of IT.


Some of my skills and tools i learn include:

- Embedded systems (C, C++)
- Backend development (Java, ASP.NET C#, C++)
- Database management (MySQL)
- Hands-on hardware prototyping

You can reach me at 
- **calle.engstrom@yh_nackademin.se**
- **calle.eng@live.se**
---
### My Projects

- **[Climate Control System](https://github.com/calleengstrom/Temperature_iot_demo)**
- A simple yet complete IoT system, composed of:
    
    
    - **Sensor** – ESP32 DHT11 Temp / Hum Sensor <br>
        Collects temperature and humidity data. Uses ESP-IDF’s Wi-Fi and HTTP library to transfer JSON data to the backend.
    
    - **Backend** – Java Spring (Gradle & Maven) – Hibernate – MySQL  <br>
        Java backend for receiving POST API requests from the ESP32 sensor and storing temperature records in a MySQL database. It also retrieves data from the MySQL database for various HTTP API calls.
        Responsible for the rule set / rule engine with three different states/rules ("Normal", "High", "Low") regarding the temperature. Publishes the corresponding message to the MQTT broker on a set topic.
    
    - **MQTT** – Mosquitto MQTT Broker   <br>
        Configured and set up a Mosquitto MQTT broker on my local LAN.
        
    - **Actuator** – ESP32 (Simulates climate control center) with RGB light  <br>
        The ESP32 uses ESP-IDF’s Wi-Fi and MQTT library to subscribe to the set MQTT topic and uses an event-driven state machine / protocol corresponding to the message ("Normal", "High", "Low").
        Turns on the RGB light that represents "Cooling" / "Heating" / "Normal".


- **[Small_Projects](https://github.com/calleengstrom/Small_Projects)** - Here I post some of my own small projects that I work on at home in my free time, mainly to gain a better understanding and practical experience in Embedded Systems and Networking.

---
### School Projects

These are some of the projects I’m currently working on or have completed as part of my studies:

- **Keypad Access System** – C++/C, Arduino, ESP32, TCP/IP,A three-part access control system:

    Arduino is built as a state machine with the states IDLE / Scanning, Await PIN, Access OK/Denied and timeout.
  <br>
    It uses an RFID scanner, a numpad for PIN entry, an RGB LED for status indication in different states, a servo motor and a buzzer for access simulation.
  <br>
    The Arduino holds the protocol for the payload and transfers the payload through UART to the ESP32.
  <br>
    The ESP32 only bridges the Arduino (via UART) to the backend over Wi-Fi/TCP.
  <br>
    The backend is a C++ TCP server that uses the same protocol for the payload, stores the valid RFID keys and matching PINs, and responds accordingly to events from the Arduino.
  
   
     * **[Arduino](https://github.com/calleengstrom/part3)**
     * **[C++ TCP Server](https://github.com/calleengstrom/part3_server)** 
     * **[ESP32 Wi-Fi/UART](https://github.com/calleengstrom/esp_wifi_uart)**

*The assignment provided a ready-made backend server, but I chose to develop my own C++ TCP server to gain a deeper understanding of TCP communication, client-server architecture and backend development.*

**Smaller yet valuable school assignment**

- **[Java Network-programming](https://github.com/calleengstrom/real_nvp)** - Java Network-programming course, contains school assignments with TCP / UDP network orientation.
- **[User Auth MD5](https://github.com/calleengstrom/User_Auth_MD5)** – C++, school assignment  
- **[Password cracker](https://github.com/calleengstrom/pwcracker)** – C++, school assignment   
- **[C_Card_System](https://github.com/calleengstrom/C_Card_System)** – C, therminal based "card-scan system", school project  
- **[Memory_game](https://github.com/calleengstrom/Memory_game)** – C/C++,AVR,Arduino, hackathon challenge
- **[Cashregister](https://github.com/calleengstrom/Cashregister)** – Java,  school assignment




---

### Other Interests

Outside of school and coding, I like to stay active and explore the world. Some of my personal interests include:

- Traveling and discovering new cultures  
- Fitness, outdoor activities, like fishing hiking, and most of all skiing  
- Spending time in nature and enjoying small adventures  


<!--
**calleengstrom/calleengstrom** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
