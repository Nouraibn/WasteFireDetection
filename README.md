# Waste Fire Detection 🔥

## Overview 🌍
The **Waste Fire Detection** project leverages drones and artificial intelligence (AI) to provide early detection and real-time monitoring of fire incidents in waste management facilities. By identifying smoke and fire at an early stage, this system enhances safety, minimizes damage, and improves emergency response times. 🚁💡

## Features ✨
- **Early Detection**: Uses AI-powered models to detect smoke and fire before they escalate. 🛑
- **Real-Time Monitoring**: Drones provide live video feeds and environmental data. 🎥📡
- **Enhanced Safety**: Supports rapid response to potential fire hazards. 🚒
- **Automation**: Reduces reliance on manual monitoring, ensuring continuous surveillance. 🤖

## Architecture 🏗️
The project integrates drones, AI algorithms, and a central monitoring system:
1. **Drones**: Equipped with cameras and environmental sensors for data collection. 🚁
2. **AI System**: Trained using YOLOv8 to process data and detect smoke and fire. 🔍🔥
3. **Monitoring System**: Displays alerts and live feeds for operator review. 📊
4. **Communication**: Real-time data transmission between drones and the monitoring system. 🌐

## Datasets and Training 📚🖥️
The AI model was trained using the **YOLOv8 framework**, which offers state-of-the-art object detection capabilities. The dataset includes:
- Images of waste facilities under various conditions.
- Annotated data for smoke and fire detection.

To reproduce the training:
1. Prepare your dataset in the YOLO format.
2. Train the model with the following command:
   ```bash
   yolo train model=yolov8 dataset=your-dataset-path epochs=50
   ```

## Installation 🛠️
Follow these steps to set up the project:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/waste-fire-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd waste-fire-detection
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up the drone hardware and configure the connection with the monitoring system.

## Usage 🚀
1. Deploy the drones in the target area. 🚁
2. Start the monitoring system:
   ```bash
   python monitor.py
   ```
3. View real-time alerts and video feeds from the dashboard. 📺
4. Respond to alerts as necessary. ⚡

## Contributing 🤝
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature or fix bug"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License 📜
This project is licensed under the [MIT License](LICENSE).

---

### Contact 📬
For any inquiries or support, please contact [Noura Ibrahim Alnassar](mailto:Noura_alnassar@hotmail.com).
