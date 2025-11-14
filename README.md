Let's detect **Ambulance** !

<img width="412" height="310" alt="image" src="https://github.com/user-attachments/assets/c3115d87-7d68-45f1-a417-72627e12381a" /> <img width="440" height="295" alt="image" src="https://github.com/user-attachments/assets/44fdfcf5-abf2-4d19-bc39-a829c6fb4fac" />



🧠 Overview
This project applies **YOLOv8-Medium** for real-time **vehicle detection and classification**.  
The model was trained on a Roboflow dataset containing five categories: *Ambulance*, *Bus*, *Car*, *Motorcycle*, and *Truck*.  

🧰 Built With
- Python  
- Ultralytics YOLOv8  
- OpenCV  
- Google Colab  

📌 What’s Inside
- Dataset download and organization  
- Model training and validation  
- Performance evaluation (mAP, precision, recall, F1)  
- Inference on test data, images, and videos  

▶️ Run the Notebook
You can open the `.ipynb` file directly, or run it in Colab:  
**[Open In Colab](https://colab.research.google.com/drive/19vpQAUveJKtbATIP1WBrZNAg7w7tHgZM)**  [https://colab.research.google.com/drive/19vpQAUveJKtbATIP1WBrZNAg7w7tHgZM]

📂 Data Source

The dataset is sourced from [Roboflow](https://public.roboflow.com/ds/6zbwalkMMm?key=z3YTzJ8NNk) [https://public.roboflow.com/ds/6zbwaIkMMm?key=z3YTzJ8NNk] and includes images and bounding-box annotations for vehicle detection.

💬 Results Summary
- Achieved mAP50 ≈ 0.78 on the test set  
- It showed strong accuracy for **Ambulance (mAP50 = 0.995)** and Bus, while Motorcycle had lower scores due to limited samples.  
- Good balance between precision and recall (F1 ≈ 0.75 at conf = 0.37)  
- Model generalizes well to **random images and videos** from online sources  
- Missing annotations in the dataset may slightly affect performance  

🙌 Thanks

Big thanks to the **Caltech + Simplilearn AI/ML Certification Program** for the awesome learning journey.  
This project helped me practice an **end-to-end deep learning pipeline for object detection**.
