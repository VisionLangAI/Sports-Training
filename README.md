# Sports-Training

## Overview

This dataset contains 5000 synthetic records simulating athlete training sessions with detailed features related to demographics, training load, physiological measurements, performance metrics, injury history, recovery indicators, psychological states, and environmental factors. It is designed for research in sports analytics, especially for exploring **association rule mining** and **classification** techniques in the context of sports training, injury prediction, and athlete performance optimization.

## Dataset Features

| Feature Name              | Description                                                  | Data Type          |
|--------------------------|--------------------------------------------------------------|--------------------|
| Athlete_ID               | Unique identifier for each athlete                           | String             |
| Age                      | Age of athlete (years)                                        | Integer            |
| Gender                   | Athlete gender (Male/Female)                                 | Categorical        |
| Height_cm                | Height in centimeters                                        | Float              |
| Weight_kg                | Weight in kilograms                                         | Float              |
| Sport_Discipline         | Sport category (e.g., Football, Basketball, Athletics)       | Categorical        |
| Training_Session_Type    | Type of training session (Endurance, Strength, etc.)         | Categorical        |
| Session_Duration_min     | Duration of training session (minutes)                       | Integer            |
| Training_Intensity       | Intensity level (Low, Moderate, High, Very High)             | Categorical        |
| Session_RPE              | Rate of Perceived Exertion (6-20 scale)                       | Integer            |
| Training_Frequency_per_Week | Number of training sessions per week                        | Integer            |
| Exercise_Type            | Specific exercise performed (Running, Weightlifting, etc.)   | Categorical        |
| Resting_Heart_Rate_bpm   | Resting heart rate (beats per minute)                         | Integer            |
| Avg_Heart_Rate_bpm       | Average heart rate during session (bpm)                       | Integer            |
| Max_Heart_Rate_bpm       | Maximum heart rate recorded (bpm)                             | Integer            |
| VO2max_ml_per_kg_min     | Maximal oxygen uptake (ml/kg/min)                             | Float              |
| Blood_Lactate_mmol_L     | Blood lactate concentration (mmol/L)                          | Float              |
| Muscle_O2_Saturation_%   | Muscle oxygen saturation percentage                           | Float              |
| Blood_Pressure_sys       | Systolic blood pressure (mm Hg)                               | Integer            |
| Blood_Pressure_dia       | Diastolic blood pressure (mm Hg)                              | Integer            |
| Speed_m_per_s            | Average speed (meters per second)                             | Float              |
| Agility_score            | Agility test score (arbitrary scale)                          | Float              |
| Power_output_watts       | Power output during exercise (watts)                          | Float              |
| Jump_Height_cm           | Vertical jump height (cm)                                     | Float              |
| Sprint_Time_s            | Sprint time (seconds)                                         | Float              |
| Strength_max_kg          | Maximal strength measure (kg)                                 | Float              |
| Skill_Execution_Score    | Skill performance score (percentage or scale)                 | Float              |
| Perceived_Exertion_RPE   | Athlete-reported exertion (6-20 scale)                        | Integer            |
| Sleep_Quality_Score      | Sleep quality rating (1-10 scale)                             | Integer            |
| Sleep_Duration_hr        | Hours of sleep                                               | Float              |
| Muscle_Soreness_Score    | Muscle soreness rating (0-10 scale)                           | Integer            |
| Recovery_Time_hr         | Recovery time between sessions (hours)                        | Float              |
| Cortisol_Level_ng_per_mL | Cortisol hormone level (ng/mL)                                | Float              |
| Creatine_Kinase_U_per_L  | Creatine kinase enzyme level (U/L)                            | Float              |
| Previous_Injury          | Injury history indicator (0 = No, 1 = Yes)                   | Integer (binary)   |
| Injury_Type              | Type of injury (if any)                                       | Categorical        |
| Injury_Severity_Score    | Injury severity scale (0-10)                                  | Integer            |
| Recovery_Stage           | Recovery phase (None, Acute, Rehabilitation, Return to Play) | Categorical        |
| Mood_State_Score         | Athlete’s mood rating (1-10)                                  | Integer            |
| Stress_Level_Score       | Stress level rating (1-10)                                    | Integer            |
| Motivation_Score         | Motivation level rating (1-10)                                | Integer            |
| Training_Environment     | Environment type (Indoor or Outdoor)                          | Categorical        |
| Temperature_C            | Training environment temperature (°C)                         | Float              |
| Humidity_%               | Training environment humidity (%)                             | Integer            |

## Usage Notes

- The dataset is only used for research and educational purposes.
- All records are unique, with randomized but realistic values reflecting typical sports training scenarios.
- This dataset is suitable for data mining, association rule mining, classification, clustering, and predictive modeling in sports science and athlete monitoring.
- Some features are subjective (e.g., RPE, mood), which may introduce variability typical of real-world data.


