# Proyecto de AWS Amplify - Sistema de Manejo de Inventario y Órdenes

Bienvenido al repositorio educativo del proyecto de AWS Amplify para el manejo de inventario y órdenes de productos. Este proyecto tiene como objetivo proporcionar una introducción práctica y educativa a las capacidades de AWS Amplify para el desarrollo del backend que puede servir tanto a una aplicacion movil como a un portal web.

## Descripción del Proyecto

El sistema de manejo de inventario y órdenes es un backend que simula las operaciones básicas de un sistema de gestión de inventario. Permite recibir peticiones desde el frontend para realizar las siguientes acciones:

1. **Gestión de Productos:** Agregar, editar y eliminar productos del inventario.

2. **Órdenes de Productos:** Crear y gestionar órdenes de productos.

3. **Autenticación de Usuarios:** Los usuarios pueden registrarse, iniciar sesión y gestionar sus propias órdenes.

## Tecnologías Utilizadas

El proyecto utiliza las siguientes tecnologías y servicios de AWS:

- **Amplify:** Para la gestión de backend sin servidor.

- **GraphQL:** Para la comunicación eficiente entre el frontend y el backend.

- **Amazon DynamoDB:** Base de datos NoSQL para almacenar información sobre productos y órdenes.

- **AWS Cognito:** Para la gestión de identidades y autenticación de usuarios.

## Configuración del Proyecto

### Prerrequisitos

- Node.js y npm instalados en su máquina.
- Instalar la CLI de AWS y Amplify
- Cuenta de AWS con permisos para crear servicios de Amplify, DynamoDB y Cognito.

### Pasos de Configuración

1. **Clonar el Repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repo.git
   cd nombre-del-repo
