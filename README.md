# 🍔🥗 Food Image Recognition and Calorie Estimation

This project focuses on developing a machine learning model that can **accurately recognize food items from images** and **estimate their calorie content**, helping users track dietary intake and make informed food choices. It combines computer vision with nutritional data to build a practical health-focused application.

---

## 📌 Project Objective

To build a system that can:

- Classify food items from image input
- Estimate the approximate calorie content
- Enable users to monitor dietary habits with ease

---

## 🗃️ Dataset

- **Source**: kaggle.com/datasets/trolukovich/food11-image-dataset
- **Categories**: e.g., Bread , Dairy product , Dessert , Egg , Fried food , Meat , Noodles-Pasta , Rice , Seafood , Soup , Vegetable-Fruit
- **Data Format**: JPEG/PNG images labeled with food class


---

## 🛠️ Technologies Used

- Python 🐍
- TensorFlow / Keras 🤖
- Pandas & NumPy 🔢
- OpenCV  📷
- Matplotlib / Seaborn 📊
- Jupyter Notebook 📒

---

## 🧹 Data Preprocessing

- Resized images to uniform dimensions (e.g., 128x128)
- Normalized pixel values
- Encoded food categories as numerical labels
- Merged with a nutrition dataset for calorie mapping
- Augmented training data for better generalization

---

## 🚀 Model Development Steps

1. **Image Classification Model**
   - Built a CNN using Keras for multi-class classification
   - Trained to recognize different food items

2. **Calorie Estimation Logic**
   - Mapped each class to an average calorie count
   - Estimated calories based on prediction confidence and food class

3. **Model Evaluation**
   - Accuracy score on classification task
   - Mean Absolute Error (MAE) on calorie prediction

---

## 📚 Learning Outcomes

- Built an end-to-end image classification pipeline
- Learned to link image recognition with real-world nutritional data
- Improved model performance through data augmentation and tuning

---

## 💡 Future Enhancements

- Use object detection to support multiple food items in one image
- Collect portion size from image to estimate more accurate calories
- Build a web/mobile app for users to upload meals and track daily intake
- Integrate with nutrition APIs for detailed info

---

