# 3. Add server (router Mikrotik) in WHMCS

#####  [Order now](https://puqcloud.com/index.php?rp=/store/whmcs-module-business-vpn) | [Dowload](https://panel.puqcloud.com/link.php?id=33) | [Forum](https://panel.puqcloud.com/link.php?id=39)

### Add a new server to the system WHMCS.

Login to Your WHMCS panel and create new server in WHMCS (*System Settings-&gt;Products/Services-&gt;Servers*)

[![image-1663142713076.png](https://doc.puq.info/uploads/images/gallery/2022-09/scaled-1680-/image-1663142713076.png)](https://doc.puq.info/uploads/images/gallery/2022-09/image-1663142713076.png)

```
System Settings->Servers->Add New Server
```

- Enter the correct **Name** and **Hostname**

**Name is just for Your convenience and You can put there anything You like ie: *Mygreat mikrotik routr***

>**You can choose whatever hostname You want. Valid entries look similar to: vpn.mydomain.com, ourgreatvpn.mydomain.net. You can also dedicate whole domain ie: myVPNservices.com if You like. The important thing is to resolve the choosen IP address of the Mikrotik router in DNS server for Your domain.** 

- In the **"Assigned IP Addresses field"**, enter a list of IP addresses that will be issued to users.

### The format in which you need to enter a list of public IP addresses and private subnets is as follows. 

To define the available pool of IP addresses, for each available IP number you should enter another line where the data is separated by the "|" separator. Each line with an IP number definition has the following structure:

>&lt;PUBLIC\_IP&gt;|&lt;MASK\_OF\_ PUBLIC\_NETWORK&gt;|&lt;PRIVATE\_NETWORK&gt;|&lt;MASK\_OF\_PRIVATE\_NETWORK&gt;

[![image-1666084404668.png](https://doc.puq.info/uploads/images/gallery/2022-10/scaled-1680-/image-1666084404668.png)](https://doc.puq.info/uploads/images/gallery/2022-10/image-1666084404668.png)

### Enter the correct data in the username and password field  
  


- In the **Server Details** section, select the "**PUQ Business-VPN**" module and enter the correct **username** and **password** for the  **Mikrotik**.
- To check, click the **"Test connection"** button

[![image-1666084894938.png](https://doc.puq.info/uploads/images/gallery/2022-10/scaled-1680-/image-1666084894938.png)](https://doc.puq.info/uploads/images/gallery/2022-10/image-1666084894938.png)
