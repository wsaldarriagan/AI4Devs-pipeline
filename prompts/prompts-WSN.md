# Conversación entre Usuario y LLM

---

## Usuario:
Requiero que analices el proyecto y me expliques qué tecnologías se usan

---

## Usuario:
que buenas practicas de desarrollo se manejan en el proyecto?

---

## Usuario:
ahora explicame que hace el proyecto

---

## Usuario:
ahora que entienes el proyecto, quiero que me ayudes a implementar lo siguiente:
"Ejercicio: Creando un Pipeline en GitHub Actions 🔴
🚨 La fecha límite es el domingo 09 de febrero a las 23:59 de tu hora local.
 
En este ejercicio vamos a trabajar en la creación de un pipeline en GitHub Actions que nos permitirá pasar unos tests de backend, generar un build y desplegar el backend en un EC2. El pipeline se disparará con un push a una rama con un Pull Request abierto.

0️⃣ Pre-requisitos:

Para este ejercicio usaremos la capa gratuita de AWS y Github Actions.

Por tanto, necesitamos tener preparadas ambas herramientas:

🔗AWS
🔗 Tutorial básico de github actions 
🔗 Añadir keys a github actions para desplegar automáticamente en AWS 
1️⃣ Descarga el repositorio base de Github
Apóyate en el repositorio base para este ejercicio:

AI4Devs-pipeline 🔗 https://github.com/LIDR-academy/AI4Devs-pipeline

2️⃣ Realiza el ejercicio
Tu misión en este ejercicio es crear un pipeline en GitHub Actions que, tras el trigger "push a una rama con un Pull Request abierto", siga los siguientes pasos:

Pase unos tests de backend.
Genere un build del backend.
Despliegue el backend en un EC2. 
Para ello, debes seguir estos pasos:

Configurar el workflow de GitHub Actions en un archivo .github/workflows/pipeline.yml.
Documentar los prompts utilizados para generar cada paso del pipeline:
Tests de backend.
Generación del build del backend.
Despliegue del backend en EC2.
Asegúrate de que el pipeline se dispare con un push a una rama con un Pull Request abierto.
3️⃣ Entrega el ejercicio
Esperamos tu entrega como un pull request en el repositorio que incluya:

Los cambios de configuración del pipeline en la carpeta .github/workflows.
Un fichero prompts-iniciales.md en la carpeta prompts que incluya los prompts utilizados para generar el pipeline.
Para ello, debes seguir los siguientes pasos una vez ya tengas el repositorio preparado como se ha explicado en el paso anterior:

Completar el ejercicio: rellenar el prompt y el código necesario.
Crear una nueva rama para tu entregable con el nombre pipeline-iniciales.
Hacer commit.
Git push.
En la interfaz de tu repositorio te saldrá un aviso arriba para hacer Pull Request. En caso de que falle, puedes enviar el proyecto en zip por correo a alvaro@lidr.co.
Si tienes dudas sobre el ejercicio, consúltalas en el grupo de WhatsApp para que podamos apoyarte lo más rápido posible y que otr@s compañer@s también la resuelvan.

Por último, no olvides añadir tus prompts en prompts.md dentro de la carpeta prompts.

¡A por ello!"

Ten en cuenta que:
1. ya tengo la instancia EC2 en AWS y tengo el archivo cnxEC2.pem local, detallame el plan de acción que debo seguir incluyendo los pasos a configurar en el repo de Github
2. ya tengo el repo lonado, de hecho es este al que tienes en el @Codebase 


---

## Usuario:
estoy haciendo el paso 2 y en el capitulo que mencionas hay dos opciones: Environment secrets y Repository secrets, cual debo seleccionar?

---

## Usuario:
referente a los secretos, como obtengo este EC2_HOST? y EC2_KEY es cargar el archivo que tengo local?

---

## Usuario:
en el requerimiento que tengo mencionan esto "Tu misión en este ejercicio es crear un pipeline en GitHub Actions que, tras el trigger "push a una rama con un Pull Request abierto"", no entiendo que debo hacer

---

## Usuario:
voy a crear la rama pipeline-wsn, que debo hacer despues de eso?

---

## Usuario:
tengo dudas antes de proceder, entonces quiero que me ayudes a recapitular.
Que Tengo:
*  un repositorio creado
* la configuracion de los secretos en el repo
* un proyecto local, donde adicione la info del .yml
* un archivo con los prompts, llamado prompts.md
dudas:
1. ¿Debo crear primero la rama pipelines-wsn, primero?
2. ¿posteriormente debo hacer un PR a esa rama?
3. ¿Como se integra esto con main?, ¿Debo hacer algo mas?

---

## Usuario:
como se el username del ec2 y la el parametro target?

---

## Usuario:
por ssh no me deja crear el archivo con ese comando, me dice que permisos denegados

---


