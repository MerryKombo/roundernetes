# roundernetes
Code to manage the aRGB fans in Roundernetes

## Fan

Code found here: https://www.waveshare.com/wiki/PI4-FAN-PWM
```bash
cd fan
python3 -m venv .
./bin/pip install gpiozero
./bin/pip install pigpio
./bin/pip3 install lgpio RPi.GPIO
./bin/pip3 install --upgrade lgpio
nohup ./bin/python3 temperature-pwm.py 2>&1 &
tail -f nohup.out
```
