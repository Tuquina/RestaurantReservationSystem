# RestaurantReservationSystem
Backend para el Sistema de Reservas de Restaurantes (SRR): Facilita la gestión avanzada de restaurantes y optimiza la experiencia de reserva. Incluye funcionalidades para el manejo de perfiles, mesas y menús. Desarrollado en .NET 6.


# Introducción
Este proyecto representa el backend del Sistema de Reservas de Restaurantes (SRR), una solución de software diseñada como una tesis universitaria. El sistema tiene como objetivo optimizar la gestión de restaurantes y proporcionar una experiencia de reserva eficiente y sencilla para los clientes.

# Tecnologías Utilizadas
.NET 6: Como marco de trabajo principal para el desarrollo del backend.
MySQL: Como sistema de gestión de bases de datos.
Swagger: Para generar una interfaz de usuario interactiva que documente y permita la interacción con la API.

#Arquitectura del Proyecto
El proyecto sigue una estructura multicapa que facilita la mantenibilidad y escalabilidad:

API Layer: Gestiona las solicitudes HTTP y las dirige a los servicios correspondientes.
Application Layer: Contiene la lógica de negocios y la comunicación entre la API y la capa de datos.
Core Layer: Define las entidades y las reglas de negocio.
Infrastructure Layer: Gestiona la persistencia de datos y la comunicación con sistemas externos.
Tests Layer: Incluye pruebas unitarias e integración para validar la funcionalidad del sistema.
