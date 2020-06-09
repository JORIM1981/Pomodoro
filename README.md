# 🍅 Tomato Clock

#### 09/06/2020
#### By **Jorim Midumbi Okong'o Opondo**

## Description
Tomato Clock is a simple command line pomodoro app written in Python,that utilizes the pomodoro technique to fight procrastination and help track time.

## Pomodoro technique

The pomodoro technique is a simple technique that helps individuals fight procrastination by using a simple timer.
The standard pomodoro timer is to work for 25 minutes and take a 5 minute break. You can read more about the technique [here](https://en.wikipedia.org/wiki/Pomodoro_Technique "Pomodoro Technique").

## Installation

Install python from https://www.python.org/

- Install via pip:
```
$ pip install tomato-clock
```

- Install via source code:
```
$ git clone https://github.com/JORIM1981/Pomodoro.git
$ cd Pomodoro
$ chmod +x tomato.py 
```

## How to use

- if you install via pip

```

$ tomato         # start a 25 minutes tomato clock + 5 minutes break
$ tomato -t      # start a 25 minutes tomato clock
$ tomato -t <n>  # start a <n> minutes tomato clock
$ tomato -b      # take a 5 minutes break
$ tomato -b <n>  # take a <n> minutes break
$ tomato -h      # help
```

- if you install via source code
```
$ ./tomato.py         # start a 25 minutes tomato clock + 5 minutes break
$ ./tomato.py -t      # start a 25 minutes tomato clock
$ ./tomato.py -t <n>  # start a <n> minutes tomato clock
$ ./tomato.py -b      # take a 5 minutes break
$ ./tomato.py -b <n>  # take a <n> minutes break
$ ./tomato.py -h      # help
```

## Terminal Output
```
🍅 tomato 25 minutes. Ctrl+C to exit
 🍅🍅---------------------------------------------- [8%] 23:4 ⏰ 
```

## Desktop Notification

- Ubuntu

`notify-send`

<img src="https://github.com/coolcode/tomato-clock/blob/master/img/screenshot-ubuntu.png?raw=true" alt="ubuntu-notification" width="300"/>



## Voice Notification
We use `say`(text-to-speech) for voice notification 

- Ubuntu

see this link: [say](http://manpages.ubuntu.com/manpages/trusty/man1/say.1.html)
```
sudo apt-get install gnustep-gui-runtime
```


## Package & Publish
```
pip install setuptools wheel twine
rm -rf dist && python setup.py sdist bdist_wheel
twine upload dist/*
```

## Technology used

* [Python3.8](https://www.python.org/)


## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information 

If you have any question or contributions, please email me at [okongo.midumbi.opondo@gmail.com]

## License:

- _MIT License:_[LICENSE MIT](./LICENSE)

- Copyright (c) 2020 **Jorim Midumbi Okongo Opondo**


