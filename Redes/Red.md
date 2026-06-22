# Red

## Configuracion de Red

Router ISP > Red Local "Casa" > Router Mikrotik > Switch Mikrotik > Proxmox vmbr0 / 192.168.0.254

Proxmox:

    VM 100: OPNsense
        1. WAN: vmbr0 / 192.168.0.253
        2. DMZ: vmbr10 / 10.10.10.1
        3. LAN-SRV: vmbr20 / 10.10.20.1
        4. LAB: vmbr30 /10.10.30.1

    VM 110 : Reverse Proxy
        10.10.10.10

    VM 120 : Docker/Servicios
        10.10.20.10

    VM 130 : NAS/PBS
        10.10.40.10

    VM 900 : Kali/Lab
        10.10.30.10
Kali
        192.168.0.200

DNS

        192.168.0.5

Host-Produccion

        192.168.0.199

## Plano de Red

## Datos Adicionales

Redirecciones:

    Pendiente

Otras configuraciones

    Pendiente

[Readme](/README.md)
