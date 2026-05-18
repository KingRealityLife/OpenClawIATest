# IC25a-OpenClayYskills - Evaluando instalacion
Actividad 
🤖 Bot de Telegram con IA (Ubuntu + AWS + Ollama)

# 📌 Descripción

Este bot permite:
- Responder mensajes usando IA local
- Mostrar la hora actual (`/hora`)
- Consultar el clima por ciudad (`/clima`)

---

# 🚀 Tecnologías usadas

- Telegram Bot API  
- Node.js  
- Ollama (IA local)  
- Ubuntu Server (AWS EC2)  
- API de clima (wttr.in)

---

# ☁️ Instalación en AWS (Ubuntu)

## 1. Crear instancia EC2
- Sistema operativo: Ubuntu 22/24
- Tipo recomendado: t2.medium o superior
- Abrir puerto SSH (22
- 
![Creación de instancia](imagenes/Screenshot%202026-05-17%20220329.png)
---

## 2. Conexión SSH

```bash
ssh -i "tu-key.pem" ubuntu@IP_PUBLICA
