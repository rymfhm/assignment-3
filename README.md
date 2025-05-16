# StudyBuddy - AI Educational Assistant

StudyBuddy is an AI-powered educational assistant designed to help students with their learning journey. It provides personalized study plans, generates quizzes, and offers guidance on various academic topics.

## Features

1. **Personalized Study Plans**
   - Creates customized study schedules based on subject and available time
   - Adapts to different difficulty levels (beginner, intermediate, advanced)
   - Provides time management recommendations

2. **Quiz Generation**
   - Generates practice questions on specific topics
   - Adjustable difficulty levels
   - Customizable number of questions

3. **Learning Support**
   - Explains complex topics in simple terms
   - Provides study techniques and memory aids
   - Offers guidance on homework and assignments
   - Encourages active learning and critical thinking

## Setup

1. Install dependencies:
   ```bash
   uv pip install -r requirements.txt
   ```

2. Create a `.env` file with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

3. Run the agent:
   ```bash
   python studybuddy.py
   ```

## Sample Interactions

### Creating a Study Plan
**User:** "I need a study plan for calculus. I have 10 hours available, and I'm at an intermediate level."

**StudyBuddy:** "I'll create a study plan for calculus at the intermediate level. Here's a structured plan for your 10 hours:

1. Review and Overview (2 hours)
   - Review basic calculus concepts
   - Identify areas needing more focus

2. Core Concepts (4 hours)
   - Differential calculus
   - Integral calculus
   - Applications

3. Practice and Application (3 hours)
   - Problem-solving exercises
   - Real-world applications

4. Review and Assessment (1 hour)
   - Practice tests
   - Self-assessment

Would you like me to break this down into a more detailed schedule?"

### Generating a Quiz
**User:** "Can you create a quiz about photosynthesis with 5 questions at an intermediate level?"

**StudyBuddy:** "I'll create a quiz on photosynthesis. Here's the structure:

Quiz on Photosynthesis (Intermediate level)
Number of Questions: 5

Instructions:
1. Read each question carefully
2. Write your answers in a separate document
3. Review your answers after completion

Would you like me to generate the actual questions now?"

## Learning Outcomes

By using StudyBuddy, students will:
- Develop better study habits and time management skills
- Gain a deeper understanding of complex topics
- Improve their problem-solving abilities
- Learn to approach assignments more effectively

## Ethical Guidelines

StudyBuddy adheres to the following principles:
- Never provides direct answers to assignments
- Encourages independent learning and critical thinking
- Maintains a supportive and encouraging tone
- Adapts to individual learning styles and needs

## Dependencies

- openai
- python-dotenv
