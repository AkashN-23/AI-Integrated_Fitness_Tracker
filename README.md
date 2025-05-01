# AI-Integrated_Fitness_Tracker
AI-powered fitness tracker app that connects with wearable devices to monitor daily activities and workouts, analyze health data, and provide personalized recommendations, tips, and improvements for better fitness and lifestyle habits.

# Requirements
All the required libraries are provided in the text file "requirements.txt" 
 -->To install the required libraries use this command,
      #pip install -r requirements.txt

# AI-Integrated Fitness Tracker

A modular fitness tracking web app powered by AI and ML to provide personalized workouts, track user data, and correct form—all in one place.

---

## Project Modules

| Module            | Description |
|------------------|-------------|
| `ai_core`         | AI-powered insights and fitness tips |
| `form_checker`    | Posture and form correction using computer vision |
| `daily_tracker`   | Tracks daily workout, sleep, calories, and progress |
| `workout_planner` | Generates personalized daily workouts |
| `wearable_data`   | (Future) Syncs with wearable fitness devices |
| `extras`          | Blogs, diet tips, reminders, and more |

---

## Folder Structure

```bash
app/
├── __init__.py
├── routes.py
├── modules/
│   ├── ai_core/
│   ├── form_checker/
│   ├── daily_tracker/
│   ├── workout_planner/
│   ├── wearable_data/
│   └── extras/
└── utils/
requirements.txt
README.md
