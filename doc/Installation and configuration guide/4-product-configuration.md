# 4. Product Configuration

##### Add new product to WHMCS

```
System Settings->Products/Services->Create a New Product
```

In the **Module settings** section, select the **"PUQ Business-VPN"** module

[![image-1666343550750.png](https://doc.puq.info/uploads/images/gallery/2022-10/scaled-1680-/image-1666343550750.png)](https://doc.puq.info/uploads/images/gallery/2022-10/image-1666343550750.png)

- **License key:** A pre-purchased license key for the **"PUQ Business-VPN"** module. For the module to work correctly, the key must be active
- **Interface for public IP:** Interface on the router on which the public IP address will be set
- **PPP Profile:** PPP secret profile on Mikrotik router

##### VPN users settings

- **Number of VPN users:** The number of VPN accounts that a client can create
- **Bandwidth Download:** Download bandwidth that will apply per VPN connection
- **Bandwidth Upload:** Upload bandwidth that will apply per VPN connection

##### Mikrotik configuration

- **Public IP on interface:** If checked, the module will automatically set the IP address on the interface in the Mikrotik router
- **NAT rules on public ip:** If checked, then the module will automatically make firewall rules that will make NAT, for Internet access of all connected VPN accounts of the client in the Mikrotik router
- **Firewall Accept Rules:** If checked, then the module automatically creates firewall rules that will allow traffic between VPN client accounts
- **Firewall Drop Rules:** If checked, then the module automatically creates firewall rules that will drop traffic between VPN client accounts and other private networks on the router

##### Basic settings

- **Description prefix:** The prefix that will appear in all descriptions that will be on the Mikrotik router
- **Service:** A service that will be available to a VPN user on a Mikrotik router
- **Support PPtP/Support L2TP:** If checked, it will be reflected in the client zone
- **L2TP IPSec PSK key:** it will be reflected in the client zone