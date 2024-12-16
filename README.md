# Semillero de talento template para estudiantes

## Pasos previos

- Tener correo electronico.
- Foto profesional en formato png o jpg.
- Tener curriculum vitae en formato pdf.

## Como utilizar este template:

0. ir a github.com

1. Ir a https://github.com/BrayanMBeltre/semillero-de-talento-talk

2. Clickear en "Fork".

3. Clickear "Crear fork".

4. Una vez en el repositorio clickear la tecla "." en el teclado.

5. En otra pestana pegar este prompt en chat gpt.

```
Eres un estudiante de ingeniería de tics, haciendo fork de un template para una pagina personal, Hazme preguntas, una por una hasta completar los siguientes campos, en caso de las listas, si el usuario solo te da uno, síguele preguntándo hasta que termine.

{
  "personalInfo": {
    "firstName": "John",
    "lastName": "Doe",
    "about": "I'm a software student and developer from the Dominican Republic. I'm passionate about web development and design. I'm always looking for new opportunities to learn and grow.",
    "birthDate": "29-08-1999",
    "email": "john@doe.com",
    "github": "https://github.com/johndoe"
  },
  "skills": [
    "JS",
    "React",
    "Node",
    "HTML",
    "CSS",
    "SASS",
    "Bootstrap"
  ],
  "experiences": [
    {
      "dates": "December 2024",
      "role": "Participant",
      "company": "Oficina Gubernamental de la Tegnología de la Información y Comunicaciones",
      "description": "I participated in the 2024 'Semillero de talentos' program. creating a web application for the management of the institution's internal processes.",
      "logo": "/assets/images/experiences/didi.ico"
    }
  ],
  "projects": [
    {
      "name": "Personal website",
      "description": "This website was created to showcase my skills and projects.",
      "image": "/assets/images/projects/tempmail.best.png",
      "url": "https://github.com/johndoe"
    }
  ]
}

Asegurándote de retornarme al final de las preguntas, ese json en el mismo formato dado, simplemente que con mi información, siempre hablame en español
```

7. pegar el resultado en el archivo llamado CONFIG.json.

8. clickear la version de controles en el panel izquierdo.

9. colocar un mensaje y presionar subir cambios.

## Hacer despliegue en Vercel

1. ir a vercel.com

2. iniciar session con github y aceptar los mensajes que aparezcan.

3. Seleccionar el projecto creado anteriormente y presionar realizar despligue.

4. Ir a la url recientemente creada.

### inspired on https://github.com/ccbikai/astro-aria
