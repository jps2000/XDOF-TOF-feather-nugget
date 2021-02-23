# XDOF-TOF-feather-nugget
Feather nugget (piggyback PCB)  with BNO080/BNO055 IMU BMP388 Baro and VL53L1X tof sensor

Small PCB that fits to feather interface. Tested with nrf52832 BLE4.2
Features
-	9DOF IMU BNO080 or BNO055 optional
-	BMP388  Sensor for height measurements
-	TOF sensor VL53L1X up to 4 meters
-	1 neopixel status LED
-	ON/ OFF toggle button for battery use; USB auto on, shtdown from controller
-	Fits inside the feather footprint

Open source hardware, producers and suggestions welcome

feather nrf52832:  To achieve lowest battery current in off it is recommendend to remove the 100k pullup on EN (R5) and to replace the MBR120 shottky diode (D5) by a SI diode (1N4148).
The housing (not for TOF sensors)  is 3D printed. The cover should be made of transparent or translucent materials Use four screws ,Flat head, stainless steel 16mm long 2.2 mm diameter
