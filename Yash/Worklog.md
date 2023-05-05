# Yash Worklog

## February

### 2/10
Spoke with Professor Mironenko about solutions for AM radio reception. Did research on how to implement AM radio reciever.

Issues with the AM recieiver include the demodulator which will take up a significant amount of poweer as well as the large antenna required. Further research is required. Look into loop antennas possibly. 

## 2/12

Brainstormed various communication protocols from bluetooth low energy to fm radio. FM radio obviously seems unviable, but we want long range connectivity how can this be done if AM radio takes up such a large amount of power. Only solution is having an intermediatry device such as a cell phone which can connect to propietry long range communication network such as LTE.

## 2/15

Both WiFi and RF (radio frequency) are wireless communication protocols, but there are some key differences between them.

WiFi is a wireless networking technology that uses radio waves to provide high-speed wireless internet and network connections. WiFi operates on specific frequency bands (usually 2.4GHz or 5GHz) and can provide data rates ranging from a few megabits per second (Mbps) to several gigabits per second (Gbps). WiFi has several advantages over RF, including:

Higher data rates: WiFi can provide much higher data rates than RF, which is particularly important for applications that require high-speed data transmission, such as video streaming, online gaming, and file transfers.

Greater range: WiFi has a longer range than RF, which means that it can cover larger areas and provide connectivity to devices that are further away from the access point.

More secure: WiFi has built-in security features that help to protect against unauthorized access and eavesdropping, which is particularly important for applications that involve sensitive data or require high levels of security.

Greater reliability: WiFi uses error-correcting techniques to ensure that data is transmitted accurately, which can help to prevent data loss or corruption.

More flexibility: WiFi can support a wide range of devices, including smartphones, tablets, laptops, and IoT devices, and can be used to create large-scale networks that can support a wide range of applications and services.

## 2/20

After doing further research we settled on using esp 32 mainly because it is a  popular choice for edge devices that require wireless connectivity. Some advantages of using the ESP32 for WiFi communication in edge devices include:

Low cost: The ESP32 is relatively inexpensive compared to other microcontrollers with built-in WiFi, making it an affordable option for edge devices.

Low power consumption: The ESP32 is designed to operate at low power levels, making it suitable for battery-powered edge devices.

Dual-core processor: The ESP32 has a dual-core processor, which allows it to perform multiple tasks simultaneously, such as running a WiFi connection while also processing sensor data.

Built-in security features: The ESP32 includes a range of security features, including support for encryption, secure boot, and secure flash, which helps to protect against unauthorized access and data breaches.

Easy to program: The ESP32 can be programmed using the Arduino IDE or the ESP-IDF (ESP32 IoT Development Framework), making it easy to develop and deploy applications.
Aurdino IDE makes it the perfect choice for us due to ease of progarmming.

## 2/25
Consultation with dentist. We decided to settle on one material that has proven to be quite useful in electrical applications in the mouth which is PMMA, which stands for polymethyl methacrylate. PMMA is a type of plastic that has several advantages when it comes to dental and medical applications.

Firstly, PMMA is considered safe to use because it doesn't react with the tissues in the mouth or cause any negative effects. This means it can be used without posing any risk to the patient's health. Additionally, PMMA is transparent, which allows for easy visualization of the underlying tissues and components. This is especially helpful when working in the oral cavity, where visibility can be limited.

Another advantage of PMMA is that it is easy to work with. It can be shaped and molded into a variety of sizes and shapes, making it highly versatile for different dental and medical applications. This means it can be used to encase different types of electrical components, such as sensors, transducers, or even small motors.
Finally, PMMA is relatively inexpensive compared to other materials used for similar purposes, which makes it a cost-effective solution for dental and medical practitioners.
## 3/11

I recently underwent a dental impression procedure to obtain a mold of my upper palate. The dentist began by providing me with an impression tray containing a viscous, water-based substance called alginate. Alginate is a hydrocolloid material that is commonly used to create dental impressions due to its ability to quickly form a stable mold.

The alginate was inserted into the impression tray, and I was instructed to place it into my mouth, making sure to bite down firmly on it. The alginate material flowed into the contours of my teeth and gums, forming a negative impression of my dental arches. The material was left to set for a few minutes until it had solidified, and the dentist carefully removed the tray from my mouth.

The negative impression was then used to create a positive plaster cast of my upper palate. The cast was filled with dental stone, which hardened and formed an exact replica of my dental arches. This replica was then used to create a custom dental appliance or restoration, tailored specifically to my oral anatomy.
This mold is then to be used to create a custom fit for the BCDC for each individauls mouth, all in all good progress.

