# MÓDULOS PRODUCIDOS - EQUIPO ADEP-UNI - AÑO 2024

### [1.- Administrador Kubernetes](https://web-k8s-dev-adep.innlab.pe/#!/auth)  
Todos los microservicios que vamos a crear deben poder ser orquestados. Aquí hemos configurado el cluster donde se puede monitorear el microservicio asignado a cada una de las máquinas físicas que tenemos en INICTEL.

### [2.- Implementación y despliegue de api gateway para microservicios](https://api-passcheck-dev-adep.innlab.pe/actuator/health)  
Desde aquí accedemos a cada uno de los microservicios que hemos programado. Al hacer click pueden ver que el estado dice “up” lo que indica que en estos momentos los microservicios están implementados y listos para ser usados. Hemos incluido en la implementación de los microservicios, conectores de kafka y rabbitmq, lo cual además de habilitar la escalabilidad que necesitamos, permite que los microservicios utilicen diferentes tecnologías o lenguajes de programación, facilitando la interoperabilidad y el intercambio de información.

### [3.- SSO - Inicio de Sesión Único](https://digital-identity-adep.innlab.pe/)  
Aquí se ha configurado el Single Sign On, Necesario para simplificar la experiencia del usuario, mejorar la seguridad y facilitar la gestión de identidades,

### [4.- Open Search](https://web-observability-dev-adep.innlab.pe/)  
Nos sirve para implementar y desplegar agentes de observabilidad para los microservicios. Hemos elegido esta opción por ser de código abierto, veloz, altamente escalable y de alto rendimiento. Además, analiza y visualiza muy bien grandes volúmenes de datos.

