# NEW VERSION TO INSTALL IF YOU HAVE COMPATIBILITY ISSUES WITH RM MINI 3

# meta-broadlink
full control of your broadlink device through neeo and meta
https://www.youtube.com/watch?v=Ub8pFTeWAiU

## How to install
You need to use this driver with meta as well as a node-red flow.
Go to jac459/meta for instruction on how to install the meta.
Below instruction for the flow:

#### Go to your node-red instance create for the meta driver 
Generally it is something like http://192.168.50.115:1880/ ==> you need to replace 192.168.50.115 by the IP address of the device running meta and node-red).
#### On the page, click the burger icon on the top right of your screen and choose "palette"
#### Click on the install pane and search node-red-contrib-broadlink-control
#### Choose install
### Now you need to create the flow associated to the node (node-red is the sum of nodes and flows)
#### Go to the menu again (burger :-))  and choose import.
#### Click select a file to import
#### copy paste this into the filename: https://raw.githubusercontent.com/jac459/meta-broadlink/main/Broadlink-flow.json
#### Click import and drag and drop the schema somewhere in the page (make it looks good).
#### Click Deploy
Congratulation, you are done.
