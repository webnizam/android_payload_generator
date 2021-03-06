# Android Payload Generator

This tool helps to generate android payload with the help of QT5. It has a cool and simple graphical user interface which will make generating payload and listening for reverse shell easier.

![alt text](https://user-images.githubusercontent.com/14030703/82488946-e18afe80-9af1-11ea-9792-4b4a0e0aef03.png)

# Installation

Payload Generator requires [Qt5](https://doc.qt.io/qtforpython/) to run.

Install below dependencies.

```sh
pip3 install --user pyqt5  
sudo apt-get install python3-pyqt5  
sudo apt-get install pyqt5-dev-tools
sudo apt-get install qttools5-dev-tools
pip install -r requirements.txt
```

Run by

> python3 qt_payload_gen.py

### Plugins

Payload generator is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Plugin | Url |
| ------ | ------ |
| MSFVenom | https://github.com/rapid7/metasploit-framework/wiki/How-to-use-msfvenom |
| qt5 | https://doc.qt.io/qtforpython/ |
