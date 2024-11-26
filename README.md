# Autonomous Parking Algorithm with ROS2 and Gazebo  

This repository showcases an **autonomous parking algorithm** developed using **ROS2** and **Gazebo**. The project simulates real-world scenarios where a vehicle detects its surroundings and accurately parks in a designated area. It integrates essential components of autonomous systems, such as control, perception, and motion planning.  

---

## 🚗 Features  

- **Perception**:  
  - Detects parking spaces and lane markings using **YOLOv8** and **Hough Transform**.  
- **Motion Control**:  
  - Implements a **PID control algorithm** to ensure precise parking between the lines.  
- **Simulation Environment**:  
  - Tested in a realistic **Gazebo simulation** to validate autonomous navigation and control.  
- **Modular Design**:  
  - Designed with modular ROS2 nodes for easy integration with different sensors and hardware setups.  

---

## 🛠️ Technologies  

- **ROS2 Humble**: Middleware for communication between nodes.  
- **Gazebo**: 3D simulation environment for testing.  
- **YOLOv8**: Object detection for identifying parking signs.  
- **Python/C++**: Used for algorithm implementation and ROS2 node development.  

---

## 🚀 Getting Started  

### Prerequisites  
Ensure you have the following installed:  
- **ROS2 Humble**  
- **Gazebo**  
- **Python 3.8+**  

### Installation  

1. Clone the repository:  
   ```bash  
   git clone <repository-link>  
   cd <repository-folder>

2. Build the workspace:
    ```bash
    colcon build

3. Source the setup file:
   ```bash
   source install/setup.bash  

## 🚀 Running the Simulation  

1. Launch the simulation:  
   ```bash
   ros2 launch <package-name> <launch-file>
## 📂 Repository Structure  

- **`src/`**: Contains ROS2 nodes for perception, control, and simulation.  
- **`models/`**: Custom Gazebo models for the simulation.  
- **`config/`**: Configuration files for parameters and settings.  
- **`launch/`**: ROS2 launch files to start the simulation.  

---

## 🤝 Contributions  

Contributions are welcome! If you encounter any issues, have suggestions, or want to enhance the project, please open an issue or submit a pull request. Let's build together!  

---

## 📄 License  

This project is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and distribute this software in accordance with the license terms.  

---  

Start your journey into autonomous parking systems with this project. Feedback and collaboration are highly encouraged!  

   
