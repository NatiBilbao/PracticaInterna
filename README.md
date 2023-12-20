# Proyecto de Base de Datos para Préstamos de Dinero
Este repositorio contiene la documentación y la implementación de una base de datos diseñada para una pequeña empresa dedicada a préstamos de dinero. La base de datos está documentada utilizando Swagger, lo que facilita la comprensión de la estructura y operaciones disponibles.

## Descripción del Proyecto
La empresa de préstamos de dinero necesita gestionar de manera eficiente la información relacionada con sus clientes, préstamos y transacciones financieras. La base de datos proporciona una solución centralizada para almacenar y recuperar estos datos, permitiendo una administración efectiva de la información.

## Estructura de la Base de Datos
La base de datos está diseñada con las siguientes entidades principales:

Advisors: Almacena la información como, CI, nombre y apellido.
Group Loans: Almacena la información como, grupo, importe del préstamo, tipo de interés, fecha de inicio, fecha de finalización, estado y asesor
Individual Loans: Almacena la información como, miembro, préstamo colectivo, importe del préstamo individual, tipo de interés individual y saldo restante
Individual Payment Plans: Almacena la información como,  préstamo individual, número de cuota, fecha de vencimiento, importe total, importe del capital, importe de los intereses, fecha de pago, importe pagado y si es puntual 
Members: Almacena la información como, nombre, apellido, CI, ocupación, salario, estado civil, número de hijos, número de celular, dirección, email, cumpleaños, género y día de registro.
Savings Group: Almacena la información como, nombre del grupo, fecha de creación, líder, secretario y el tesorero. 

## Documentación Swagger
La documentación incluye detalles sobre los endpoints, los métodos HTTP permitidos, los parámetros de entrada y salida, así como ejemplos de solicitudes y respuestas para cada una de las 6 entidades.

## Tecnologías Utilizadas
Swagger: Utilizado para documentar la API de la base de datos.
Nest: Para construir el programa.

## Documentación
Manual de Usuario - ()

## Contribuciones
Las contribuciones son bienvenidas. Si encuentras problemas, tienes sugerencias de mejora o deseas agregar nuevas características, no dudes en abrir un problema o enviar una solicitud de extracción.
