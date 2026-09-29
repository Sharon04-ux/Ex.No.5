# EXP 5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios

# NAME : SHARON ARULBHARATHI J F
# REG NO : 212224100056
# Aim:To compare different prompting techniques and evaluate their effectiveness in solving real-world engineering problems by using a problem selected from a student's 3rd-year or final-year project work. 


## Project Title

AI-Based Real-Time Suspicious Activity Detection Using CCTV

## Problem Statement

Traditional CCTV surveillance requires continuous human monitoring, which can be difficult and time-consuming. The proposed engineering project aims to develop an AI-based system that automatically detects suspicious human activities from CCTV video and generates an alert for security personnel.

Selected Engineering Scenario

Scenario:
Design an AI-based real-time system that can detect suspicious human activities from CCTV surveillance video and generate an alert when suspicious behavior is identified.

The system should use computer vision and deep learning techniques to detect people, analyze their movements over time, classify activities, and generate alerts.

## Algorithm
Select a genuine engineering problem from the 3rd-year or final-year project.
Define the problem clearly and identify its major engineering requirements.
Create a simple base/naïve prompt without using advanced prompting techniques.
Generate and record the AI response.
Rewrite the same engineering problem using at least four different prompting techniques.
Generate and record the AI response for each improved prompt.
Compare the responses based on:
Relevance
Accuracy
Completeness
Clarity
Feasibility
Usefulness
Assign scores to each response.
Analyze how different prompting techniques affect the AI-generated solutions.
Select the most effective prompting technique.
Create a refined final prompt using the selected technique.
Validate the final AI-generated solution against the actual engineering requirements.
Record the observations and prepare the final result.

## Prompt
1. Naïve / Base Prompt

Technique: Basic prompting

How can I detect suspicious activities using CCTV cameras and AI?
Output

Suspicious activities can be detected using artificial intelligence and computer vision. CCTV video can be processed using an object detection model such as YOLO to identify people and objects. A deep learning model can analyze movements over time to identify suspicious behavior. When suspicious activity is detected, the system can generate an alert for security personnel.

2. Straightforward Prompt

Technique: Straightforward prompting

Suggest a method to detect suspicious human activities from CCTV
video using artificial intelligence.

Explain the main steps involved in detecting the activity and
generating an alert.
Output

A suitable approach is to process CCTV video using computer vision and deep learning. First, the video is divided into frames. An object detection model such as YOLO can be used to detect people in each frame. The movement of detected people can then be analyzed over multiple frames using a temporal model such as GRU or LSTM. The activity can be classified as normal or suspicious. If suspicious activity is detected, the system can generate an alert.

Pipeline:
CCTV Video → Frame Extraction → Person Detection → Feature Extraction → Temporal Analysis → Activity Classification → Alert

3. Role-Based Prompt

Technique: Role prompting

Act as an experienced AI and computer vision engineer.

Design a practical solution for detecting suspicious human activities
from real-time CCTV footage.

Consider:
- Person detection
- Object tracking
- Temporal activity analysis
- Deep learning
- Real-time processing
- Alert generation

Explain the proposed architecture, models, processing steps, and
implementation considerations.
Output

A practical solution can combine object detection, tracking, and temporal activity recognition. CCTV frames can be processed using YOLO to detect people. An object tracking algorithm can then track each person across consecutive frames.

Movement features can be extracted from the tracked objects and passed to a GRU or LSTM model. The temporal model can classify the sequence as normal or suspicious activity.

When suspicious activity is detected above a predefined confidence threshold, an alert can be sent to security personnel.

Architecture:
CCTV → Frame Processing → YOLO Detection → Object Tracking → Feature Extraction → GRU/LSTM → Activity Classification → Alert System

4. Constraint-Based Prompt

Technique: Constraint-based prompting

Design an AI-based real-time suspicious activity detection system
using CCTV footage.

The system must satisfy the following constraints:

1. It must operate in real time.
2. It must detect and track people.
3. It must distinguish normal and suspicious activities.
4. It must generate an alert when suspicious activity is detected.
5. It should use deep learning.
6. It should minimize false-positive alerts.
7. It should be feasible using commonly available hardware.

Provide:
- System architecture
- Recommended models
- Processing pipeline
- Dataset requirements
- Methods for reducing false positives
- Real-time implementation considerations
Output

A feasible system architecture is:

CCTV Camera → Video Stream → Frame Processing → YOLO Person Detection → Object Tracking → Temporal Feature Extraction → GRU/LSTM Activity Classification → Thresholding → Alert

YOLO can be used for real-time person detection, while object tracking maintains the identity of detected people across frames. A GRU or LSTM model can analyze temporal movement patterns to classify activities.

False positives can be reduced using confidence thresholds, multiple-frame confirmation, balanced training data, and appropriate datasets containing both normal and suspicious activities.

GPU acceleration and optimized models can be used to improve real-time performance.

5. Context-Based Prompt

Technique: Context-based prompting

You are designing a final-year engineering project for real-time
suspicious activity detection using CCTV.

Project context:
- CCTV cameras provide continuous surveillance video.
- The system must detect people from video frames.
- People need to be tracked across multiple frames.
- Suspicious behavior occurs over a sequence of frames rather than
  in a single image.
- YOLO is proposed for person detection.
- GRU is proposed for temporal activity analysis.
- An alert must be generated when suspicious activity is detected.

Based on this project context, design the complete processing
pipeline.

Explain:
1. System architecture
2. Role of each component
3. Data flow
4. Dataset requirements
5. Training process
6. Methods for reducing false positives
7. Real-time implementation requirements
8. Evaluation metrics

## Output

The proposed system consists of several stages:

1. CCTV Input: Continuous video is obtained from the surveillance camera.

