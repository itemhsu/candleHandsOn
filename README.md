# candleHandsOn
compile the candle for ubuntu 22.04

### Get the source
```
git clone https://github.com/Denvi/Candle.git
```
### Install QT5
```
sudo apt update
sudo apt install qt5-qmake qtbase5-dev
sudo apt install libqt5widgets5
sudo apt install libqt5network5
sudo apt install libqt5gui5
sudo apt install qtdeclarative5-dev  # For QML
sudo apt install qttools5-dev        # For additional tools
sudo apt install libqt5serialport5 libqt5serialport5-dev
```

### Config 
```
cd Candle
mkdir build
cmake ../
```

### Build
```
make -j8
```
