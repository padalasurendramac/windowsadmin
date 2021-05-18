# windowsadmin
------------------------------------------
##  Using powershell to enable the Telnet-client
     Install-WindowsFeature -name Telnet-Client
     
 ## same with cmd
 
    dism  /online /Enable-Feature /FeatureName:TelnetClient
    
    
