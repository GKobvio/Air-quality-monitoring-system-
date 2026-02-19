# Air-quality-monitoring-system-
The Air Pollution Monitoring System is an embedded hardware project designed to detect and monitor harmful gases in the surrounding environment. The system uses an MQ-2 Gas Sensor to sense the presence of combustible and toxic gases such as LPG, methane, carbon monoxide, and smoke. The MQ-2 sensor converts gas concentration into an analog voltage signal, which is then read and processed by an Arduino Uno microcontroller.

The Arduino Uno acts as the central processing unit of the system. It continuously reads analog data from the sensor, analyzes the gas concentration level, and compares it with a predefined safety threshold. The real-time gas value is displayed on a 16×2 LCD module connected through an I2C interface, ensuring clear and easy monitoring. This allows users to observe environmental conditions instantly.

When the detected gas concentration exceeds the safe limit, the system immediately activates a visual and audible alert mechanism. An LED indicator turns on, and a buzzer generates a warning sound to notify users of potential danger. This dual-alert system enhances safety by providing both visual and sound-based warnings.

The project is cost-effective, compact, and easy to implement, making it suitable for homes, laboratories, industries, and public spaces where continuous air quality monitoring is essential. It helps in the early detection of gas leaks and hazardous conditions, thereby reducing health risks and preventing accidents.

Overall, this system demonstrates the practical application of embedded systems and sensor technology in environmental monitoring, offering a reliable and efficient solution for real-time air pollution detection and safety management.
