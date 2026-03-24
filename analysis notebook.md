# Digital Behavior and Mental Well-being Analysis

## Objective
This project analyzes how digital behavior relates to mental well-being metrics such as focus, mood, and anxiety.

## Key points covered
- Screen Time & Anxiety
- Screen Time & Sleep
- Social Media & Anxiety
- Screen Time & Mood
- Screen Time & Focus
- Conclusion

## Overview of dataset:
500 observations across the following:

This is sample set taken from Kaggle.com, and shows data from 500 participants and observing relationship between mental health and digital behavior between 2020-2024. 

## Key features:
- daily_screen_time_min Total daily screen time (mobile + desktop, in minutes)
- num_app_switches Number of times the user switched between apps in a day
- sleep_hours Number of hours slept per day
- notification_count Number of notifications received by the user in a day
- social_media_time_min Time spent on social media platforms in minutes
- focus_score Self-reported focus score (1–10, where 1 is very distracted and 10 is highly focused)
- mood_score Self-reported mood score (1–10, where 1 is very poor mood and 10 is excellent mood)
- anxiety_level Self-reported anxiety level (1–10, where 1 is low anxiety and 10 is high anxiety)
- digital_wellbeing_score Calculated score based on focus, sleep, and anxiety levels; higher value represents better well-being

## 1. What's the coorelation between anxiety and screen time?

Little correlation between anxiety levels and daily screen time. This may be because there can be many external factors that contribute to anxiety levels.
Average correlation = 0.003
<img width="563" height="433" alt="image" src="https://github.com/user-attachments/assets/8c154d00-cdb4-42cd-851f-397d5dc8393b" />

## 2. Does daily screen time relate sleep hours?

There isn't a strong correlation between daily screen time and how much sleep participants' get.
Average correlation = 0.021

<img width="563" height="433" alt="image" src="https://github.com/user-attachments/assets/e15f039a-9584-42e9-89a0-d8f6827c4d46" />

## 3. Does higher social media usage relate to higher anxiety?

Moderate coorelation, anxiety does uptick with low social media usage and stays consistently high with higher use(not increasing, but steady)
Average correlation = 0.311

<img width="371" height="105" alt="Screenshot 2026-03-23 at 9 45 24 PM" src="https://github.com/user-attachments/assets/e37a9b0e-d5b8-4c12-997f-8e3ca6915e55" />

<img width="563" height="433" alt="image" src="https://github.com/user-attachments/assets/0c8710fd-d77a-45ae-bed9-7f7f19738bcb" />

## 4. Does more screen time = lower focus? 

There's a negative coorelation here, where increased screentime is moderately related to lower focus. However, when looking at this data vi:a bins, we can see there is a slight trend here where where focus slightly decreases as screen time increases.
Average correlation = -0.306

<img width="362" height="153" alt="Screenshot 2026-03-23 at 9 46 31 PM" src="https://github.com/user-attachments/assets/77ccb016-0682-4a96-ad9a-3f085be551b9" />

<img width="567" height="433" alt="image" src="https://github.com/user-attachments/assets/17976f4a-dc94-4484-8158-305625e23bb4" />

## 5. Do participants with more screen time have worse mood?

Mood score slightly increases with lower screen time. Beyond this threshold, mood score drops slightly and doesn't increase consistently with more screen time.

Average correlation = 0.073

<img width="365" height="152" alt="Screenshot 2026-03-23 at 9 47 17 PM" src="https://github.com/user-attachments/assets/12bbd8ed-4694-453c-bd61-0e7e07aa28fe" />

# Conclusion
My initial hypothesis was that the participants' mental health would be strongly influenced by their digital behavior. I expected that in increase in screen time and social media usage would lead to higher anxiety, worsened mood and decreased focus, but this analysis paints a more nuanced picture. Screen time has a moderate negative relationship with focus; higher usage associated with lower concentration. Social media usage also shows a moderate relationship with increased anxiety. Screentime has no meaningful effect on mood or overall anxiety levels, likely because there are several other factors that can effect aspects of mental health such as school, work or personal circumstances. 
Overall, while there is some impact on mental health and performance, it's not a conclusive outcome. I'm curious how more recent datasets differ from this conclusion.











