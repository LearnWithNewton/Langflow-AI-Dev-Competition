# 🚀 👋 Welcome to the AI Devs Langflow Competition! 🏆 🇮🇳

Are you ready to showcase your AI skills and compete for amazing prizes? Join us for an exciting 3-week journey into the world of Langflow!

### 🏆 Competition Structure
1. 📅 Duration : 3 weeks of challenges, 
1. each progressively more difficult!

### 🧠 Weekly Challenges
1. Week 1: Prompt Engineering
1. Week 2: RAG (Retrieval-Augmented Generation)
1. Week 3: Agents

You have one week to solve each challenge individually. Your submissions will be automatically evaluated, generating a score from 0 to 1 and contributing to a dynamic leaderboard!

### 💰 Prize Pool: ₹ 8,00,000

### 🏅 Weekly Prizes (Weeks 1-3)
1. ₹ 2,00,000 per week
1. Distributed among the top 50 scores

🎨 Content Creation Prize
₹ 60,000 awarded to the best content creators

🌟 Special Prizes
Best bug report
Best integration
Content creation (YouTube videos explaining competition projects)

🎯 Objectives
Skill Development: 
Learn to use Langflow effectively, from basics to advanced applications
Create your own AI projects using Langflow

Talent Spotting: 
Show off your skills and become a recognized "Langflow Wizard"
Potential recruitment opportunities for top performers

🔐 How to Join
Click on the ⛓️ emoji below this message to verify yourself
Gain access to exclusive competition channels
Get ready to compete and learn!

📢 Stay Tuned
More details about each week's challenge will be released soon. Follow the announcements channel for updates!

Are you ready to embark on this AI adventure? Let's innovate, create, and push the boundaries of what's possible with Langflow!

Good luck to all participants! 🍀💻

#IADevsIndia #Langflow #AICompetition

# 🚀 Exciting News! IA Devs India Week 1 Competition is Here! 🇮🇳

Get ready for an incredible challenge that will put your AI skills to the test! We're thrilled to announce the launch of IA Devs India Week 1, a competition that will showcase your **prompt engineering** prowess.

## 📅 Important Dates:
- Start Date: August 26, 2024
- Submission Deadline: September 1, 2024, 23:59 IST
- Results Announcement: September 2, 2024

## 🏆 Prizes:
We're offering a total prize pool of ₹2,00,000! Here's how it breaks down:

1st Place: ₹50,000
2nd Place: ₹40,000
3rd Place: ₹25,000
4th Place: ₹15,000
5th to 10th Place: ₹10,000 each
11th to 50th Place: Gift Cards

## 🎥 Content Creation Bonus:
We're giving away a total of ₹60,000 for the best content created during the competition! The top 10 content creators will be rewarded for their efforts. Share your journey, insights, or tutorials about the project, the competition, or Langflow in general. This is your chance to win while helping others learn!

## 💡 The Challenge:
Your task is to create a flow in Langflow that demonstrates advanced prompt engineering techniques. The flow should:

1. Process the provided "Prompt Engineering Guide" text file
2. Extract the content
3. Generate a concise yet comprehensive TLDR (Too Long; Didn't Read) summary

## 🎯 Evaluation Criteria:
1. Primary Metric: The generated TLDR will be evaluated against 10 questions for similarity. Your summary should be comprehensive enough to answer these questions accurately.
2. Secondary Metric: The number of tokens in the generated answer will be used as a tiebreaker. Shorter, more concise summaries that still capture all necessary information will be favored.

## 📊 Judging Process:
- We'll use the LangWatch component to track and evaluate your submissions.
- At the end of the submission period, we'll run evaluations on the LangWatch traces to determine the winners based on the above criteria.

## 📝 How to Submit:
1. Create your flow in Langflow, focusing on innovative prompt engineering techniques
2. Use the LangWatch component provided in the template flow.
3. Run your flow using the provided "Prompt_Engineering_Guide_EN" file
4. The LangWatch trace generated is your official submission

### 🔍 Tips:
- Experiment with advanced prompt engineering techniques such as few-shot learning, chain-of-thought prompting, or other methods to improve your summary's quality and conciseness.
- Consider the trade-off between comprehensiveness and brevity in your summary.
- Test your summary against potential questions to ensure it captures the most crucial information.

Remember, this challenge is not just about summarization, but about showcasing your prompt engineering skills to create the most effective and efficient prompts for this task!

### 📌 Remember:
- The LangWatch trace is your official submission
- Make sure to include your correct details in the LangWatch component for identification

### 🏷️ Don't forget to use the hashtags #langflow  #IADevsIndia when sharing your progress or content!

## 💳 Prize Distribution:
Cash prizes will be distributed via bank transfer. Gift cards will be awarded for some positions as well.

Are you ready to showcase your prompt engineering skills and compete for amazing prizes? Join us for IA Devs India Week 1 and let's push the boundaries of AI together! 

Good luck to all participants! 🍀💻

# 🚀 AI Devs India Week 2 Challenge: RAG-based Q&A System

## 🎯 Objective
Create a question-answering system based on the attached book, using the RAG (Retrieval-Augmented Generation) methodology. The system should be capable of answering questions about the book's content accurately and relevantly.

## 📊 Evaluation Methodology
1. Evaluation will be conducted using Langwatch and RAGAS evaluator.
2. Responses will be compared to an answer key, using the following evaluation metrics:
   - All submissions must be made through the provided evaluation flow.
   - Ragas Answer Correctness (correctness of the answer relative to the expected evaluation)

3. Participants will receive access to a dataset with 10 questions and answers to test their system.
4. Final validation will occur on a dataset with DIFFERENT questions, thus forcing participants to create a system that generalizes well to previously unseen questions.
5. An evaluation component (Langwatch Evaluator) will be provided, which must be plugged into all participants' flows, as this will also be used by the challenge submission flow. When running the Langwatch Evaluator and completing the test submission, it will provide an access link to view your test submission.
6. The submission evaluation flow will be made available on Saturday and will work as follows:
   - Users will place their flow JSON in the evaluation component
   - Fill in the required data (registered email and identification number)
   - Submission will occur through this provided flow, instead of via a form
   - This flow will also return the evaluation URL for result verification

## 📋 Requirements
1. Input: A question about the content of the book "TRADITIONAL FOOD RECIPES from AYUSH SYSTEMS of MEDICINE".
2. Output: An answer generated by your system.
3. Components: Free choice, as long as it includes a chat input, a single chat output, and the Langwatch Evaluator component for sending evaluations.

## 📤 Submission
- All submissions must be made through the provided evaluation flow.
- Optional: Content Creation.
- Project submission can occur multiple times per participant. Only the last submission will be considered.

## 📅 Important Dates
- September 4th, 2024: Opening of Challenge 2 on Crowdcast
- September 12, 2024: [Live session](https://crowdcast.io/c/27zlw9c9u17z) with the Langflow team
- September 15, 2024: Final submission deadline (23:59 IST)
- September 18, 2024: Announcement of winners and next challenge

## 🛠️ Installation and Configuration:
1. If you already have Python installed, start with pip:
   ```
   python -m pip install langflow
   ```
2. Refer to the official documentation for further instructions.

Good luck to all participants! 🍀💻

#AIDevsIndia #Langflow #AIChallenge #RAG

# 🚀 AI Devs India Week 3 Challenge: 

Coming Soon!