# Custom FPV Drone Build

This project documents my custom FPV (First-Person View) drone build — designed for high-speed flying, freestyle, and aerial cinematography. It includes the frame, flight controller setup, motors, ESCs, FPV system, and software configuration.

## About This Build

This drone was built from scratch to achieve:
- Fast and responsive flight for freestyle and racing
- Real-time video transmission with low latency
- Durability for hard landings and rough use
- Easy repair and modular upgrades

## Components

| Part                | Model / Specs                            |
|---------------------|-------------------------------------------|
| Frame               |                       |
| Motors              | [         |
| ESCs                | []                       |
| Flight Controller   | []     |
| FPV Camera          | []    |
| Video Transmitter   | []                |
| Receiver            | [e.g., Crossfire Nano / ELRS]             |
| Battery             | 4S or 6S LiPo [enter capacity]            |
| Props               | [Enter size, e.g., 5x3x3 tri-blade]       |
| Firmware            | Betaflight [enter version]                |
| Radio Transmitter   | [e.g., Radiomaster TX16S / Taranis QX7]   |
| Goggles             | [e.g., DJI Goggles / FatShark Dominator]  |

## Setup Guide

1. **Frame Assembly** – Install arms and center stack
2. **Soldering** – Connect ESCs to FC, motor wires, power distribution
3. **FPV System** – Mount camera and VTX; wire to FC
4. **Receiver Binding** – Set up your radio link (CRSF, ELRS, etc.)
5. **Betaflight Config** – Flash latest firmware, configure ports, modes, OSD
6. **Maiden Flight** – Calibrate sensors, test failsafe, and do LOS hover check

## Tuning and Performance

This drone is tuned for smooth flight, responsive throttle, and stable video. PID tuning and rates were dialed in using both Blackbox logging and test flights.

## Videos and Footage

Check out flight footage, build logs, and tuning tips on my YouTube channel:  
🎥 [FTR Garage](https://youtube.com/@ftrgarage)

## Notes

- All wiring is kept modular for quick repairs
- Flight controller supports GPS, barometer, and Blackbox logging
- Designed to be beginner-repairable but high-performance

## Future Upgrades

- GPS rescue + telemetry
- Onboard HD recording (e.g., Caddx Walnut or GoPro)
- Custom 3D-printed parts for improved protection

## License

Feel free to fork, build, or remix this project for personal use. Commercial use requires permission.  
Licensed under the [MIT License](LICENSE).

---

## Contact

**Aleksander R. Rodriguez Kozlowski**  
Email: [alekrodriguezresume@gmail.com](mailto:alekrodriguezresume@gmail.com)  
Instagram: [@ftrgarage](https://instagram.com/ftrgarage)  
GitHub: [alekrodriguezresume](https://github.com/alekrodriguezresume)
