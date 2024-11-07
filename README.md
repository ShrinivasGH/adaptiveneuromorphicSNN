# adaptiveneuromorphicSNN
Abstract
This project simulates and evaluates the performance of adaptive neuromorphic circuits designed for low-power spiking neural networks (SNNs). By integrating biologically-inspired mechanisms, such as spike-timing-dependent plasticity (STDP) and threshold adaptation, the design aims to achieve real-time computation with minimal energy use, suitable for edge AI applications. Simulations focus on pre-layout and post-layout analyses to assess the circuit’s performance characteristics under various conditions.
# A Glance at the Adaptive Neuromorphic IP
Adaptive neuromorphic circuits are crucial for implementing spiking neural networks that operate efficiently in terms of power and speed. These circuits are designed to mimic biological neurons, using adaptive mechanisms to adjust circuit behavior based on input patterns. This project’s design incorporates STDP, allowing the circuit to dynamically alter responses based on timing and frequency of input spikes, making it ideal for energy-constrained applications. Adaptive neuromorphic circuits have wide applications in signal processing, robotics, sensor interfaces, and embedded AI for edge devices.
# Overview of the Neuromorphic Circuit Components
The adaptive neuromorphic circuit is designed to enhance efficiency, with a high power supply rejection ratio (PSRR) and minimal temperature dependency. The design focuses on components that support STDP, enabling the circuit to learn and adapt without extensive computation. The principle of operation, circuit implementation, challenges, improvements, conclusions, and future scope will be discussed further.
# Block Diagram of the Adaptive Neuromorphic IP
 
# Installing Ngspice on Windows 10
 1. Download Ngspice
Visit the Ngspice download page and download the latest stable version for Windows (usually a .zip file).
2. Install Ngspice
Unzip the downloaded file.
Move the extracted folder to a directory of your choice (e.g., C:\Ngspice).Inside the folder, locate ngspice.exe – this is the executable file for Ngspice.
3. Set Up Environment Variable (Optional but Recommended)
To make it easier to use Ngspice from any command prompt location, add the Ngspice directory to your system’s PATH environment variable:
Open Control Panel > System and Security > System.
Click on Advanced system settings and then on Environment Variables.
Under System Variables, find the Path variable, select it, and click Edit.
Add the path to your Ngspice folder (e.g., C:\Ngspice) and click OK.

# Running Ngspice Simulations on Windows 10
Once Ngspice is installed, you can use it to run simulations on your circuit netlists.

1. Open Command Prompt
Press Win + R, type cmd, and hit Enter.
(If you added Ngspice to your PATH, you can run Ngspice commands directly from any directory.)

2. Navigate to Your Netlist Folder
Use the cd command to go to the folder containing your netlist files.

example:
cd C:\Users




