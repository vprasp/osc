# osc
17.  Vdd
9.   Gnd
5.   Scl 
3.  , Sda
sudo raspi-config
    I2C enable
sudo apt-get install build-essential python-dev python-smbus git
git clone https://github.com/adafruit/Adafruit_Python_ADS1x15.git
cd Adafruit_Python_ADS1x15
sudo python setup.py install

cd examples
python simpletest.py
sudo apt-get install python-matplotlib
sudo pip install drawnow
sudo osci.py
