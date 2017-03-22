Twitter Bot Bitcoin Development Running In Python

### Setting up bitcoin python module

## Installing the modules that are required

```
git clone https://github.com/laanwj/bitcoin-python
```

### Then run the following commands to install

```
cd bitcoin-python
sudo python setup.py build
sudo python setup.py install
```

```
git clone https://github.com/petertodd/python-bitcoinlib
```

### Then run the following commands to install

```
cd python-bitcoinlib
sudo python setup.py build
sudo python setup.py install
```

### Setting up one of the twitter modules

```
pip install twython
```

### Setting up the other twitter module

```
git clone https://github.com/tweepy/tweepy.git
cd tweepy
sudo python setup.py install
```

## You have to also execute the .py file like you would with a bash script

### sudo chmod +x ./block1.py ./first1.py

### Before running block1.py you will need to go into block1.py, and change the following code

```
os.system('python /home/pi/Music/first1.py')
```

### /home/pi/Music/first1.py is an example path, you will need to put in YOUR path location for first1.py

## command to put in bitcoin.conf
### blocknotify='location of the file' %s

