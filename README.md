# 🍽️ K.R.I.S. – Restaurant Agent

K.R.I.S. (**K**nowledgeable **R**estaurant **I**ntelligent **S**ystem) es un agente inteligente diseñado para procesar datos de entrada proporcionados por el usuario, verificar disponibilidad y gestionar reservas de forma automática, reduciendo al mínimo la intervención requerida por parte del usuario.  

---

## 🚀 Características principales
- Procesa datos de entrada de forma sencilla.
- Verifica disponibilidad en tiempo real.
- Gestiona reservas automáticamente.
- Minimiza la intervención manual del usuario.

---

## 🛠️ Tecnologías utilizadas
- **Node.js**  
- **Express**  
- **Axios**  
- **AI Spine SDK**  
- **Jest** (para pruebas)  

---

## 📦 Instalación

Clona el repositorio y entra a la carpeta del proyecto:

```bash
git clone <repo_url>
cd <nombre_proyecto>
```

Instala las dependencias:

```bash
npm install
```

---

## ⚙️ Configuración

Antes de ejecutar el proyecto, crea un archivo `.env` en la raíz con las siguientes variables de entorno:

```env
# Puerto en el que corre el servidor
PORT=3000

# API Key de AI Spine
AI_SPINE_API_KEY=tu_api_key_aqui

# Endpoint de servicio de reservas
RESERVATION_API_URL=https://api.reservas.com

# Token de autenticación para el servicio de reservas
RESERVATION_API_TOKEN=tu_token_aqui
```

---

## ▶️ Ejecución

Ejecutar en modo desarrollo con la herramienta **AI Spine**:

```bash
npm run dev
```

Ejecutar el CLI (`cli.ts`):

```bash
npm run cli
```

---

## ✅ Tests

Para correr los tests:

```bash
npm test
```

---

## 📌 Notas
- Requiere **Node.js v16 o superior**.  
- Asegúrate de configurar correctamente las variables de entorno en el archivo `.env`.  
- El proyecto está pensado para integrarse fácilmente con servicios externos de reservas.  

---

👨‍💻 Desarrollado con ❤️ para automatizar la experiencia de reservas en restaurantes.

