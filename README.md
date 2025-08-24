# Practo Learn 

**AI-Powered Personalized Learning System with Practical Mini-Projects**

Practo Learn is an intelligent learning platform that uses AI agents to assess your skills, create personalized learning paths, and track your progress through hands-on projects.

## Features

- **Smart Assessment**: AI agent evaluates your current skill level and learning style
- **Practical Projects**: Get 3-5 mini-projects tailored to your goals and experience
- **Progress Tracking**: Monitor your learning journey with visual progress indicators
- **Personalized Path**: Learning recommendations based on your specific needs
- **Real-World Focus**: Projects designed to build practical, applicable skills

## How It Works

### 1. Assessment Phase
The **Learner Assessment Agent** analyzes:
- Current skill level
- Knowledge gaps
- Learning preferences
- Available time commitment

### 2. Project Generation
The **Mentor Agent** creates:
- Practical mini-projects
- Step-by-step guidance
- Success criteria
- Learning resources

### 3. Progress Tracking
The **Progress Tracking Agent** provides:
- Milestone monitoring
- Struggle point identification
- Next challenge recommendations
- Motivation and encouragement

##  Installation

### Prerequisites
- Python 3.8+
- CrewAI library
- Gemini API access

### Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/practo-learn.git
   cd practo-learn
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up API credentials**
   ```bash
   # Add your Gemini API key to environment variables
   export GEMINI_API_KEY="your_api_key_here"
   ```

4. **Run the system**
   ```bash
   python src/practo_learn.py
   ```

##  Usage Example

```python
learning_session = {
    "topic": "Python loops",
    "level": "Beginner", 
    "goal": "Build web scraping skills",
    "time_commitment": "2 hours/week",
    "previous_experience": "Basic Python syntax"
}

result = learning_crew.kickoff(inputs=learning_session)
```

## Example Learning Topics

- **Programming**: Python, JavaScript, Data Structures
- **Web Development**: HTML/CSS, React, APIs
- **Data Science**: Pandas, Machine Learning, Visualization  
- **DevOps**: Docker, CI/CD, Cloud Services
- **Design**: UI/UX, Figma, Design Systems




---

**Ready to transform your learning journey? Star ⭐ this repo and let's build skills together!**
