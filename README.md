# XDOF-TOF-feather-nugget
Feather nugget (piggyback PCB)  with BNO080/BNO055 IMU BMP388 Baro and V53L1X tof sensor

Small PCB that fits to feather interface. Tested with nrf52832 BLE4.2
Features
-	9DOF IMU BNO080 or BNO055 optional
-	BMP388  Sensor for height measurements
-	TOF sensor VL53L1X up to 4 meters
-	1 neopixel status LED
-	ON/ OFF toggle button for battery use; USB auto on
-	Fits inside the feather footprint

Open source hardware, producer and suggestions welcome

feather nrf52832:  To achieve lowest battery current in off it is recommendend to remove the 100k pullup on EN (R5) and to replace the MBR120 shottky diode (D5) by a SI diode (1N4148).
