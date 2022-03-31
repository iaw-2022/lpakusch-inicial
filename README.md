# Proyecto Inicial

## Idea a Implementar

La idea a implementar es una página web para recibir informacion sobre enfermedades especificas (p.e. hipertensión, sobrepeso, diabetes) y recomendaciones para platos que deberías o no deberias comer con esta enfermedad ( para hipertensión p.e. platos con poca sal, diabetes platos con poca azucar..). 
El/La dueño de una pagina así podria ser una clinica o una empresa de seguro. Con una pagina con mucha información oficial podrían evitar consultas (clinica) y costos (seguro), si los clientes siguien los recomendaciones y comen más saludable.
En el primer paso, el enfoque de las comidas serían platos tipicos de Argentina.


## Diagrama ER

![image](https://user-images.githubusercontent.com/72938499/161144270-4bef2ba9-2aa5-443d-931b-85e145554817.png)

## Actualizaciones a los datos

Inicialmente solo hay una persona que puede cambiar los datos, un/a administrador/a del seguro/clinica, que puede cambiar los siguientes datos:


•	ABM de comidas


•	ABM de pacientes


•	ABM de otras profesionales


•	ABM de recomendaciones

En un paso mas avanzado durante el proyecto las modificaciones serán dependiendo de la profesion especial:


•	Los nutricionistas cambian los datos de las comidas


•	Los medicos cambian los datos de las pacientes


•	Los administradores pueden crear nuevos nutricionistas/medicos


## Información del Servicio Web

Para los usuarios no logueados en el sitio, la informacion de la pagina web que está disponible es: 


•	Las enfermedades con su definición/explicación (adicional quizas con una API a videos de explicación en youtube) 


•	las recomendaciones de platos dependiendo de la enfermedad

Los usuarios pueden ver sus datos personales.



## Visualización y Acceso a la Información

La informacion es visualisada en tres columnas/menus/buttons, una para cada enfermedad. Abajo de las columnas hay informacion sobre la enfermedad. Con click en el menu/button,el usuario puede acceder a las recommendaciones de platos y más informacion (sintomas, consecuencias p.e.).
Un usuario/cliente que es registrado va a ver su enfermedad subrayada por color.

![image](https://user-images.githubusercontent.com/72938499/161144390-e5096a9a-b246-4a3e-a6f5-7c2338574d20.png)


