# How to Configure a Point to Site VPN using Azure VPN Gateway

A Point to Site VPN  (P2S VPN) allow user to access resources on Azure when not connected to the company LAN. A P2S VPN access can be given also to external collaborator that are not allowed to connect to company LAN regardless of their working location.

## Overview

To deploy an P2S VPN using Azure VPN Gateway  must go trough the following steps: 

1. create VPN Gateway e Virtual Network
2. generate a root certificate e client certificate

3. configure VPN Gateway with root certificate

4. generate VPN client setup package

5. installa certificate on client
6. install VPN client

https://docs.microsoft.com/it-it/azure/vpn-gateway/vpn-gateway-howto-point-to-site-resource-manager-portal

https://docs.microsoft.com/it-it/azure/vpn-gateway/vpn-gateway-certificates-point-to-site

## Create VPN Gateway





## Generate Root Certificate



![new_sef_signed_root_certificate](new_sef_signed_root_certificate.png)

![run_certmgr](run_certmgr.png)

![](cert_in_cert_manager.png)



## Generate Client Certificate 

![generate client certificate](C:\gitrepos\emanbuc\Appunti_Qualita_e_Sicurezza_Informatica\azure_point2site_vpn\new_client_certificate.png)



## Install certificate on client

https://docs.microsoft.com/it-it/azure/vpn-gateway/point-to-site-how-to-vpn-client-install-azure-cert



## Install VPN Client

TBC.