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

## LED

| LED Number | Location | Description |
|------------|----------|-------------|
| 0          | interior | dami-3b-3   |
| 1          | interior | between dami-3b-2 et dami-3b-1 |
| 2          | interior | between dami-3b-1 et goun-3bplus-1 |
| 3          | interior | goun-3bplus-1 |
| 4          | interior | goun-3bplus-2 |
| 5          | interior | dami-3b-2 |
| 6          | interior | goun-3bplus-3 |
| 7          | interior | between goun-3bplus-3 et dami-3bplus-2 |
| 8          | exterior | between dami-3bplus-1 et goun-3bplus-1 |
| 9          | exterior | goun-3bplus-1 |
| 10         | exterior | goun-3bplus-2 |
| 11         | exterior | goun-3bplus-2 |
| 12         | exterior | enttr goun-3bplus-2 et dami-3b-1 |
| 13         | exterior | dami-3b-1 |
| 14         | exterior | between dami-3b-1 et dami-3b-2 |
| 15         | exterior | dami-3b-2 |
| 16         | exterior | between dami-3b-2 et goun-3bplus-3 |
| 17         | exterior | between goun-3bplus-3 et dami-3bplus-2 |
| 18         | exterior | dami-3bplus-2 |
| 19         | exterior | between dami-3bplus-2 et dami-3bplus-3 |
| 20         | exterior | dami-3bplus-3 |
| 21         | exterior | between dami-3bplus-3 et dami-3bplus-1 |
| 22         | exterior | dami-3bplus-1 |
| 23         | exterior | between dami-3bplus-1 et goun-3bplus-1 |

