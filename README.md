# Temperature Data Analyzer

A simple and clean Python project that demonstrates how to use Object-Oriented Programming (OOP) to analyze temperature readings from a sensor.  
This project calculates:

- Average temperature  
- Highest temperature  
- Lowest temperature  
- Temperature range  

It uses a custom Python class (`TemperatureData`) to store sensor information and process its readings.

---

## 🚀 Features

- Object-oriented class for handling temperature data  
- Calculates key temperature statistics  
- Easy to extend and reuse  
- Clear and beginner-friendly Python code  

---

## 📌 Project Structure


---

## 🧠 How It Works

The project uses a class named **`TemperatureData`**, which:

1. Stores the **sensor name**  
2. Stores an array/list of **temperature readings**  
3. Provides methods to calculate:
   - Average temperature  
   - Highest and lowest readings  
   - Temperature range (max - min)  

---

## 📝 Example Code

```python
sensor_name = "East Forest Road Sensor"

sensor = TemperatureData(sensor_name, [75, 71, 68, 64, 88])

print(sensor.calculate_average_temp())       # Average
print(sensor.find_high_temp())               # Highest
print(sensor.find_low_temp())                # Lowest
print(sensor.find_temperature_range())       # Range
