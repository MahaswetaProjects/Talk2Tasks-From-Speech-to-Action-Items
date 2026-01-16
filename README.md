# Talk2Tasks-From-Speech-to-Action-Items


###  Project Overview

Talk2Tasks is an end-to-end AI system that converts raw meeting audio into structured, actionable insights. It automatically transcribes meetings, extracts action items and decisions, evaluates transcription quality, and visualizes key analytics to help teams track outcomes efficiently. This project demonstrates practical use of **speech recognition, NLP, data processing, and visualization** in a real-world business scenario.


##  Problem Statement

Meetings often result in:

* Missed action items
* Unclear ownership of tasks
* No structured summary
* Time wasted revisiting discussions

Manual note-taking is inconsistent and error-prone.

**Talk2Tasks solves this by automating meeting understanding.**


##  Key Features

*  Speech-to-Text transcription using Whisper
*  Clean and structured meeting transcripts
*  NLP-based extraction of:

  * Action items
  * Decisions
  * Task owners and deadlines
    
*  Transcription quality evaluation
*  Visual analytics for confidence scores and insights
*  Modular and scalable pipeline design


##  Tech Stack

* **Python**
* **Whisper** – Speech-to-Text
* **spaCy** – NLP extraction
* **Matplotlib** – Visualizations
* **FastAPI** (optional extension) – API layer


##  System Architecture

**Pipeline Flow:**

1. **Audio Input**
   Raw meeting audio files (simulated & real)

2. **Whisper STT**
   Converts speech into text transcripts

3. **Text Transcripts**
   Cleaned and stored transcripts for processing

4. **NLP Extraction (Actions & Decisions)**
   Identifies tasks, owners, deadlines, and decisions

5. **Quality Evaluation**
   Calculates transcription confidence scores

6. **Analytics & Visualization**
   Displays insights using charts and summaries


##  Visual Insights Included

* Transcription confidence per meeting
* Action item count distribution
* Decision frequency analysis
* Processing pipeline visualization

##  Use Cases

* Corporate meeting summarization
* Project status meetings
* Academic or research discussions
* Interview or discussion analysis
* Team productivity tracking


##  Future Enhancements

* Real-time transcription
* Speaker identification
* Meeting action reminders
* Web dashboard integration
* LLM-based summarization

