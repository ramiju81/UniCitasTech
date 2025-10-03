# 🎓 UniCitasTech  
## Plataforma de Agendamiento de Tutorías Universitarias

![Estado](https://img.shields.io/badge/🚀_En_Desarrollo-blue) 
![Licencia](https://img.shields.io/badge/Licencia-🔒_Privada-red)
![Firebase](https://img.shields.io/badge/Firebase-Firestore-orange)
![Gmail](https://img.shields.io/badge/Gmail_Corporativo-Activo-green)
![Responsive](https://img.shields.io/badge/Responsive-Android/iOS/PC-informational)

---

## 📋 Descripción del Sistema
**UniCitasTech** es un MVP diseñado para centralizar la gestión de citas entre estudiantes y tutores universitarios.  
Actualmente, el proceso es manual y propenso a errores (agenda en papel, llamadas o WhatsApp).  
Este sistema busca **automatizar y unificar** la reserva de tutorías, notificando al tutor por correo y bloqueando los horarios ya tomados.

---

## 🚀 Características principales
- Formulario de estudiante: nombre, celular/WhatsApp, carrera y semestre.  
- Selección de materia → muestra tutor/es asignados.  
- Calendario y horas disponibles (bloqueo en tiempo real con Firestore).  
- Correo automático al tutor con la información de la cita.  
- Interfaz responsive, usable desde PC o cualquier dispositivo móvil.  

---

## 📂 Estructura del proyecto
UniCitasTech/  
├── index.html # Interfaz principal  
├── data/  
│ └── config.json # Catálogo: carreras, materias, tutores y horarios  
└── static/  
├── css/  
│ └── styles.css # Estilos  
└── js/  
└── app.js # Lógica de reservas y validación


---

## 🛠 Stack Tecnológico
**Frontend:**
- HTML5, CSS3, JavaScript (vanilla)
- Responsive Design

**Base de Datos:**
- Firebase Firestore (bloqueo de horarios y reservas)

**Notificaciones:**
- Google Apps Script (Webhook)  
- Gmail corporativo (`noreply@womosolucions.com`)

---

## 🔍 Flujo de uso
1. El estudiante ingresa sus datos y selecciona materia.  
2. Se listan los tutores asignados a esa materia.  
3. Elige fecha y hora disponible (consultando slots configurados y reservas existentes).  
4. Se registra la cita en Firestore y se envía correo automático al tutor.  
5. El mismo horario queda bloqueado para otros estudiantes.  

---

## 🧩 Configuración necesaria
- **Firestore**: crear colección `reservations` con reglas que bloquean duplicados.  
- **Google Apps Script**: desplegar webhook para envío de correos.  
- **config.json**: parametrización inicial de carreras, materias, tutores y franjas horarias.  

---

## 📅 Objetivo del MVP
- Validar la experiencia de agendamiento en línea.  
- Reducir errores y duplicación de citas.  
- Reemplazar la agenda manual por un sistema digital centralizado.  

---

## 🛡️ Derechos de Autor
© 2025 **WoMo Soluciónˢ**. Todos los derechos reservados.  
Uso interno y confidencial. Prohibida su reproducción sin autorización.

---

## 📬 Contacto Corporativo
**Julián Alberto Ramírez**  
💻 Socio Fundador & Visionario Tecnológico
⚙️ Automatización | 🧩 Soluciones software | 💡 Innovador Tecnológico | 🔍 Apasionado por IA  
<img width="222" height="29" alt="Logo WSˢ" src="https://github.com/user-attachments/assets/24519130-f605-4762-a4f2-374c450f2b64" />  
🏢 **Soluciones Tecnológicas Avanzadas**  
<img width="150" height="150" alt="Logo" src="https://github.com/user-attachments/assets/09c23a95-e483-452e-880f-e7c90c222014" />  

---

## 💡 Notas Técnicas
Este sistema está diseñado para:  
✅ Digitalizar el agendamiento de tutorías universitarias  
✅ Bloquear horarios en tiempo real con Firestore  
✅ Enviar notificaciones confiables desde Gmail corporativo  

*"Tecnología que conecta estudiantes y tutores sin fricciones."*

---

## 📅 Control de Versiones
![Versión](https://img.shields.io/badge/Versión-1.0.0-blue) 
![Última Actualización](https://img.shields.io/badge/Actualizado-Oct_2025-green)

