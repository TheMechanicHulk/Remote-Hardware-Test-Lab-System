# Remote Hardware Test Lab System for Automobile ECU, Blackberry QNX

## Overview
This project presents a remote hardware test lab system designed for testing automotive Electronic Control Units (ECUs) in a controlled environment. The system was developed using a LAMP stack (Linux, Apache, MySQL, PHP) and enabled remote interaction with ECUs via a web dashboard. Customized Board Support Packages (BSPs) were developed to facilitate the unit testing of various ECUs, and Ansible scripts were created to automate deployment processes. The system is designed to streamline the remote testing process for automotive ECUs, making testing more efficient and accessible.

## Features
- **Remote Access**: A user-friendly web dashboard that allows remote testing and monitoring of automotive ECUs.
- **BSP Development**: Customized Board Support Packages (BSPs) to support unit testing for different ECU models.
- **Automated Deployment**: Ansible scripts were developed to automate the deployment and configuration of the test lab system.
- **LAMP Stack**: The system is built on a Linux, Apache, MySQL, and PHP (LAMP) stack for reliable web-based interaction.
- **Hardware Integration**: Hardware procurement and integration for seamless communication between the test lab system and ECUs.

## Workflow
1. **System Design**:
    - Utilized the LAMP stack to build the backend and frontend for remote interaction with the ECUs.
    - Developed a user-friendly web interface for easy control and monitoring.
2. **BSP Development**:
    - Created and customized BSPs for different ECUs to facilitate unit testing.
    - Optimized BSPs for efficient and accurate test results in the remote lab environment.
3. **Automation with Ansible**:
    - Automated system deployment and updates using Ansible scripts for consistent environment setup.
4. **Hardware Procurement & Integration**:
    - Orchestrated the procurement of hardware components necessary for the remote test lab.
    - Integrated the hardware seamlessly with the test lab system to ensure reliable communication with ECUs.

## Technologies Used
- **LAMP Stack**: The backend is built using Linux, Apache, MySQL, and PHP, providing a reliable foundation for the web dashboard.
- **Ansible**: Employed Ansible to automate deployment and ensure consistency in testing environments.
- **Blackberry QNX**: Blackberry QNX was the operating system for running BSPs and managing ECU communication.
- **BSPs**: Developed custom BSPs for different ECUs to support testing scenarios.
- **ECUs**: Tested various automotive ECUs in a controlled, remote lab environment.

## How to Run the Project
1. **Setup LAMP Stack**:
    - Install and configure Linux, Apache, MySQL, and PHP on the server to host the web dashboard.
2. **Clone the Repository**:
    ```bash
    git clone https://github.com/TheMechanicHulk/Remote-Hardware-Test-Lab-ECU.git
    ```
3. **Setup Ansible for Automation**:
    - Run the provided Ansible scripts to set up and configure the test lab system for hardware testing.
4. **Develop and Deploy BSPs**:
    - Ensure that BSPs for each ECU are properly configured and deployed within the test lab environment.
5. **Connect Hardware**:
    - Procure and integrate the necessary hardware for the ECUs per the setup instructions.
6. **Access the Web Dashboard**:
    - Navigate to the web dashboard to begin remote testing and monitoring of the ECUs.

## File Structure
- `src/`: Contains the PHP and backend code for the web dashboard.
- `ansible/`: Ansible scripts for automating system deployment and configuration.
- `bsp/`: BSP configurations for different ECUs used in testing.
- `docs/`: Documentation on hardware integration and lab setup.

## Hardware Setup
- **ECUs**: Connect the automotive ECUs to the test system.
- **Hardware Components**: Ensure the components (interface boards) are connected and functioning.

## Future Improvements
- **Enhanced Monitoring**: Implement real-time monitoring and logging of ECU testing metrics.
- **Expanded ECU Support**: Add support for additional ECU models with corresponding BSPs.
- **Scalability**: Improve the system's ability to handle large-scale testing scenarios across multiple remote locations.

## Acknowledgements
This project would not have been possible without the support of the team at Blackberry QNX and the open-source community for LAMP stack and Ansible resources.
