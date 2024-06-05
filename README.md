# PosePerfect 🏋️‍♂️

PosePerfect is a real-time posture detection and repetition counting application designed to assist with exercise form and tracking. Using computer vision and machine learning, the application can identify different stages of an exercise and count repetitions with high accuracy.

## 🎥 Demo Video



## 🛠️ System Diagrams

![mermaid-diagram-2024-06-05-102340](https://github.com/DhruvSharma19/mlapp/assets/112254552/8eaaea7e-e22a-490f-8832-d8e222c70f18)
![diagram](https://github.com/DhruvSharma19/mlapp/assets/112254552/cb3836f8-d310-427b-af0d-80da19d62202)

## 🌟 Key Features

- **Real-time Pose Detection**: Utilizes Mediapipe for efficient and accurate pose detection. 🏋️‍♂️
- **Repetition Counting**: Automatically counts exercise repetitions and updates the count in real-time. ⏱️
- **Stage Classification**: Identifies and displays the current stage of the exercise. 📊
- **Probability Display**: Shows the probability of the current pose classification. 📈
- **Dark Mode Interface**: User-friendly dark mode interface using CustomTkinter. 🌑

## Technologies Used 🛠️

- **Python**: Core programming language. 🔵
- **Tkinter**: Standard GUI library for Python. 🖼️
- **CustomTkinter**: Enhanced widgets for a modern look and feel. 🎨
- **OpenCV**: Library for real-time computer vision. 📷
- **Mediapipe**: Framework for building perception pipelines. 🛠️
- **Pandas & Numpy**: Data handling and numerical computations. 📊
- **PIL (Python Imaging Library)**: Image processing capabilities. 🖼️
- **Pickle**: For loading pre-trained machine learning models. 🧠

## Getting Started 🚀

To get a local copy up and running follow these simple steps:

### Prerequisites

Make sure you have Python installed. You can download it from [Python's official website](https://www.python.org/).

### Installation

1. Clone the repo:
   ```sh
   git clone https://github.com/DhruvSharma19/PosePerfect.git
   ```
2. Navigate to the project directory:
   ```sh
   cd PosePerfect
   ```
3. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```
4. Ensure your webcam is connected.

### Usage

1. Run the application:
   ```sh
   python app.py
   ```
2. The GUI should appear. Start performing your exercises in front of the webcam.
3. The application will display the current stage, repetition count, and classification probability in real-time.
4. Use the "RESET" button to reset the repetition counter.

## 🤝 Contributions

We welcome contributions to PosePerfect! To contribute:

1. **Fork the Repository**:
   Click the "Fork" button at the top right corner of the repository page.

2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/your-username/PosePerfect.git
   cd PosePerfect
   ```

3. **Create a New Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make Your Changes**:
   Implement your feature or fix the bug.

5. **Commit Your Changes**:
   ```bash
   git add .
   git commit -m "Add your commit message here"
   ```

6. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Create a Pull Request**:
   Open a pull request from your forked repository's branch to the main branch of the original repository.

We appreciate your contributions and will review your pull request as soon as possible!

## 🙏 Acknowledgements

A big thank you to everyone who contributed to this project! We appreciate your support and feedback.

If you have any questions or need assistance, feel free to open an issue or reach out to the project maintainers. Enjoy using PosePerfect and happy coding! ✨
