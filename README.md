# NetWorm


> Python network worm that spreads on the local network and gives the attacker control of these machines.

This code is not finished and works more like a "worm template" for you to get inspiration at the moment. 

You can bruteforce ssh servers, spread with USBs, etc..



## Downloading necessary libraries

```
pip install -r requirements.txt
```

## Executing

Windows & Linux:

```
python worm.py
```

## Compilation (.exe)

Targeted machines won´t probably have python and the required libraries installed. 
To run this code on other machines, you need to convert it into an executable.



To use it, simply write these commands in your terminal:
```
pip install pyinstaller

pyinstaller worm.py
```



## Contributing


1. Create your feature branch (`git checkout -b feature/fooBar`)
2. Commit your changes (`git commit -am 'Add some fooBar'`)
3. Push to the branch (`git push origin feature/fooBar`)
4. Create a new Pull Request

## Legal Advice
This repository and every script included in it is for educational and testing purposes only.
The owner nor any contributor is not responsible for your actions.

