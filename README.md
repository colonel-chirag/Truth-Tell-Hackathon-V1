# TruthTell - Combat Misinformation in Real-Time  

## 🚀 Project Overview  
TruthTell is an AI-powered tool designed to tackle misinformation during live broadcasts. Leveraging cloud technologies, machine learning, and data analytics, our tool provides real-time detection, flagging, and alerts for misinformation, empowering broadcasters and viewers alike.  

### Key Features:  
- **Real-Time Misinformation Detection**: Uses advanced NLP and machine learning techniques.  
- **Interactive Dashboard**: Visualizes misinformation trends and impacts for quick decision-making.  
- **Future Expansions**: Browser plugins or social media extensions for seamless integration into daily use.  

---

## 🧩 Problem Statement  
**Hack the Hoax**:  
Misinformation spreads at lightning speed in today’s digital landscape, especially during live events. Journalists, broadcasters, and viewers need reliable, real-time tools to identify and counter false information before it propagates.  

### The Challenge:  
Develop a scalable AI tool that:  
- Detects false claims in real time.  
- Integrates with fact-checking databases.  
- Delivers accessible alerts to enhance transparency and informed decision-making.  

---

## 🏆 Vision  
To foster critical thinking and encourage users to question and verify information, reducing the spread of misinformation while promoting a culture of trust and informed communication.  

---

Here’s a polished version of your **Target Audience** section for the README, structured for clarity and brevity:  

---

## 🎯 Target Audience  

### Industries & Use Cases  

| **Industry**                  | **Use Case**                                   | **Description**                                                                 | **Priority**    | **Future Extensions**                                                       |  
|-------------------------------|-----------------------------------------------|--------------------------------------------------------------------------------|-----------------|------------------------------------------------------------------------------|  
| **Broadcasts & Media**        | **Live News Reporting**                        | Ensure factual accuracy, avoid misinterpretation or anti-sentimental statements. | High            | Extend for scripted shows to cross-reference pre-approved content.          |  
| **Sports & Entertainment**    | **Live Event Coverage**                        | Fact-check claims, stats, and announcements during live broadcasts.             | Low             | -                                                                            |  
| **Talk Shows & Discussions**  | **Panel Discussions**                         | Verify statements in real-time to avoid misinterpretation.                      | Low             | -                                                                            |  
| **Journalism**                | **Field Reporting**                           | Provide on-ground verification for faster reporting accuracy.                   | High            | Integrate real-time fact-checking into editorial workflows.                 |  
|                               | **Editorial Decision-Making**                 | Offer fact-checked insights to teams before airing content.                     | High            | -                                                                            |  
| **Social Media & Streaming**  | **Live Stream Moderation**                    | Flag and alert moderators about misinformation during live user content.         | High            | -                                                                            |  
|                               | **Posts & Comments**                          | Verify authenticity of posts, threads, or comments with a browser plug-in.      | High            | -                                                                            |  
| **Government & Public Sector**| **Press Conferences**                         | Fact-check official statements to ensure accurate public messaging.             | Medium          | Prioritize critical topics during emergencies.                              |  
| **General Viewers**           | **News Consumers**                            | Empower viewers with tools for real-time fact-checking during live events.      | High            | -                                                                            |  
|                               | **Misinformation Reporting**                  | Enable viewers to report misinformation directly to broadcasters/platforms.     | Low             | -                                                                            |  

---

This table provides a clear and actionable overview for different audiences and their specific use cases.

Here’s a polished version of your **Technical Approach** and **User Interface/Interaction** sections, structured for readability and clarity:  

---

## 🔧 Technical Approach  
### Workflow of the Real-Time Misinformation Detection System  
![truthtell hackathon diagram (1)](https://github.com/user-attachments/assets/f2db9564-4c5a-4988-9d2c-4b388ef90d7c)


1. **Data Ingestion (Apache Kafka)**  
   - Live broadcast data is ingested in real time via Apache Kafka.  
   - Kafka ensures low-latency data transfer between the NLP pipeline and the dashboard.  

2. **Data Processing and NLP (Python, Spark Streaming, NLP Tools)**  
   - Data is pre-processed with Spark Streaming, cleaned, and tokenized.  
   - NLP models (e.g., Hugging Face Transformers with TensorFlow) analyze text for entities, sentiment, and misinformation patterns.  
   - Pre-trained models like BERT and GPT are fine-tuned on custom datasets for complex tasks such as sentiment analysis and context extraction.  

3. **Fact-Checking and Database Lookup (PostgreSQL, Fact-Checking APIs)**  
   - Claims are cross-referenced with databases (PostgreSQL/MongoDB) and verified through fact-checking APIs.  
   - Results, including confidence scores, are stored for retrieval and analysis.  

4. **Real-Time Dashboard (Plotly, D3.js, Dash, JavaScript)**  
   - A dynamic dashboard visualizes analyzed data, confidence scores, sources, and alerts.  
   - Interactive features enable broadcasters to respond to flagged content in real time.  

5. **Cloud Deployment and Scalability (AWS)**  
   - The system is hosted on AWS for scalability and real-time processing as user demand increases.  

---

## 🎨 User Interface & Interaction  

### Features:  
1. **Real-Time Alerts & Notifications**  
   - Flags claims with visual indicators (e.g., red for high misinformation probability, yellow for unclear, green for verified).  
   - Alerts include confidence scores and relevant sources for broadcaster review.  

2. **Deeper Insights**  
   - Provides users with insights into the causes, effects, and psychology behind misinformation.  
   - Offers explanations through key theories:  
     - **Rumor Theory**: Influence of ambiguity and anxiety.  
     - **Rhetorical Theory**: Examines belief structures around misinformation.  
     - **Third-Person Effect**: Studies collective rumor behavior.  
     - **Situational Crisis Communication Theory (SCCT)**: Government communication during crises.  
     - **Reputation Theory**: Cognitive biases in content evaluation.  

---

## 🧠 Exploring Determinants of Misinformation  

### 1. **Personal & Psychological Factors**  
   - Anxiety and uncertainty during crises.  
   - Confirmation bias favoring pre-held beliefs.  
   - Emotional attachment to topics or devices.  

### 2. **Source Characteristics**  
   - Credibility and appeal of the sender.  
   - Ambiguity and relevance of content timing.  

### 3. **Platform Features**  
   - Impact of likes, shares, and video formats.  
   - Simplified sharing options increasing spread.  

### 4. **Social & Contextual Factors**  
   - Cultural and ideological narratives.  
   - Peer influence and repetition from multiple sources.  
   - Differences in device usage (mobile vs. larger screens).  

---

