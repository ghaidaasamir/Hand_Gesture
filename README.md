# Hand Gesture Detection

Simple process for detecting hand gesture in an image of hands by extracting contours that can be used to estimate the number of fingers shown. The process involves reading an image, applying HSV color thresholding for skin detection, performing morphological operations to remove noise, computing a difference mask, and finally detecting and counting contours.


## Requirements

- **Python 3.x**
- **OpenCV**
- **NumPy** 

---

**Run the Script:**  
   ```bash
   hand_gesture.ipynb
   ```

   The script will process the image, and print the number of detected contours.
