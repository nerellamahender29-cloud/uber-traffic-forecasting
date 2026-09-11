# Predictive Model for Hourly Traffic Forecasting - Uber Data
Hyderabad | 48,120 records

## Data
- Traffic: Dataset_Uber_Traffic.csv - 4 junctions
- Weather: Open-Meteo API - temp, rain, humidity, wind
- Events: Holidays + IPL + Concerts

## Integration
Merged on DateTime. Final file: traffic_final.csv (48,120 x 11)

## Quality
- 0 duplicates
- 12 rain values filled with 0
- Scaled with StandardScaler

## Reports
/research folder has fare effect report
