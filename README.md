# Pineapple Detection & Automated Sorting using YOLO11

<p align="center">
  <b>Computer Vision • YOLO11 • Raspberry Pi • Edge AI • Smart Agriculture</b>
</p>

This project explores an AI-based **pineapple detection and sorting system** using a YOLO11 object-detection model. The system is designed to identify pineapple maturity/ripeness from camera images and support automated sorting using an embedded vision system.

The project combines **deep learning, computer vision, Raspberry Pi-based edge processing, and automated actuation** to reduce manual inspection and improve consistency in agricultural sorting.

---

## 📌 Project Objectives

- 🍍 Detect pineapples using computer vision
- 🤖 Apply a YOLO11 object-detection model
- 📷 Capture images using an embedded camera system
- 🧠 Classify pineapple maturity/ripeness
- ⚙️ Support automated sorting and actuation
- 🌾 Improve consistency and reduce manual inspection
- 📈 Evaluate model performance using quantitative metrics

---

## 🏗️ System Concept

```text
       Pineapple on Conveyor
                │
                ▼
        ┌───────────────┐
        │ Pi Camera     │
        │ Image Capture │
        └───────┬───────┘
                │
                ▼
        ┌───────────────┐
        │ YOLO11 Model  │
        │ Detection +   │
        │ Classification│
        └───────┬───────┘
                │
         Ripeness Result
                │
                ▼
        ┌───────────────┐
        │ Raspberry Pi  │
        │ Decision Logic│
        └───────┬───────┘
                │
                ▼
        ┌───────────────┐
        │ Servo / Gate  │
        │ Sorting Action│
        └───────────────┘
```

---

## 🤖 AI Model

The repository includes:

- YOLO11-based detection workflow
- Jupyter Notebook for model experimentation
- Confusion matrix
- Performance graph
- Example detection output
- Inference/control code

The project reports approximately **93% detection/classification accuracy** in the associated project evaluation. Performance may vary with dataset quality, lighting, camera position, and deployment conditions.

---

## 📊 Model Evaluation

### Confusion matrix

![Confusion Matrix](CONFUSION%20MATRIX)

### Performance graph

![Performance Graph](Performance%20Graph)

### Detection output

![Detection Output](OUTPUT)

---

## 🧰 Technologies Used

| Technology | Role |
|---|---|
| **YOLO11** | Pineapple detection/classification |
| **Raspberry Pi** | Edge-AI processing and system control |
| **Pi Camera** | Image acquisition |
| **Python** | AI and control software |
| **Jupyter Notebook** | Model development and evaluation |
| **Computer Vision** | Image-based inspection |
| **Servo Actuation** | Automated sorting mechanism |

---

## 🔄 Working Principle

1. Pineapples move through the inspection area.
2. The camera captures an image of the fruit.
3. The YOLO11 model processes the image.
4. The system detects the pineapple and determines its classification.
5. Raspberry Pi control logic interprets the detection result.
6. A sorting mechanism can direct the fruit to the appropriate path.
7. Detection results can be recorded for performance analysis.

---

## 📁 Repository Structure

```text
Pineapple-Detection-using-YOLO-V11/
│
├── CODE
├── CONFUSION MATRIX
├── OUTPUT
├── Performance Graph
├── pineapple_detection.ipynb
├── LICENSE
└── README.md
```

---

## 🎯 Applications

- Automated fruit sorting
- Agricultural quality inspection
- Smart farming
- Food-processing automation
- Computer-vision-based grading systems
- Edge-AI agricultural systems

---

## 🚀 Future Improvements

- Deploy the model directly on Raspberry Pi hardware
- Add real-time conveyor tracking
- Improve classification accuracy with a larger dataset
- Add multiple maturity classes
- Add automatic conveyor-speed control
- Record production/sorting statistics
- Optimize inference speed for edge deployment

---

## 👨‍💻 Author

**Alwin Babu**  
Electronics & Communication Engineering

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
