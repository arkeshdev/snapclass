# 🎓 SnapClass

An AI-powered smart attendance management system built with **Python**, **Streamlit**, and **Supabase**. SnapClass uses **Face Recognition**, **Voice Recognition**, and **QR Code technology** to simplify and automate attendance management for educational institutions.

## ✨ Features

### 👨‍🎓 Student
- Student Registration
- Secure Password Login
- Face Recognition Login
- Voice Registration
- QR Code Attendance
- View Attendance History
- Student Dashboard

### 👨‍🏫 Teacher
- Teacher Login
- Teacher Dashboard
- Manage Subjects
- Voice-based Attendance
- Generate QR Code Attendance
- View Attendance Records
- Download Attendance Reports in Excel (.xlsx)

### 🤖 AI Features
- Face Recognition Authentication
- Voice Recognition
- QR Code Attendance

## 🛠️ Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python
- **Database:** Supabase (PostgreSQL)
- **Computer Vision:** OpenCV, face_recognition, dlib
- **Voice Recognition:** Librosa, Resemblyzer
- **QR Code:** Segno
- **Security:** bcrypt
- **Libraries:** NumPy, Pandas, Pillow

## 📂 Project Structure

```text
SnapClass/
│── src/
│   ├── components/
│   ├── database/
│   ├── screens/
│   ├── services/
│   ├── ui/
│   └── utils/
│── app.py
│── requirements.txt
│── README.md
│── LICENSE
```

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/arkeshdev/snapclass.git
cd snapclass
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure your Supabase credentials and run:

```bash
streamlit run app.py
```

## 🔮 Future Enhancements

- Attendance Analytics Dashboard
- AI-powered Attendance Insights
- Email Notifications
- Multi-Institution Support

## 📄 License

This project is licensed under the MIT License.
