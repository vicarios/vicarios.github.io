# Software Repositories

The Vicarios ecosystem consists of several interconnected repositories designed for high-performance robotics, real-time middleware, and immersive simulation.

---

## 🚀 Core Repositories

### [Vicarios Robots](https://github.com/vicarios/VicariosRobots)
**Hardware Control & Configuration**  
The central repository for robot-specific drivers and hardware abstraction layers. It provides the necessary interface logic to connect physical robotic platforms with high-level control software.

*   **Integration:** Works in tandem with the [Robot Importer](https://github.com/vicarios/RobotImporterUnreal) for digital twin synchronization.
*   **Support:** Open structured issues for hardware-specific bugs [here](https://github.com/vicarios/VicariosRobots/issues/new?template=request-form.yml).

### [EasyDDS](https://github.com/vicarios/EasyDDS)
**Middleware & Communication**  
A streamlined, lightweight C++ interface for Data Distribution Service (DDS) messaging. It abstracts the complexity of standard DDS, making it easier to implement low-latency communication in ROS 2 environments.

*   **Performance:** Optimized for real-time telemetry and command streaming.
*   **Support:** Open structured issues for middleware bugs [here](https://github.com/vicarios/EasyDDS/issues/new?template=request-form.yml).

### [Robot Importer (Unreal)](https://github.com/vicarios/RobotImporterUnreal)
**Simulation & Visualization**  
A specialized plugin for Unreal Engine 5 that facilitates the import and simulation of complex robotic models (URDF/MJCF). It is essential for projects involving immersive teleoperation and high-fidelity rendering.

*   **Features:** Supports foveated rendering and real-time unicasting.
*   **Support:** Open structured issues for simulation bugs [here](https://github.com/vicarios/RobotImporterUnreal/issues/new?template=request-form.yml).
