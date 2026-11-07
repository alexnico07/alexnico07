# Hi, I'm Alex

I'm a Mechatronics Engineering student at the **University of Cape Town** (BSc Eng, Mechatronics, Robotics and Automation, 2026 to 2029), based in Cape Town, South Africa.

I like building things where software meets hardware: robots, electronics, home servers and drones. I'm especially interested in where AI meets physical and engineering systems, and I learn best by building something, breaking it, and working out why.

---

## What I'm working on right now

- **A LEGO EV3 robot arm** with homing, IR remote control and a simulator
- **Learning ROS 2** (Jazzy, running in WSL), working through the Articulated Robotics tutorials
- **Sensor instrumentation for an electric tuk-tuk** as part of vacation work (ESP32-S3 nodes, CAN bus, Raspberry Pi hub)
- **Running AI models locally** with Ollama and Docker on my own hardware

---

## Repositories

| Repo | What it is |
| --- | --- |
| [LEGO-Mindstorms-EV3](https://github.com/alexnico07/LEGO-Mindstorms-EV3) | Python control code and a simulator for a 3-joint EV3 robot arm (base, shoulder, elbow). Runs on `pybricks-micropython` over EV3DEV. Each joint homes itself against a physical limit stop, then the arm can be jogged with the EV3 infrared remote. A touch sensor triggers the homing sequence. The gripper is waiting on one more motor. |
| [ros-learning](https://github.com/alexnico07/ros-learning) | My ROS 2 learning workspace. Packages and launch files as I follow along with the Articulated Robotics series on ROS 2 Jazzy. |
| [urdf_example](https://github.com/alexnico07/urdf_example) | A fork of [joshnewans/urdf_example](https://github.com/joshnewans/urdf_example). On the `jazzy-gz` branch I ported the robot from Gazebo Classic to the newer Gazebo (Harmonic) on ROS 2 Jazzy, with joint position controllers and an RGB camera. The changes are written up in `PORT_NOTES.md`, and launch arguments such as `use_sim_time`, `world` and `robot_name` have been added. Full credit to Josh Newans for the original robot. |

---

## Other things I've built

Not all of these are on GitHub yet.

- **Water-level alarm** (first-year EEE project): a purely analogue, loadshedding-aware alarm with conductive water probes, an LDR, a CD4049 inverter stage, 555 timers and diode AND gates. Designed and simulated in LTspice before building, with about R20 spent on extra parts.
- **Raspberry Pi 3 home server** running OpenMediaVault, Plex and Pi-hole, with Tailscale for remote access.

---

## Skills and tools

**Languages:** Python, Java, Delphi (Object Pascal)

**Robotics and embedded:** ROS 2, URDF, Gazebo, RViz2, pybricks / MicroPython, ESP32, Arduino IDE, Raspberry Pi, CAN bus

**Electronics:** LTspice, analogue circuit design, sensor interfacing, oscilloscope work

**Everyday tools:** Git and GitHub, WSL, VS Code, Docker, Onshape (CAD), 3D printing, MATLAB

---

## Outside of engineering

I play guitar, and I'm getting into FPV and RC drones.

---

## Get in touch

<!-- Add your LinkedIn URL below -->
- LinkedIn: [Alex Nicolaides](https://www.linkedin.com/in/alex-nicolaides)
