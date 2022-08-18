<img alt="GoStack" src="https://github.com/RaffaelSchemmer/Humidity_Sensor/blob/main/humidity.gif" />

<div align="center">
  <h2>
    System for Measuring and Monitoring Soil Moisture, Temperature and Atmospheric Moisture Parameters
  </h2>
  <h4>
    :star: Star us on GitHub — it helps!
  </h4>
   

</div>

## 🧿 About the Application Purpose
<div align="justify">
In this GitHub repository, you will find a <b>complete application</b> (full-stack and multiple technology) that allow measure and monitoring soil moisture, temperature and moisture atmospheric, using Arduino sensors. This application was developed :bulb:, to the integrative project of the student Gustavo Chimenes Dias, that happened during 2020 and 2021 📅 in Camboriú, SC in Brazil. 
</div>

## :rocket: About the Application Architecture and Technologies
<div align="justify">
The architecture of application was developed to running in three different types of machines and applications. 1️⃣ First machine, are responsible to the camp sensoring that measure the soil and the atmosphere. In this machine, we running a C/Arduino application. This application sensoring Yl-69 and DHT-11 and send and information using RF 433MHz. 2️⃣ In the other hand (second machine), we have the base sensoring that receive the data of camp and send data to the server. In this machine, we running a C/Arduino application. This application send this data using a serial/usb cable to the server. In the server, we running a python code that read serial port and write the information in a MySQL database. The last application 3️⃣ of architecture, is a web system write using html/css and javascript, running based in express web server. This application allow that all information available in database, can be used by user. This application have a complete CRUD that allow the creation of users and syncronization the data of boards/sensor to individual farms.
</div>

## ✅ Requirements to Installing the Application
<div align="justify">
In Arduino/C, user need to configure the camp board to syncronize to base board. Than, the python server code need to be configured to receive data of base board. The files of arduino boards and the server are availabled in the folder Sensores. 
 In the server side you need to run a http service with NODEJS and a MySQL Server.
</div>

## 💻 Requirements to Running the Application

- Arduino Camp and Base
- Server with Linux like Ubuntu Server 20.04 LTS
- Server with IPv4 static in Internet
- Server that running Http Web Services (NodeJS/Express)
- Server that running Python Services
- Server running Mysql Services
- Computer with Windows Xp or Later

## ❤️ Community and Contributions to Future Work
<div align="justify">
Our major dreaming of this project, is that the community uses this magic tool to monitoring soil and atmosferic parameters, to to plant and harvest better greens and vegetables, like we achieved when we developing and apply our study case. But, we are open to new ideas to grow this project to the next level. With future work, that you can implement, we suggest a native mobile version of this application. This will allow that every people of farm team, can manage the system using your cellphone.
</div>

## 📫 Have a question? Want to chat? Ran into a problem?
<div align="justify">
We are really open and interest in your opinion about this tool and his ideia. Feel free to contact us with e-mail: raffael.schemmer@gmail.com.
</div>

## 🤝 Found a bug? Missing a specific feature?
<div align="justify">
Feel free to <b>file a new issue</b> with a respective title and description on this repository. If you already found a solution to your problem, <b>we would love to review your pull request</b>!
</div>

## 📘 License

This project uses MIT license. See the file [LICENSE](LICENSE) to more details.

---

Made with 💜 by Raffael Schemmer :wave: [See my Online CV!](https://www.raffael.dev)
