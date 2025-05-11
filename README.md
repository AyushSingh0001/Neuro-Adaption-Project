# Neuro-Adaption-Project

Project Overview:
The Neuro-Adaptation Therapy System (NATS) is an AI-powered mental health and cognitive monitoring tool that uses EEG brainwave data to assess a patient’s emotional and cognitive states in real time. It delivers personalized neurofeedback therapy based on this analysis and tracks progress over time.

Core Objectives:
1. Analyze real-time or simulated EEG data.

2. Detect mental states: Stressed, Focused, Fatigued, or Neutral.

3. Deliver adaptive feedback (light, sound, vibration) for therapy.

4. Track patient sessions and maintain profiles.

5. Visualize emotional state patterns using graphs and pie charts.

Core Functionalities:

1. Patient EEG Data Analysis:

Loads unique EEG data per patient.

Evaluates cognitive states using alpha, beta, and theta brainwave ratios.

2. Cognitive State Detection:

Classifies mental state as:

Stressed

Focused

Fatigued

Neutral

3. Neurofeedback Response Generation:

Suggests appropriate therapeutic responses based on the detected mental state.

4. Visual Reporting:

Displays:

Line Graph showing state transitions over time.

Pie Chart summarizing session-wise state distribution.

5. Patient Profile Management:

Maintains longitudinal mental health history in a JSON file (patients.json).

Appends new session data per patient with timestamps and results.

6. Session Summarization:

Outputs session duration, cycle-wise results, and total state counts.

7. CSV Export:

Stores each session’s data in an individual CSV file (therapy_output_{patient_id}.csv).

8. Interactive History Viewer:

Allows users to retrieve and view a patient’s past sessions and states.

Tech Stack Used:

1. Python

2. CSV & JSON (for EEG data and patient profiles)

3. Matplotlib (for graphs & charts)

4. Simulated EEG data (can be replaced by real EEG input)

5. Command-line interface

