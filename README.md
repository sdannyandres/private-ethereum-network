# Private Ethereum Network

Utilidad Node.js para crear y administrar una **red Ethereum privada** con Geth (Clique PoA): crea directorios de red y de nodo, genera el génesis, inicializa el nodo y lo arranca con RPC/HTTP/IPC.

**Estado:** proyecto de aprendizaje, red de desarrollo.

## Uso
```bash
export GETH_PASSWORD="<contraseña-local>"
cd backend && npm install && node router-network.js
```
Requiere Geth instalado.

## Seguridad
La contraseña se pasa por variable de entorno. No usar esta configuración con fondos reales.
