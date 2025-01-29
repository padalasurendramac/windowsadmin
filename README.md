
# windowsadmin

------------------------------------------
##  Using powershell to enable the Telnet-client
     Install-WindowsFeature -name Telnet-Client
     
 ## same with cmd
 
    dism  /online /Enable-Feature /FeatureName:TelnetClient
    
    
## firewall panel open single commment
    firewall.cpl
   
## user account panel open single commend
    lusrmgr.msc
    
    
## networking  panel nic single command
     ncpa.cpl
    
## unistall app
    appwiz.cpl
     
###  device  management 
     devmgmt.msc
     
###  disk management
      diskmgmt.msc
      
### computer management command 
      compmgmt.msc
