# smart-doorlock
Keys are yesterday's tech, your smart home needs a smart door lock. This repository contains the code for making a smart door lock using Raspberry Pi.

A WLAN connected, servo-driven deadbolt actuator with IP camera stream that can be operated remotely using a smartphone.

## Schematic Diagram 

![Circuit Diagram](https://raw.githubusercontent.com/Vipul-Kumar/smart-doorlock/master/res/schematic_diagram.jpg)

**NOTE:** In place of external battery we can place a capacitor in the circuit , since I did not have a capacitor while making this project over a weekend, had to manage the power using a battery.
For more information on how to connect raspberry pi with a servo motor click [here.](https://circuitdigest.com/microcontroller-projects/raspberry-pi-servo-motor-control) 

# Future Features
Creating a multi-user feature, that allows multiple users to have access from same entry point and lock. Adding lock detection. Adding a lock counter. Add personal sounds, or alarms to each indvisual pass or fail attempt. Create more user friendly interface, adding greetings, salutations and overall more structual sense.




## Installations

Clone the project using the following command

```bash
git clone https://github.com/Vipul-Kumar/smart-doorlock.git
```
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install smart-doorlock.


```bash
cd smart-doorlock
```
It is best to contain a Python application within its own environment together with all of its dependencies. An environment can be best described (in simple terms) as an isolated location (a directory) where everything resides. For this purpose, a tool called virtualenv is used.


Run the following to install virtualenv and create an env using pip:
```bash
sudo pip install virtualenv
virtualenv .env
```

Activate and install the requirements for the project
```bash
source .env/bin/activate
pip install -r requirements.txt
```

## Usage

```bash
python app.py
```
Once the flask server is up you can open the browser and test the app on the url http://127.0.0.1:5000/

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Demo
https://youtu.be/g9kslgWyq4w

## License
[MIT](https://choosealicense.com/licenses/mit/)

