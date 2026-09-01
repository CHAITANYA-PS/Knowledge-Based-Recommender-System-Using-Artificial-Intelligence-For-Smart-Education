# Knowledge-Based Recommender System Using Artificial Intelligence For Smart Education

## Title of the Project
**Knowledge-Based Recommender System Using Artificial Intelligence For Smart Education**

A smart AI-driven recommendation and peer-networking platform tailored for students to discover academic peers, project collaborators, and study partners based on shared technical interests, departmental background, and academic domains using Natural Language Processing (NLP) and Machine Learning techniques.

## About
<!--Detailed Description about the project-->
The **Knowledge-Based Recommender System for Smart Education** is an intelligent web-based application built to enhance student networking and collaborative learning in educational institutions. In traditional academic environments, finding peers with matching technical skill sets, complementary interests, or shared project goals often requires manual inquiries and ad-hoc searches. 

This project solves this challenge by leveraging **Natural Language Processing (NLP)**, specifically **TF-IDF (Term Frequency-Inverse Document Frequency) Vectorization** and **Cosine Similarity**, to analyze student interest profiles and dynamically compute compatibility scores. The system features a responsive **Streamlit** user interface, secure authentication (for both Students and Administrators), profile management, and a centralized **SQLite** relational database.

## Features
<!--List the features of the project as shown below-->
- **AI-Powered Recommendation Engine**: Utilizes TF-IDF and Cosine Similarity to compute affinity scores and recommend best-fit peer connections.
- **Role-Based Access Control**:
  - **Student Portal**: User registration, login, profile setup, and personalized connection discovery.
  - **Admin Portal**: Comprehensive dashboard to view, add, edit, and delete student records from the database.
- **Interactive Streamlit Web UI**: Clean, responsive, and easy-to-navigate user interface with custom styling.
- **Lightweight & Fast**: Built with Python, Streamlit, SQLite, and Scikit-Learn with minimal computational overhead.
- **Cloud Deployed**: Ready for deployment on Streamlit Community Cloud.

## Requirements
<!--List the requirements of the project as shown below-->
* **Operating System**: Windows 10/11, macOS, or Linux (Ubuntu 20.04+)
* **Development Environment**: Python 3.8 or later
* **Frameworks & Libraries**:
  - `streamlit` - Interactive web application framework
  - `scikit-learn` - TF-IDF vectorization and cosine similarity calculations
  - `pandas` - Data manipulation and table rendering
  - `sqlite3` - Lightweight embedded relational database management
* **IDE**: VSCode / PyCharm / Any Python IDE
* **Version Control**: Git & GitHub

## Live Deployment
- **Deployed App URL**: [https://kbrsminiprojectsaveetha.streamlit.app/](https://kbrsminiprojectsaveetha.streamlit.app/)

## Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/CHAITANYA-PS/Knowledge-Based-Recommender-System-Using-Artificial-Intelligence-For-Smart-Education.git
   cd Knowledge-Based-Recommender-System-Using-Artificial-Intelligence-For-Smart-Education
   ```

2. **Install dependencies:**
   ```bash
   pip install -r Miniproject/Miniproject-main/code/requirements.txt
   ```
   *(Or `pip install streamlit scikit-learn pandas`)*

3. **Run the Streamlit application:**
   ```bash
   cd Miniproject/Miniproject-main/code
   streamlit run App.py
   ```

## System Architecture
<!--System Architecture Workflow-->
```
+-------------------------------------------------------------+
|                     Streamlit Web UI                        |
|  (Student Registration / Login / Admin Management Dashboard)|
+------------------------------+------------------------------+
                               |
                               v
+-------------------------------------------------------------+
|                  Database Layer (SQLite3)                   |
|       (Stores Student Profiles, Credentials & Interests)    |
+------------------------------+------------------------------+
                               |
                               v
+-------------------------------------------------------------+
|                   AI Recommendation Engine                  |
|    1. Extract Interest Strings                              |
|    2. TF-IDF Vectorization                                  |
|    3. Cosine Similarity Matching Matrix                     |
|    4. Rank & Recommend Top Peer Connections                 |
+-------------------------------------------------------------+
```

## Results and Impact
<!--Give the results and impact as shown below-->
The Knowledge-Based Recommender System successfully bridges the gap between students seeking collaborators across departments and years. By utilizing content-based filtering on domain interests, it facilitates meaningful student connections, fosters academic collaboration, and enhances the smart education ecosystem.

## References
1. F. Ricci, L. Rokach, and B. Shapira, *Introduction to Recommender Systems Handbook*, Springer, 2015.
2. C. D. Manning, P. Raghavan, and H. Schütze, *Introduction to Information Retrieval*, Cambridge University Press, 2008.
