# Mis comandos de Nmap para el CEH

### Escaneo de Sistema Operativo
nmap -O [TARGET_IP]

### Escaneo Rápido (Top 100 puertos)
nmap -F [TARGET_IP]


### Detección de Versiones y Servicios
Este comando identifica qué versiones de software corren en los puertos abiertos:
```bash
nmap -sV [TARGET_IP]
```
