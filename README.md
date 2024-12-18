# FarmBot Interfaces Documentation

The `farmbot_interfaces` package provides a collection of ROS2 message and service definitions tailored for integrating and controlling FarmBot hardware within a ROS2 environment. These interfaces facilitate seamless communication between various ROS2 nodes and the FarmBot system, enabling efficient automation and monitoring of farming tasks.

## Overview

The `farmbot_interfaces` package defines custom messages and services that represent the various commands, statuses, and data exchanges pertinent to FarmBot operations. By utilizing these standardized interfaces, developers can create ROS2 nodes that interact cohesively with FarmBot hardware and other components within the ROS2 ecosystem.

## Repository Structure

The repository is organized as follows:

- `action/`: Contains action definitions for long-running tasks.
- `msg/`: Includes message definitions for data structures used in topics.
- `srv/`: Houses service definitions for request-response interactions.
- `CMakeLists.txt`: Configures the build process for the package.
- `package.xml`: Specifies package metadata and dependencies.

## Prerequisites

Before installing the `farmbot_interfaces` package, ensure the following:

- **ROS2 Installation**: ROS2 Humble Hawksbill or a compatible version should be installed on your system.
- **Development Tools**: Ensure that you have the necessary development tools and dependencies for building ROS2 packages.

## Installation

1. **Clone the Repository**:

   Navigate to your ROS2 workspace's `src` directory and clone the repository:

   ```bash
   cd ~/ros2_ws/src
   git clone https://github.com/Agroecology-Lab/farmbot_interfaces.git
   ```

2. **Build the Package**:

   After cloning, navigate back to the workspace root and build the package using `colcon`:

   ```bash
   cd ~/ros2_ws
   colcon build --packages-select farmbot_interfaces
   ```

3. **Source the Workspace**:

   Once the build is complete, source the setup file to overlay this workspace into your environment:

   ```bash
   source install/setup.bash
   ```

## Message types   

The `farmbot_interfaces` package defines several custom ROS2 message types that facilitate communication between ROS2 nodes and FarmBot hardware. Here are the primary message types and their functions:
  

## Usage

With the `farmbot_interfaces` package installed and sourced, you can develop ROS2 nodes that publish, subscribe, and interact using the defined messages and services. This standardization ensures compatibility and streamlined communication within the FarmBot ROS2 ecosystem.

## Contributing

Contributions to the `farmbot_interfaces` package are welcome. To contribute:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix.
3. Implement your changes, ensuring adherence to ROS2 development standards.
4. Test your changes thoroughly.
5. Submit a pull request with a detailed description of your changes.

## Support

For issues, questions, or further assistance with the `farmbot_interfaces` package, please open an issue in the [GitHub repository](https://github.com/farmbot-ros/farmbot_interfaces/issues).

## License

This package is licensed under the MIT License. For more details, refer to the `LICENSE.md` file in the repository.
