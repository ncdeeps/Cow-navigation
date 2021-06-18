# Cow-navigation

# About the data
- To measure the movement of a cow, the collars are equipped with a GPS module (Global
Positioning System) and an IMU (Inertial Measurement Unit).
- The IMU outputs a ‘heading’ value, a compass bearing denoting which way the cow’s head
is facing.
- The GPS unit provides a latitude and longitude, tracking the position of the cow, specifically
its head. When the cow is walking, the direction of movement, the GPS heading, is
determined by calculating the bearing between subsequent points.
- Data has been collected from 14 cows while walking down the raceway, a 5 m wide fenced
pathway that cows walk down to go to the milking shed. In this case the raceway is
straight and aligned with North, i.e. a bearing of 0 o (360 o ). The following fields were
sampled at a nominal sampling rate of 1 Hz:
- The timestamp of the data point
- Serial number – the unique identifier for a collar
- Latitude and longitude – the cow’s location
- Heading – the bearing the cow is facing, measured from the IMU
- GPS heading – the direction (bearing) of the cow’s movement
- GPS speed – the speed of the cow in m/s


# Objective
- The assumption has been made that cows face straight ahead while walking. We would
like to investigate whether this is a reasonable assumption, to understand how a cow could
be guided along a path.
