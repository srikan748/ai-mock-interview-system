# AI-Mock Interview System

An AI-driven technical interview platform that evaluates candidates using:

- Speech recognition
- Computer vision
- Natural language processing
- Semantic answer scoring
- Hiring recommendation

Built for placement preparation and real-world technical interview simulation.

## Features

✅ 5 adaptive interview rounds (Easy → Medium → Hard)  
✅ Real-time webcam attention tracking using OpenCV  
✅ Speech-to-text answer capture using Faster Whisper  
✅ Semantic answer evaluation using Sentence Transformers  
✅ Confidence score calculation  
✅ Automated feedback generation  
✅ Final hiring recommendation  

---

## Tech Stack

- Python
- OpenCV
- Faster Whisper
- Sentence Transformers
- NumPy
- Pandas
- SoundDevice
- SoundFile

---

## Project Architecture

```text
Candidate Answer
       ↓
Microphone + Webcam
       ↓
Speech Recognition + Attention Tracking
       ↓
Semantic Answer Evaluation
       ↓
Technical + Confidence + Attention Scoring
       ↓
Final Hiring Recommendation
```

---

## Project Structure

```text
ai-mock-interview-system/
│
├── main.py
├── answer_scorer.py
├── feedback_generator.py
├── confidence_scorer.py
├── interview_dataset.csv
├── requirements.txt
├── README.md
├── screenshots/
└── sample_outputs/
```

---

## Installation

Clone the repository:

```bash
git clone <your-github-repo-url>
cd ai-mock-interview-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run Project

```bash
python main.py
```

---

## Sample Output

```text
ROUND 1/5

Question:
What is Singleton Pattern?

Your Answer:
Singleton pattern is a design pattern.

Correct Answer:
Singleton pattern is a creational design pattern that ensures only one instance of a class exists.

Round Score:
78.5 %

Feedback:
Good answer but missing implementation details.
```

---

## Key Highlights

- Designed multi-round adaptive interview logic
- Integrated real-time attention analysis
- Built semantic NLP-based answer scoring
- Generated automated hiring decisions

---

## Future Improvements

- GUI dashboard
- Cloud deployment
- Resume parsing
- Emotion detection
- Recruiter analytics dashboard

---

## Author

Gunji Srikanth
