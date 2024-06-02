# solar-panel-system
Solar panel that orients towards the sun.

In this project, we aim to design a control system that automatically adjusts the position of a solar panel according to the sun's position. The system charges a battery with the energy harvested from sunlight, thereby conserving electricity. This creates an efficient battery management system.

A simple web interface for battery management control is implemented using the STM32. The ESP32 module is used for this purpose. Battery percentages can be viewed via the IP address displayed through the serial port, using the specified username and WiFi password.


<h3> Used materials </h3>
<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/kullan%C4%B1lan_malzemeler.png" alt="Kullanılan malzemeler" width="600" height="400">

<h3> Circuit Diagram Drawing </h3>
<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/devre_semas%C4%B1.png" alt="devre şeması çizimi" width="900" height="500">

<h3> Result </h3>
<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/devre2.png">

In this system, two LDR sensors on the solar panel measure light levels. The servo motor turns the panel towards the side with higher light intensity. The solar panel harnesses energy from sunlight and charges a battery through a BMS circuit. The ESP32 module measures the remaining battery energy and displays it to the user via a specified IP address.


<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/server.png" alt="server">

## Files

- `stm32_solar_panel_code.ino`: STM32 code for controlling the solar panel.
- `esp_code.ino`: Code for the web interface on ESP32.

  
## Usage

To run the project:
1. First, upload and run the `stm32_solar_panel_code.ino` file to your STM32 board to control the solar panel.
2. Then, upload and run the `esp_code.ino` file to your ESP32 board to set up the web interface.
3. While on the same network, enter the assigned IP address into a web browser to access the web interface and monitor the system.


## Contributing

If you would like to contribute, please submit a pull request. All contributions are welcome!

