# 🎨 AI-Powered Art Classification

An advanced deep learning-based system for classifying artwork images into 30 distinct artistic styles, including **Cubism, Surrealism, Impressionism**, and more. This project leverages **state-of-the-art CNN architectures** to achieve high-precision art recognition.

---

## 🚀 Features

- **Trained on 7,315+ artwork images** across **30 artistic styles**.
- **Implemented deep learning models**: `ResNet152V2`, `Xception`, and `InceptionV3`.
- **Achieved 97% accuracy** using `ResNet152V2`.
- **Explainability with Grad-CAM**: Generates heatmaps to visualize model decisions.
- **Potential applications** in **museum archiving, e-commerce, and AI-powered art education**.

---

## 📂 Dataset

The dataset used for this project can be found here: [Surreal Symphonies - A Dataset of Diverse Art](https://www.kaggle.com/datasets/cyanex1702/surreal-symphonies-a-dataset-of-diverse-art).

---

## 📌 Model Architectures

The following pre-trained deep learning models were fine-tuned for the classification task:

- **ResNet152V2** *(Best Performer: 97% Accuracy)*
- **Xception**
- **InceptionV3**

These models were trained and evaluated to determine the most efficient approach for accurate art classification.

---

## 🔍 Explainability with Grad-CAM

To ensure transparency in AI-driven decisions, **Grad-CAM (Gradient-weighted Class Activation Mapping)** was used to generate heatmaps, highlighting the key areas in images that influenced the model’s predictions.

---

## 🛠 Installation & Setup

Clone the repository:
```bash
git clone https://github.com/your-username/ai-art-classification.git
cd ai-art-classification
```

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🎯 Training the Model

To train the model, run the following command:
```bash
python train.py --model resnet152v2 --epochs 20 --batch_size 32
```

For other models, specify `--model xception` or `--model inceptionv3`.

---

## 📊 Evaluation

Evaluate the trained model on the test dataset:
```bash
python evaluate.py --model resnet152v2
```

---

## 📈 Grad-CAM Visualization

To generate heatmaps for model predictions:
```bash
python grad_cam.py --image sample.jpg --model resnet152v2
```

This will output a visualization of the regions in the image that contributed to the classification.

---

## 🔮 Future Applications

This AI-powered classification system can be expanded to various domains:

- 🏛️ **Museum Archiving**: Digitally categorize and preserve artworks.
- 🛍️ **E-commerce**: Enable style-based search for art marketplaces.
- 📚 **AI-powered Art Education**: Assist students in learning about different artistic styles.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 📩 Contact

For any inquiries or collaborations, reach out at **your-email@example.com**.

---

⭐ **If you found this project useful, don't forget to star this repo!** ⭐
