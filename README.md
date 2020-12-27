# Crestron-MyQ
This module works the MyQ API to control a garage door operner  

Inputs
    Init              - Pulse to initialize communications

    Open_*            - Pulse to open a garage door
    Close_*           - Pulse to close a garage door

Outputs
    Init_Success      - High if Initialization was successful, Otherwise Low
    Init_Failure      - High if Initialization failed, Otherwise Low

    Name_*$           - Name of a garage door as specified in the MyQ app.  This
                        can be used to display the name on a touch panel for the user
    Serial_Number_*$  - Unique serial number of the garage door for reference purposes
		
Paramteters
    Username$         - Account username
    Password$         - Account password
    Debug_Msg_Output  - Where to Send Debug Messages - None, Console, Error Log, or Both
