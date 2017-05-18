# Changing IMEI Number of a mobile phone using Mobile Uncle Tools
* Open Mobile Uncle Tools
* Grant root permission if not granted.
* Tap MTK Engineer Mode
* Go to connectivity and select CDS information
* Now select Radio Information
* Select Phone 1 or 2 to change IMEI no
* Then you will see `AT+` command prompt.
* Type 
	`AT+EGMR=1,7,"IMEI_NUMBER1"` for SIM 1
	`AT+EGMR=1,10,"IMEI_NUMBER2"` for SIM 2
* Push SEND AT COMMAND
* A notification message will be displayed saying AT command is Msend
* Restart mobile and the IMEI number will be changed.

## Trouble shooting
* If you get `command is not allowed in user build` error message, place a space between `AT+` and `EGMR` like `AT+ EGMR=1,7,"IMEI_NUM"`


