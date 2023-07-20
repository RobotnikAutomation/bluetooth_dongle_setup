# bluetooth_dongle_setup
Script to change mac address of bluetooth dongles

# Usage
There are 2 ways of using this script. 
It takes the hostname and creates a unique mac address from it or it is also possible to set a robot name as an argument for the script. 

```
./bluetooth_setup.sh
```

e.g:
```
sudo ./bluetooth_setup.sh ther0-230112aa
```

In case the last letters are higher than f (for example ther0-230112ag), it is mandatory to use the second method and change slightly the hostname so it is compatible with hexadecimal digits. 
