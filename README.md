# 🍽️ Kris Restaurant Agent

Agente inteligente desarrollado para la empresa *Dataframe AI*, cuyo propósito es **optimizar procesos digitales en un hotel resort**, principalmente en la gestión de **reservas de restaurantes** y **check-in** en diferentes ámbitos.

---

## 📌 Problemática

El reto consiste en diseñar un agente que realice reservas de restaurantes basado en las preferencias y restricciones del usuario, considerando:

- Tipo de comida y restricciones alimenticias.  
- Ubicación actual y tiempo de traslado.  
- Posible hora de llegada.  
- Número de acompañantes.  
- Datos del restaurante (estilo, especialidades, menú, administración de la reserva).  

El agente debe:
- Gestionar la lista de espera.  
- Establecer el lugar donde se sentará el usuario.  
- Cancelar la reserva si el usuario no se presenta a la hora indicada.  

---

## 🎯 Objetivos

- Procesar los datos de entrada proporcionados por el usuario.  
- Realizar una **verificación de disponibilidad** antes de reservar.  
- Gestionar automáticamente la reserva, reduciendo al mínimo la intervención del usuario.  

---

## 🛠️ Diseño y Propuesta

El sistema de agentes sigue una arquitectura modular que incluye:

1. **Entrada de datos**: información del usuario y del restaurante.  
2. **Verificación de disponibilidad**: cruza datos con reservas existentes.  
3. **Gestión automática**: crea, modifica o cancela reservas.  
4. **Optimización de tiempos**: reduce tiempos de espera y mejora la experiencia del usuario.  

---

## 💻 Implementación

- Desarrollado en **Python**.  
- Uso de **agentes inteligentes** para la toma de decisiones.  
- Arquitectura extensible para integrar nuevos servicios (check-in, reservas de actividades, etc.).  

---

## 📂 Código

🔗 Repositorio en GitHub: [Kris-Restaurant-Agent](https://github.com/SebasBS1/Kris-Restaurant-Agent/tree/main)  

---

## 📖 Manual de Uso

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/SebasBS1/Kris-Restaurant-Agent.git
   cd Kris-Restaurant-Agent
   ```
2. Instalar dependencias (si aplica):
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecutar el agente:
   ```bash
   python main.py
   ```
4. Ingresar los datos solicitados (usuario y restaurante).  
5. El sistema realizará automáticamente la verificación y confirmación de la reserva.  

---

## ✅ Conclusiones

- El agente permite automatizar procesos repetitivos en un hotel resort.  
- Disminuye la intervención manual requerida del usuario.  
- Mejora la eficiencia en la gestión de reservas.  
- Puede escalarse a otros ámbitos como check-in, actividades recreativas y más.  

---

## 📚 Referencias

- **Documentación oficial del proyecto** (este repositorio).  
- Conceptos de **Agentes Inteligentes** en sistemas multi-agente.  
- *Dataframe AI* — Optimización de procesos digitales.  

---

👨‍💻 **Autores/Equipo de trabajo**:
- Eduardo Cárdenas Valadez (A00232432)
- Jonathan Uziel Medina Rodríguez (A01255048)
- Sebastián Blanchet Sanchez (A00227588)
- Araceli Ruiz Sánchez (A01255302)
- Rubén Alonso Castro Molina (A01255344)
*
📅 Proyecto académico / empresarial en curso  
