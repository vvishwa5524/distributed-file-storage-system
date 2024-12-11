# Distributed File Storage System

A robust distributed file storage system designed to handle file storage and retrieval across multiple nodes.

## Features
- **Distributed Architecture**: Utilizes multiple nodes for data storage, ensuring redundancy and reliability.
- **Client-Server Model**: Interact with the system using the provided `client.py` script.
- **Scalability**: Easily add more nodes to increase storage capacity.
- **Configuration Driven**: Configurations are managed using the `config.yaml` file.
- **Protobuf Integration**: Efficient communication using protocol buffers.

## Project Structure
- **`client.py`**: Client-side script for interacting with the storage system.
- **`server.py`**: Server-side script for managing storage nodes.
- **`config.yaml`**: Configuration file for system settings.
- **`service/`**: Contains service-specific implementations.
- **`utils/`**: Utility scripts for various functionalities.
- **`proto/`**: Protocol buffer definitions.
- **`generated/`**: Auto-generated code from protobuf definitions.
- **`images/`**: Contains images for documentation.
- **`files/`**: Directory for storing user files.
- **`iptable.txt`**: IP address table for distributed nodes.
- **`requirements.txt`**: Python dependencies for the project.

## Prerequisites
- Python 3.8 or higher
- `pip` for managing Python packages
- Protobuf compiler (`protoc`)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/vvishwa5524/Distributed-File-Storage-System.git
   cd Distributed-File-Storage-System
