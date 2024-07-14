# GPS Toll Based Simulation Using Python
This project simulates the movement of vehicles (a truck and a car) through a predefined set of toll gates within a 100km by 100km area using the SimPy discrete event simulation library. The project includes the implementation of dynamic toll calculation based on vehicle type and distance traveled through toll zones, and visualizes the results on a map using Folium.

# Features
1.Simulation of Vehicle Movement: Vehicles travel from a random start location to a random end location, passing through predefined toll gates.

2.Dynamic Toll Calculation: Toll rates are calculated based on the distance traveled through each toll zone and adjusted according to the vehicle type.

3.Balance Deduction: The balance of each user is updated as vehicles pass through toll gates.

4.Alerts: Alerts are generated when vehicles pass through toll gates.

5.Visualization: Routes and toll gates are visualized on an interactive Folium map.

6.Data Analysis: Visualization of data including distance traveled and remaining balance for each vehicle.
# Requirements
1.Python 3.7+

2.simpy

3.geopandas

4.shapely

5.pandas

6.matplotlib

7.folium

8.geopy
# Summary
This project simulates truck and car movements through toll gates within a 100km by 100km area using SimPy. It dynamically calculates toll charges based on distance and vehicle type, updates user balances, and alerts when vehicles pass toll gates. Visualization is provided through an interactive Folium map and data analysis charts using Matplotlib, showcasing distance traveled and remaining balances. It's designed to simulate real-time traffic scenarios, providing insights into toll road operations and user interactions in a controlled environment.
# Visualization
![graphs](https://github.com/user-attachments/assets/8d0fd57d-9053-43b0-bc0b-4d53223af6e6)
![Screenshot 2024-07-14 162634](https://github.com/user-attachments/assets/38339600-12fe-49e2-ba24-d7a841afffe5)


# License
This project is licensed under the MIT License.
