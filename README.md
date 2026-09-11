# Uber Traffic Forecasting - Hyderabad

**Junction 1: LB Nagar area | RandomForest R2: 0.9650 | GradientBoosting R2: 0.9659 | Final Tuned R2: 0.9665 | MAE: 4.2**

Study of 48,120 hourly records from 4 junctions in Hyderabad (Nov 2015 - June 2017) to check effect of traffic on Uber business.

**What I did:**
- Joined Traffic + Weather (temp, rainfall, humidity) + Events (Diwali, IPL, holidays)
- Feature Engineering: hour, day_of_week, month, is_weekend, is_event, lag_1h, lag_24h
- Models: RandomForest, GradientBoosting (Best), LSTM concept
- Final Model R2: 0.9665

**Business Impact:**
- Peak hours 9-11 AM & 6-9 PM at LB Nagar area - 40% more demand but 18% cancellations
- Rain >2mm = 35% more jam, 50% more demand = surge 1.5x-2.2x
- Revenue up 12-15% with forecast model

Files: Dataset, Weather, Events, Final Model Notebook, Report
