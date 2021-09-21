# pistats
simple pi statistics on 0.91 oled display using adfruit drives and codes

Make sure that i2c interface on raspberry pi is enabled.

```sudo raspi-config```

<img width="674" alt="CleanShot 2021-09-21 at 14 38 22@2x" src="https://user-images.githubusercontent.com/11728585/134112572-9e7af5e4-af4d-4191-aebc-97b47d20bd18.png">

<img width="644" alt="CleanShot 2021-09-21 at 14 38 42@2x" src="https://user-images.githubusercontent.com/11728585/134112539-f346f62b-7350-408e-965f-75f471910c13.png">


then install all the required software/libraries

```sudo apt install python3-pip```

```sudo pip3 install adafruit-circuitpython-ssd1306```

```sudo apt install python3-pil```

```sudo apt install -y python-smbus```

```sudo apt install -y i2c-tools```

```sudo pip3 install psutil```


execute pistat.py ```python3 pistat.py```

<img width="654" alt="CleanShot 2021-09-21 at 14 47 51@2x" src="https://user-images.githubusercontent.com/11728585/134113093-b4902ae4-78b3-427c-897d-f09b922ca426.png">


