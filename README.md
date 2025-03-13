# HackMAIT_6.0
# MindGuardian
### **Project Title**  
**MindGuardian - AI-Powered Mental Health Assistant for Students**  

---

### **Problem Statement**  
Mental health issues among college students have surged globally, with studies indicating that **1 in 3 students** experience anxiety, depression, or burnout. Stigma, lack of awareness, and limited access to counselors prevent students from seeking help, leading to academic decline, dropouts, and even tragic incidents of self-harm.  

**Real-Life Validation**:  
- **Example 1**: A 2022 survey by the WHO reported that **45% of Indian students** aged 18–25 experienced moderate to severe stress during exams.  
- **Example 2**: Delhi University recorded **12 student suicides** in 2023 due to academic pressure and isolation.  
- **Example 3**: Campus counseling centers are often understaffed, with a **1:1500 counselor-to-student ratio**, making timely intervention nearly impossible.  

---

### **Solution / Product**  
**MindGuardian** is an **AI-driven mental health assistant** that provides **anonymous, 24/7 emotional support** to students via a chatbot. It uses **NLP-based sentiment analysis** to detect distress, offers coping strategies, and alerts campus counselors in high-risk cases while preserving user anonymity.  

#### **Key Features**  
1. **Anonymous Chat Interface**: Students interact via a secure, non-traceable chatbot.  
2. **Real-Time Sentiment Analysis**: NLP models (e.g., BERT) detect emotional states (e.g., anxiety, depression) from text inputs.  
3. **Emergency Escalation**: Triggers alerts to counselors if suicidal ideation or severe distress is detected.  
4. **Institutional Dashboard**: Colleges monitor **aggregate mental health trends** (e.g., spikes in stress during exams) without accessing individual data.  
5. **Resource Hub**: Curated self-help guides, meditation exercises, and crisis helplines.  

---

### **Approach & Working**  
#### **1. Technical Approach**  
- **Frontend**: React.js for a student-friendly web app and counselor dashboard.  
- **Backend**: Java Spring Boot for secure API handling and user session management.  
- **AI/ML**: Python with TensorFlow/PyTorch for NLP sentiment analysis (fine-tuned on mental health datasets).  
- **Database**: SQL (MySQL) to store anonymized chat logs and aggregate analytics.  
- **Security**: End-to-end encryption for chats and role-based access control for counselors.  

#### **2. Workflow**  
1. **Student Interaction**:  
   - Student chats with the bot about their feelings.  
   - NLP model analyzes text for keywords (e.g., "suicide," "hopeless") and emotional tone.  
2. **Risk Assessment**:  
   - Low Risk: Bot shares coping strategies or meditation videos.  
   - High Risk: System notifies counselors with a anonymized report (e.g., "Student ID#45: Severe depression detected").  
3. **Counselor Dashboard**:  
   - Track trends (e.g., "30% of users reported anxiety this week").  
   - Initiate anonymous outreach campaigns (e.g., workshops during exam season).  

---

### **Future Scope & Scalability**  
1. **Multilingual Support**: Expand beyond English to Hindi and regional languages.  
2. **Wearable Integration**: Sync with smartwatches to detect physiological stress signals (e.g., elevated heart rate).  
3. **Predictive Analytics**: Use historical data to identify at-risk students *before* crises (e.g., declining academic performance + late-night chat patterns).  
4. **Global Adaptation**: Partner with universities worldwide by customizing datasets (e.g., cultural nuances in expressing distress).  
5. **Gamification**: Reward students for practicing self-care (e.g., "Mindfulness Badges").  

---

### **Technologies to Be Used**  
1. **AI/ML**: Python, TensorFlow, Hugging Face Transformers (BERT), NLTK.  
2. **Backend**: Java Spring Boot, REST APIs, JWT for authentication.  
3. **Database**: MySQL with anonymization techniques (data masking).  
4. **Frontend**: React.js, Redux, Chart.js for analytics.  
5. **Security**: AES-256 encryption, OAuth 2.0.  
6. **Deployment**: Docker, AWS EC2.  



### **Competition Overview & Strategic Alignment**  
**HackMAIT 6.0** (hosted by **Maharaja Agrasen Institute of Technology, Delhi**) is part of **Impulse 2025**, focusing on themes like **Healthcare, Cybersecurity, and Ed-Tech**. MindGuardian aligns with the **Healthcare** track by addressing mental health crises among students through scalable AI innovation.  

#### **Why HackMAIT 6.0?**  
1. **Theme Fit**: Directly targets the **Healthcare** theme with a focus on preventive mental wellness, reducing institutional burdens.  
2. **Social Impact**: Resonates with MAIT’s goal to foster **student-centric solutions** for real-world problems.  
3. **Scalability**: Designed for rapid deployment in MAIT and other Delhi/NCR colleges, with potential for nationwide adoption.  

---

### **Execution Strategy for HackMAIT 6.0**  
#### **Pre-Hackathon Prep (Before March 9, 2025)**  
- **Research**: Analyze anonymized stress patterns from MAIT’s student surveys (if publicly available).  
- **Toolkit Setup**: Pre-download open-source libraries (TensorFlow, React.js) to comply with "no pre-work" rules.  
- **Mentor Outreach**: Discuss feasibility with HackMAIT mentors to refine NLP model architecture.  

#### **36-Hour Hackathon Plan**  
**Day 1 (March 9, 10 AM – 5 PM)**  
- **Hour 0–4**: Build MVP chatbot with React.js frontend + Java Spring Boot APIs.  
- **Hour 4–8**: Train NLP model on mental health datasets (e.g., Crisis Text Line corpus).  
- **Hour 8–12**: Implement encryption and anonymization in MySQL.  

**Night (March 9, 5 PM – March 10, 9 AM)**  
- **Debugging**: Test sentiment analysis accuracy and fix false positives/negatives.  

**Day 2 (March 10, 9 AM – 10 PM)**  
- **Hour 12–24**: Develop counselor dashboard with trend analytics (Chart.js).  
- **Hour 24–30**: Integrate emergency alert system via Twilio API for SMS notifications.  
- **Hour 30–36**: Create pitch deck + demo video highlighting MAIT-specific use cases.  

#### **Post-Submission (March 11–18, 2025)**  
- **Judging Phase**: Highlight MAIT’s potential to lead Delhi/NCR in student mental health innovation.  
- **Post-Hackathon Scalability**: Partner with MAIT’s counseling center for pilot testing.  

---

### **Unique Value Proposition for HackMAIT**  
1. **Local Relevance**: Tailored for Delhi/NCR student stress factors (e.g., competitive exams, commute stress).  
2. **Cost-Effective**: Uses MAIT’s existing infrastructure (e.g., college Wi-Fi, LMS integration).  
3. **Compliance**: Adheres to HackMAIT’s rules with all code written during the event (GitHub logs as proof).  

---

### **Expected Outcomes**  
1. **For Students**: Reduce stigma around mental health with 24/7 anonymous support.  
2. **For MAIT**: Position the institute as a pioneer in AI-driven student wellness.  
3. **For Judges**: Demonstrate a **working prototype** with live sentiment analysis and counselor alerts.  
---

### **Why This Idea Stands Out?**  
1. **Privacy-Centric**: Unlike existing apps (e.g., Woebot), MindGuardian **never stores personal data**, addressing stigma-related fears.  
2. **Institutional Impact**: Empowers colleges to take **data-driven mental health initiatives** (e.g., allocating resources during exam weeks).  
3. **Scalable MVP**: A functional prototype can be built in 36 hours using open-source libraries and pre-trained models.  
