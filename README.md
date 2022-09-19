# Data_TR
Data  You will be given anonymised user gameplay data in the form of 3 csv files. 
Fields in the data are as described below: Gameplay_Data.csv 
1.contains following fields:      
    Uid: Alphanumeric unique Id assigned to user     
    Eventtime: DateTime on which user played the tournament     
    Entry_Fee: Entry Fee of tournament     
    Win_Loss: ‘W’ if the user won that particular tournament, ‘L’ otherwise     
    Winnings: How much money the user won in the tournament (0 for ‘L’)     
    Tournament_Type: Type of tournament user played (A / B / C / D)     
    Num_Players: Number of players that played in this tournament  
2.Wallet_Balance.csv contains following fields:      
    Uid: Alphanumeric unique Id assigned to user     
    Timestamp: DateTime at which user’s wallet balance is given    
    Wallet_Balance: User’s wallet balance at given time stamp  
3.Demographic.csv contains following fields:      
    Uid: Alphanumeric unique Id assigned to user     
    Installed_At: Timestamp at which user installed the app     
    Connection_Type: User’s internet connection type (Ex: Cellular / Dial Up)     
    Cpu_Type: Cpu type of device that the user is playing with     
    Network_Type: Network type in encoded form     
    Device_Manufacturer: Ex: Realme     
    ISP: Internet Service Provider. Ex: Airtel     
    Country     
    Country_Subdivision     
    City     
    Postal_Code     
    Language: Language that user has selected for gameplay     
    Device_Name     
    Device_Type
