# Badminton Swing Wearable Device Time-Series Dataset

## **Introduction**
This dataset contains detailed 6-axis time-series data collected from wearable devices during badminton swings performed by 203 participants. The purpose of this dataset is to support research in sports science, motion analysis, and federated learning.

### **Data Collection**
- **Task**: Participants returned shuttlecocks served by professional players using a "high clear" stroke.
- **Sessions**: Each participant completed 30 serves. However, a few participants had only 20 serves due to specific conditions, as noted in the label file.
- **Accuracy Protocol**: Participants were instructed not to swing if they could not perform a proper "high clear" stroke, ensuring data integrity.
- **Result**: Most participants completed approximately 30 swings, but the total count varies slightly between individuals.

### **Evaluation**
- Video recordings of the swings were reviewed by professional coaches.
- Each swing was assessed on five key dimensions, with scores ranging from 1 (low) to 5 (high):
  1. Swing Path Accuracy
  2. Swing Speed Smoothness
  3. Wrist Rotation Timing Accuracy
  4. Hit Timing Accuracy
  5. Ball Contact Position Accuracy
- Coaches also provided qualitative feedback in Traditional Chinese.

---

## **File Description**
1. **`time_series_data_1.zip` & `time_series_data_2.zip`**:
   - Contain 203 de-identified `.txt` files.
   - Each file includes 6-axis time-series data with the following format:
     ```
     Timestamp1, Acceleration_X, Acceleration_Y, Acceleration_Z, Timestamp2, AngularAcceleration_X, AngularAcceleration_Y, AngularAcceleration_Z
     ```

2. **`label_and_comments.xlsx`**:
   - Summary of evaluation results and comments for all participants.
   - Columns include:
     - `Filename`: Corresponding `.txt` file name.
     - `Swing Path Accuracy`: Score (1-5).
     - `Swing Speed Smoothness`: Score (1-5).
     - `Wrist Rotation Timing Accuracy`: Score (1-5).
     - `Hit Timing Accuracy`: Score (1-5).
     - `Ball Contact Position Accuracy`: Score (1-5).
     - `Comments`: Qualitative feedback in Traditional Chinese.
     - `Notes`: Additional information about specific swings.

---

## **Usage Instructions**
1. **Download**:
   - Retrieve the dataset files from either of the following sources:
     - **OSF**: [https://doi.org/10.17605/OSF.IO/4UY38](https://doi.org/10.17605/OSF.IO/4UY38)
2. **Extract**:
   - Unzip the `.zip` files to access the 203 de-identified `.txt` files.
3. **Analyze**:
   - Use the time-series `.txt` files for quantitative analysis.
   - Use the `label_and_comments.xlsx` file to incorporate expert evaluations and comments in your study.

---

## **Citation**
If you use this dataset, please cite it as follows:
Si, Pei-Chi (2025). Badminton Swing Wearable Device Time-Series Dataset. OSF. https://doi.org/10.17605/OSF.IO/4UY38

[![DOI](https://img.shields.io/badge/DOI-10.17605%2FOSF.IO%2F4UY38-blue)](https://doi.org/10.17605/OSF.IO/4UY38)

---

## **License**
This dataset is made available under the **CC-BY 4.0 License**. You are free to use, share, and adapt the dataset as long as you provide appropriate attribution.

---

## **Contact**
For questions or further details, please contact:  
**Si, Pei-Chi**  
**National Chengchi University(NCCU), Department of Computer Science College of Science**  
**111753214@g.nccu.edu.tw**



