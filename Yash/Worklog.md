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
Consultation with dentist. We choose to use the material PMMA beacuse PMMA, or polymethyl methacrylate, is a type of plastic that is commonly used in dental prosthetics and orthodontic appliances. It is also used in some cases to encase electrical components that are placed in the mouth, such as sensors or electrodes.

One advantage of using PMMA for this purpose is its biocompatibility. PMMA is a biologically inert material, which means that it does not react with the tissues in the mouth and does not cause any harmful effects. This makes it a safe material to use for dental and medical applications.

Another advantage of using PMMA is its transparency. PMMA is a clear and transparent material, which allows for easy visualization of the underlying components. This can be particularly useful when working with sensors or other devices that need to be positioned accurately.

PMMA is also easy to work with and can be molded into a variety of shapes and sizes. This makes it a versatile material that can be used to create custom enclosures for specific devices or components.

Finally, PMMA is a relatively inexpensive material, which makes it a cost-effective option for dental and medical applications.
