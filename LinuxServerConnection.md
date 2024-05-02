# Accessing a linux server in a Network

## Requirements

- Both Servers must be in a same network
- SSH port i.e. 22 must be open on both servers
- we must have user account on both server

## Protocol
 
 We can use SSH protocol to connect two servers

 syntax of SSH

 ssh -i "Private_Key" username@hostname

 sssh -i "Ubuntu_key" ubuntu@172.31.23.11



## Steps

1. Create one EC2 instance from AWS Console

2. Connect Server from Terminal/PowerShell using ssh command

3. Create a file in linux server and copy the private key from local computer and save file on linux server1

4. Using ssh command connect server 2 from server 1

<style>
table {
  border-collapse: collapse;
}

td, th {
  border: 1px  solid blue;
}
</style> 

|Linux       |Windows        |
|---------   | ----------    |
|Opensource  | Free          |
|More Secure | Less Secure   |
|Commandline | Has GUI & CLI |

![Connection Diagram](Img1.png) 

[Click here for more details](https://google.com )


