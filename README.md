# Robot-Design-ELEC330Ass1

## Project Overview

This project involves designing and implementing a robot model for an indoor exploration task, capable of being deployed for over two hours. The project includes designing the robot using CAD software, generating STL files, creating the robot's visual and collision meshes in ROS, and finally generating a URDF file. The robot model is displayed in Gazebo, and appropriate launch files are used to spawn the robot.

## File Structure

- **flat_exploration_robot folder**
  - Contains URDF, launch files, configuration, and mesh files
  - Main files and folders:
    - `CMakeLists.txt`: Build configuration file for CMake
    - `config/`: Contains configuration files
      - `joint_names_flat_exploration_robot.yaml`: Joint names configuration
    - `launch/`: Contains launch files
      - `display.launch`: Launch file to display the robot in Rviz
      - `gazebo.launch`: Launch file to spawn the robot in Gazebo
    - `meshes/`: Contains the STL files for the robot's parts
    - `package.xml`: Package configuration file for ROS
    - `textures/`: Contains texture files (if any)
    - `urdf/`: Contains URDF files


- **flat_exploration_robot_Solidworks folder**
  - Contains the Solidworks files of the robot and all its parts

## Dependencies

- ROS (Robot Operating System)
- Gazebo
- Solidworks (for designing and generating STL files)
- CAD software (Solidworks recommended)

## Final Result Video

[Click here to watch the final result video](<https://youtu.be/wIzx7EtPSE4>)
