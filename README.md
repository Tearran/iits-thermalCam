# its-i2cDevices
include these scripts for i2c devices

## Featured Scripts

- its_database.py 
  - sqlite3.db ~ A list of i2c [LKARS](https://www.lkars.com/) tested devices 
- [its_bmp280.py](https://gitlab.com/tearran/its_bmp280) - Temperature and barometric pressure __Updated__  

- its_amg8833.py - 8x8 IR camera ( aka: GridEye )
- its_mlx90614.py -  infrared thermometer
- its_mpu60xx.py - 6-axis Inertial measurement unit 
- its_pyWebApp.py - web app example 
  - Launches a simple web server
  - list apps folder files with the .py extension
  - displays list on localhost:8000

### its scripts
basic use:
  python3 its_{name}.py
## its_database.py
  ```bash
  python3 its_database.py
  ```
  ```bash
  python3 its_bmp280.py
  ```
  ```bash
  python3 its_pyWebApp.py
  ```
  etc...

### Tools
- [sqliteonline](https://sqliteonline.com/) - Playground
### Libraries
- [bmp280](https://github.com/Tearran/bmp280) - Weather Sensor
- [FaBo9AXIS-MPU9250-Python](https://github.com/FaBoPlatform/FaBo9AXIS-MPU9250-Python) - Inertial measurement sensor
- [Melopero_AMG8833](https://github.com/melopero/Melopero_AMG8833) - 8x8 ir camera ( aka grideye )
