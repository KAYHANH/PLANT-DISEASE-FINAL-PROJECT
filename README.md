# 🌿 Plant Disease Detection & Classification

**Description**

This project leverages deep learning and transfer learning with ResNet50 to detect and classify plant leaf diseases from images. It aims to empower farmers and agricultural experts by automating disease identification, enabling timely interventions, and reducing crop losses.

---

## 📚 Table of Contents

* [Installation](#installation)
* [Dataset](#dataset)
* [Usage](#usage)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

---

## 🔧 Installation

To get started, follow these steps:

1. **Clone this repository:**

   ```bash
   git clone https://github.com/your-username/plant-disease-detection.git
   cd plant-disease-detection
   ```

2. **(Optional) Create and activate a virtual environment:**

   ```bash
   python -m venv env
   source env/bin/activate  # Windows: env\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

---

## 📂 Dataset

This project uses a comprehensive dataset of healthy and diseased plant leaf images to train and evaluate the model.

* **Source:** [Download Dataset from Google Drive](https://drive.google.com/file/d/12OS3a0bLn1zDnhqv5KRRH_BfFml6gCVX/view?usp=sharing)
* **Details:** The dataset contains multiple classes of plant diseases along with healthy leaf images. It has been preprocessed and augmented to improve model robustness.

> **Note:** After downloading, please extract the files and update the dataset path in your notebook or scripts accordingly.

---

## 🚀 Usage

### Option 1: Google Colab

* Open the project notebook in [Google Colab](https://colab.research.google.com).
* Mount Google Drive and set the dataset path accordingly.
* Execute cells sequentially to train and test the model.

### Option 2: Local Machine

* Open `Plant_Disease_Classification.ipynb` in Jupyter Notebook or VS Code.
* Update dataset paths to your local setup.
* Run the notebook step-by-step for training and evaluation.

---

## 📊 Results

After training with transfer learning on ResNet50, the model achieves:

* **Training Accuracy:** \~85%
* **Validation Accuracy:** \~82%
* **Loss:** Smoothly decreasing during training
* **Confusion Matrix:** (Add your results/visualization here)

The model shows reliable performance on unseen data and is suitable for deployment in real-time applications.

---

## 🤝 Contributing

We welcome contributions! To contribute:

1. Fork this repository.
2. Create a new feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.
[View License](https://opensource.org/licenses/MIT)

---

## 📬 Contact

For any questions or collaboration opportunities, contact me at:
**[mdkaunain2957@gmail.com](mailto:mdkaunain2957@gmail.com)**

---

