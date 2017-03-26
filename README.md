# Bitsnet Login

This is a script for logging into the Captive Portal at BITS Goa

## Features

- Save your username and password once and login with ease
- Logout if necessary
- Use CLI or App 
- Use another username and password temporarily when out of data
- Update from the CLI with single command
- Easy install script

## Usage

Use the installed app from launcher

or

Use terminal to issue this command: ```bitsnet```

### Options

```
    -u USERNAME 
        Use specific username
    -p PASSWORD
        Specify a different password
    -o
        Logout
    -d
        Turn debug on
    -f
        Force login attempt
    -U
        Update program
    -w
        Force sending request to wireless
    -q
        Quiet mode. Don't send a notification
    -h
        Display help
```

## How to install

Fire up a terminal and issue these commands:
```
git clone https://github.com/OSDLabs/BitsnetLogin
cd BitsnetLogin
```
- Open bitsnetrc file and specify your username and password
- Save and close
```
./install
```

You can now login via terminal (```bitsnet```) or by launching the app

## Author
UTkarsh Maheshwari,  
**OSDLabs**

## License
GPL version 3
