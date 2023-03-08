# Stress
The pocket arcade fight pad is a compact and portable gaming controller that is designed for fighting game enthusiasts. It is powered by the GP2040 software from Open Stick Community, which provides seamless compatibility with various gaming platforms and ensures smooth and responsive gameplay.

One of the key features of the pocket arcade fight pad is its use of choc switches, which are known for their fast actuation. These switches provide an excellent balance of speed and precision, making them ideal for fighting games that require quick reflexes and precise inputs.

The controller is also equipped with a Waveshare rp2040-zero controller, which is a powerful and efficient microcontroller that offers excellent performance and energy efficiency. This allows the pocket arcade fight pad to provide hours of gameplay on a single charge, making it perfect for gaming on the go.

Despite its small size, the pocket arcade fight pad packs a lot of functionality, including a D-pad, six face buttons, and two shoulder buttons. This allows players to execute complex combos and special moves with ease, and provides a satisfying and immersive gaming experience.

Overall, the pocket arcade fight pad is a high-quality and versatile gaming controller that is perfect for fighting game fans who are always on the go. With its advanced software and high-performance hardware, it offers a level of responsiveness and precision that is unmatched by other portable gaming controllers.

![This is an image](https://github.com/GroooveBob/Stress/blob/main/pics/IMG_20230307_140611.jpg)

# BOM
1 x waveshare rp2040-zero
6 x 6x6mm Panel PCB Momentary Tactile Takt Mini Push Button Switch DIP 4pin 
12 x Choc Switches (i would recomend ligt as pissible)
12 x Choc Keycaps
12 x HS Sockets (optional)

# Setup
To get started with your Waveshare RP2040, download the pre-built firmware from this [LINK](https://github.com/OpenStickCommunity/GP2040-CE/releases)Once downloaded, flash the MCU.

The GP2040 features a web-based configuration application that can be accessed by holding down K1 when plugging your controller into a PC. To begin configuration, simply visit http://192.168.7.1. Under the Data Backup and Restoration section, upload the StressConfig.gp2040 file.

After uploading, you can access the web configuration by clicking the Start button. Your Stress Pad should now be ready to use.
