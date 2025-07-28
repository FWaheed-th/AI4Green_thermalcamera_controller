# AI4Green_thermalcamera_controller

# PIX Connect OPC UA Controller

A Python application for controlling PIX Connect thermal imaging system via OPC UA, with automated file management.

## Key Features

- **OPC UA Integration**: Connects to OPC UA server to receive slice triggers and job status
- **Dual Snapshot Mode**: 
  - Takes "_recoated" snapshot immediately on trigger
  - Takes "_exposed" snapshot after laser exposure delay (μs)
- **Automated File Management**: 
  - Organizes files into timestamped folders when job is active
  - Moves files to "Untriggered_Folder" when inactive
- **Recording Control**: Start/stop recording with PIX Connect
- **Connection Monitoring**: Automatic reconnection for both OPC UA and PIX Connect

## Requirements

- Python 3.8+
- PIX Connect installed
- OPC UA server access
- Windows OS (for PIX Connect integration)

## Installation

1. Clone this repository
2. Make sure the required dll file are present at the location


## Usage

1. Run the application

2. UI Controls:
- Take manual snapshots
- Start/stop recording
- Toggle auto-snapshot mode
- View connection status


## License

[GPL-3.0 license](LICENSE)