2. Frame Processing: The video stream is divided into frames and prepared for model processing.

3. YOLO Detection: YOLO detects people in each frame.

4. Object Tracking: Detected people are tracked across consecutive frames.

5. Feature Extraction: Movement and positional information are collected from consecutive frames.

6. GRU Analysis: The GRU model analyzes the sequence of features and identifies temporal activity patterns.

7. Activity Classification: The activity is classified as normal or suspicious.

8. Alert Generation: If suspicious behavior exceeds a defined confidence threshold, an alert is generated.

Training requires a representative dataset containing normal and suspicious activities. False positives can be reduced through balanced datasets, appropriate confidence thresholds, temporal confirmation, and proper model evaluation.

## Output Comparison

The responses generated from the different prompts are compared below.

Prompting Technique	Response Quality	Technical Detail	Specificity	Practicality
Naïve / Base	Basic	Low	Low	Moderate
Straightforward	Good	Moderate	Moderate	Good
Role-Based	Very Good	High	High	Very Good
Constraint-Based	Excellent	High	High	Excellent
Context-Based	Excellent	Very High	Very High	Excellent
Evaluation Table

Each response can be evaluated on a 1–5 scale.

1 = Poor, 5 = Excellent

Technique	Relevance	Accuracy	Completeness	Clarity	Feasibility	Usefulness
Naïve / Base	3	3	2	4	3	2
Straightforward	4	4	3	4	4	4
Role-Based	5	4	5	5	4	5
Constraint-Based	5	5	5	5	5	5
Context-Based	5	5	5	5	5	5

Note: The scores above are sample evaluation scores. For your final submission, you can assign scores based on the actual responses generated during your experiment.

## Analysis and Observations
1. Naïve Prompt

The naïve prompt produced a general answer. It identified possible AI techniques but did not provide sufficient information about architecture, datasets, implementation, or system constraints.

2. Straightforward Prompt

The straightforward prompt produced a better response because it clearly specified what information was required. The response included a basic processing pipeline.

3. Role-Based Prompt

The role-based prompt produced a more technical response. Assigning the role of an AI and computer vision engineer encouraged the AI to provide architecture, model selection, tracking, and implementation considerations.

4. Constraint-Based Prompt

The constraint-based prompt produced a more practical engineering solution because specific requirements such as real-time operation, false-positive reduction, and hardware feasibility were included.

5. Context-Based Prompt

The context-based prompt produced a highly specific response because it provided details about the actual project, proposed models, expected system behavior, and required outputs.

## Overall Observation

The experiment shows that the quality of an AI-generated engineering solution depends strongly on how clearly the problem, context, constraints, role, and expected output are specified in the prompt.

The naïve prompt was useful for obtaining a quick general idea, but improved prompts provided more detailed and actionable engineering solutions.

Final Selected Prompting Technique

Context-Based + Constraint-Based Prompting

This combination was selected because it provides:

Project-specific information
Engineering requirements
System constraints
Expected outputs
Technical context
Implementation considerations

Therefore, it produces a more practical and useful engineering solution than a simple naïve prompt.

Refined / Final Prompt
Act as an experienced AI and computer vision engineer helping to
develop a final-year engineering project.

## Project Title:
AI-Based Real-Time Suspicious Activity Detection Using CCTV

## Problem:
Traditional CCTV surveillance requires continuous human monitoring.
The proposed system should automatically detect suspicious human
activities from CCTV footage and generate an alert for security
personnel.

## Project Context:
- CCTV provides continuous video.
- People must be detected in each frame.
- Detected people must be tracked across consecutive frames.
- Suspicious behavior must be analyzed over a sequence of frames.
- YOLO is proposed for person detection.
- GRU is proposed for temporal activity analysis.

## Engineering Requirements:
1. The system should operate in real time.
2. It should detect and track people accurately.
3. It should classify normal and suspicious activities.
4. It should generate an alert for suspicious activities.
5. False-positive alerts should be minimized.
6. The solution should be feasible using commonly available
   computing hardware.

## Provide:
1. Complete system architecture.
2. Detailed processing pipeline.
3. Role of each component.
4. Dataset and training requirements.
5. Model training and testing approach.
6. Methods to reduce false positives.
7. Real-time implementation considerations.
8. Suitable evaluation metrics.
9. Limitations of the proposed approach.
10. Possible future improvements.

Ensure that the solution is technically accurate, practical,
feasible, and suitable for a final-year engineering project.
Engineering Validation

The final AI-generated solution should be checked against the actual engineering requirements.

Validation Parameter	Expected Requirement	Validation
Person Detection	Detect people accurately	✓
Object Tracking	Track people across frames	✓
Activity Recognition	Identify normal/suspicious activities	✓
Real-Time Processing	Process CCTV with acceptable delay	✓
Alert Generation	Generate alert for suspicious activity	✓
False Positives	Minimize incorrect alerts	✓
Dataset	Include normal and suspicious activities	✓
Feasibility	Implementable with available hardware	✓
Evaluation	Use suitable performance metrics	✓

Important: The AI response should not be treated as automatically correct. Model choices, accuracy, dataset suitability, real-time performance, and feasibility should be verified through actual engineering testing.

## Result

The experiment was successfully carried out by applying different prompting techniques to the same real-world engineering problem. The comparison showed that naïve prompts produced general solutions, whereas straightforward, role-based, constraint-based, and context-based prompts produced increasingly detailed, relevant, and practical solutions.

Among the tested techniques, context-based prompting combined with engineering constraints provided the most useful solution because it incorporated the project's specific requirements and implementation conditions. Thus, the experiment demonstrates that effective prompt engineering can significantly improve the quality, accuracy, completeness, clarity, feasibility, and usefulness of AI-generated solutions for real-world engineering problems.
