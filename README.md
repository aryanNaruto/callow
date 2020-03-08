# Callow

Callow is an dead simple brute force tool for websites with simple structures.

> **Note:** *This project currentry only supports windows*

## Requirements

- Python 2.7.x
- Google Chrome
- [Chromedriver](http://chromedriver.chromium.org/)

Callow currently ships with ChromeDriver 80.0.3987.106 and hence supports Chrome 80 and quite possibly any future virsions.

If you want to use a different directory, simply change the CHROME_DRIVER_LOCATION variable inside the python file.

## Installation

- Clone the repo

```txt
git clone https://github.com/maximousblk/callow.git
```

- Install dependencies

```txt
pip2 install -r requirements.txt
```

## Options

```txt
~\workspace\repos\maximousblk\callow (master -> origin)
λ python main.py -h
Usage: main.py [options]

Options:
  -h, --help       show this help message and exit
  --site=WEBSITE   Target website (http/https only)
  --usel=USEL      Username input selector
  --psel=PSEL      Password input selector
  --lsel=LSEL      Submit button selector
  --user=USERNAME  Target username to attack
  --pass=PASSLIST  Password dictionary
```

dont worry if you run the tool without any options. You'll greeted with a wizard!

## How to use

1 Find a website with a login page
2 Inspect element to find the Selector of the username form
3 Do the same for the password field
4 The the login form
5 When Asked put in the username to brute force
6 Watch it go!

## To Do

- [ ] Make it Python 3 compatible
- [ ] Cross platform compatibility

For more, look into [issues](/issues/) and [projects](/projects/)...
