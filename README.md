# Trace-the-Ace
NLP Dialogue & Student Comprehension Assessment

**Trace the Ace** is an automated NLP assessment pipeline designed to evaluate student concept mastery following 1-on-1 tutoring sessions. By parsing raw multi-turn dialogue transcripts, the system extracts rich discourse structure and combines it with session metadata to predict post-session student comprehension.

---

## Project Overview

Understanding whether a student truly grasps a concept after a tutoring session is critical for personalized learning. **Trace the Ace** automates this assessment by:
1. Cleaning and merging utterance-level dialogue transcripts between tutors and students.
2. Annotating conversation flow, discourse acts, and pedagogical patterns using pre-trained transformer models via `edu-convokit`.
3. Training downstream classification models to predict student concept understanding post-session.
