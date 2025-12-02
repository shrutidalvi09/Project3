# Face-Based Attendance System using Python & OpenCV
A Python and OpenCV–powered attendance system that detects, registers, and recognizes faces to automate student attendance. The project captures face images, trains a recognition model, and logs attendance into CSV files for each subject. It includes a simple GUI for smooth interaction.

---

🚀 Features
* Face registration with ID and name
* Automatic image capture (up to 50 samples per user)
* Model training using LBPH (Local Binary Patterns Histograms)
* Real-time face recognition
* Automatic attendance marking
* CSV-based attendance records
* Simple and easy-to-use Tkinter GUI
* Attendance viewer in tabular format

---

🛠️ Tech Stack
* **Python 3.x**
* **OpenCV** for face detection
* **Tkinter** for the GUI
* **NumPy** for array processing
* **Pandas** for attendance table handling

---

📦 Installation
Clone or download the repository:
```bash
git clone <your-repo-url>
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Create required folders:
```
TrainingImage/
TrainingImageLabel/
Attendance/
```

Update file paths inside `attendance.py` and `automaticAttendance.py` according to your system.
---

▶️ How It Works
1. Register a New Student
* Enter **ID** and **Name**
* Click **Take Image**
* The system captures ~50 face images and stores them in `TrainingImage/`

2. Train the Model
* Click **Train Image**
* The system converts face images into numerical form and trains the LBPH recognizer

3. Automatic Attendance
* Click **Automatic Attendance**
* Enter subject name
* System recognizes faces in real time
* Attendance is saved in a CSV file for that subject
  (Example: `Attendance/SubjectName.csv`)

4. View Attendance
* Click **View Attendance**
* A table displays all stored attendance entries

---

📁 Project Structure
```
│-- attendance.py
│-- automaticAttendance.py
│-- train.py
│-- requirements.txt
│-- TrainingImage/
│-- Attendance/
│-- README.md
```

---

📷 Screenshots
*(Insert your screenshots here)*
Example:

```
Simple UI  
Image Capture  
Recognition Window  
Attendance Table View
```

---

⭐ Contribution & Support
Feel free to fork this project, submit issues, or contribute improvements.
If you find this useful, consider giving the repository a ⭐.

---
