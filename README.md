# DroidBruter
DroidBruter is an Android Phone PIN Bruteforcer Tool if you forgot your phone's PIN Code.

## Disclaimer
Please ask for permission first before attempting to bruteforce one of your friend or family's android phones.

I am not responsible for any damage or trouble caused by this script.

## Script Features
* Device Detection
   * Waits every 5 seconds to reconnect the device when disconnected
* 3-32 PIN Support
* Optimized PINs
   * Optimized PINs for 3, 4, 5, 6 digit PINs
* Editable PIN Cooldown
   * Puts 4 PINs (maxatmp) every 600 seconds (10 mins | maxatmpcd)

## Available Commands

```
  help                            Shows all DroidBruter commands
  start [<-opt>]                  Starts bruteforcing the phone with settings 
  exit                            Stops the server and exits DroidBruter      
  pinlength <length>              Changes the pin length
  maxatmp <int>                   Changes the max attempts for placing PINs   
  maxatmpcd <int>                 Sets the max attempts cooldown
  settings                        Shows current settings
  defpin <int>                    Changes starting PIN
  refresh                         Refreshes the DroidBruter Bruteforce Console
  toggleenter <-true | -false>    Presses enter after placing PIN
```
## Changing Pins
To change pins you can type ``pinlength 6`` in the DroidBruter command line to change pins to 6.

## DroidBruter Screenshots
![DroidBruter Screen](https://user-images.githubusercontent.com/53323309/126936418-ac0fa43f-8edd-4f68-ae4c-b045e8949140.png)
![DroidBruter Help](https://user-images.githubusercontent.com/53323309/126936476-ff27c801-9ac6-4432-9bcd-efb685982cd3.png)
