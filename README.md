# Semillero de talento template para estudiantes

## Pasos previos

- Tener correo electronico.
- Foto profesional en formato png o jpg.
- Tener curriculum vitae en formato pdf.

## Como utilizar este template:

1. Clickear en "Fork".

2. Clickear "Crear fork".

3. Presionar enter cuando le pregunte algo.

4. Una vez en el repositorio clickear la tecla "." en el teclado.

5. En otra pestana pegar este prompt en chat gpt y volver a este documento una vez termines.

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


Asegurándote de retornarme al final de las preguntas, ese json en el mismo formato dado, simplemente que con mi información, siempre hablame en español, tammbien me gustaria que las preguntas sean simples y en caso de que puedas abundar un poco mas en mis respuestas lo hagas como por ejemplo en el about.
```

7. pegar el resultado en el archivo llamado CONFIG.json.

8. clickear la version de controles en el panel izquierdo.

9. colocar un mensaje y presionar subir cambios.

## Hacer despliegue en Vercel

1. En google ir a https://vercel.comj

2. Click en "Start deploying"

3. iniciar session con github y aceptar los mensajes que aparezcan.

4. Luego presionar instalar y aceptar los mensajes que aparezcan.

5. Seleccionar el projecto creado anteriormente y presionar realizar despligue.

6. Presionar el boton que dice "Deploy" y esperar a que termine el proceso.

7. Ir a la url recientemente creada.

### inspired on https://github.com/ccbikai/astro-aria
