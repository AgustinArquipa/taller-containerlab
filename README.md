# Ejemplo de topología de red LAN con Containerlab
---
<div align=center markdown>
<a href="https://codespaces.new/ernestosv73/taller-containerlab?quickstart=1">
<img src="https://gitlab.com/rdodin/pics/-/wikis/uploads/d78a6f9f6869b3ac3c286928dd52fa08/run_in_codespaces-v1.svg?sanitize=true" style="width:50%"/></a>

**[Run](https://codespaces.new/ernestosv73/taller-containerlab?quickstart=1) this lab in GitHub Codespaces for free**.  
[Learn more](https://containerlab.dev/manual/codespaces) about Containerlab for Codespaces.  
<small>Machine type: 2 vCPU · 8 GB RAM</small>
</div>

---
 La topología creada provee un laboratorio de pruebas para la configuración de una red LAN IPv4 que conecta un dispositivo Switch Arista cEOS y un Router CISCO IOL.
 
![Alt text](images/topo-lab-taller.png)

---
## Descripción de configuraciones
* Se configura DHCP Server para VLAN 10 y VLAN 11 en Switch Arista. Archivo de configuración inicial: myconfig.conf
* Archivo de configuración inicial Router Cisco: config.partial
---
## Conexión a los nodos
* `docker exec -it clab-labtaller-PCx /bin/bash`
* Obtener dirección IP ejecutando: `dhcpcd eth1`
  
