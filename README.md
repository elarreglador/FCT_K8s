# FCT_K8s

```
------------------------ CLUSTER -------------------------
|                                                        |
|                                                        |
|    --------------------- RACK 1 ---------------------  |
|   |                                                 |  |
|   |                                                 |  |
|   |   -------------------------------------------   |  |
|   |   |                                         |   |  |
|   |   -------------------------------------------   |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   ---------------------------------------------------  |
|                                                        |
|                                                        |
|   --------------------- RACK 2 ----------------------  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   |                                                 |  |
|   ---------------------------------------------------  |
|                                                        |
|                                                        |
----------------------------------------------------------

```

## Instalacion de sistema
Instalaremos Ubuntu server LTS, durante la instalacion prepararemos las particiones de este modo:

```
  5GB   |  .. Swap ..  |  .  |  Memoria virtual
  50GB  |  .. Ext4 ..  |  /  |  Sistema operativo
  120GB | sin formato  |  .  |  
  325GB | sin formato  |  .  |
```

tambien instalaremos el servidor SSH con acceso usuario/clave para poder acceder de forma remota

## IP estatica
