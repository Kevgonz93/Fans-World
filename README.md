# Fans World Project

Este repositorio actúa como el repositorio principal que vincula los proyectos del **Frontend** y **Backend** de la red social para fans del fútbol.

## 📂 Estructura del Proyecto

Este repositorio está compuesto por dos submódulos:

- **Frontend**: Contiene el código de la interfaz de usuario desarrollado con **Angular 17** y **TypeScript**.
- **Backend**: Contiene el código del servidor desarrollado con **NestJs**, **Prisma** y **JWT**.

---

### 🔗 Submódulos

Este repositorio utiliza **submódulos** para gestionar el código de los proyectos **Frontend** y **Backend** de manera independiente. Los submódulos son los siguientes:

| Submódulo    | Descripción                                                  | Enlace                                                                                                        |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------- |
| **Frontend** | El repositorio que gestiona el frontend de la aplicación.    | [Ver Repositorio Frontend](https://github.com/isdi-coders-2023/Kevin-Gonzales-Final-Project-202402-Mad-Front) |
| **Backend**  | El repositorio que gestiona la API y la lógica del servidor. | [Ver Repositorio Backend](https://github.com/isdi-coders-2023/Kevin-Gonzales-Final-Project-202402-Mad-Back)   |

---

## 🚀 Instalación

### 1. Clonar el Repositorio Principal

    git clone https://github.com/Kevgonz93/Fans-World
    cd Fans-World

### 2. Inicializar y Actualizar Submódulos

Después de clonar el repositorio, necesitarás inicializar y actualizar los submódulos para obtener el código de Frontend y Backend:

    git submodule update --init --recursive

### 3. Instalar Dependencias

#### Frontend

Ve a la carpeta del Frontend:

    cd Front

Instala las dependencias:

    npm install

Ejecuta el servidor

    npm start

#### Backend

Ve ala carpeta del Backend:

    cd ../Back

Installa las dependencias:

    npm install

Configura las variables de entorno necesarias (como las credenciales de la base de datos y el JWT).

Ejectuta el servidor de desarrollo:

    npm run start:dev

### 4. Acceder a la Aplicación

-     El Frontend debería estar corriendo en http://localhost:4200.
-     El Backend debería estar corriendo en http://localhost:3000.

## 🧪 Testing

Para ejecutar las pruebas automáticas de los proyectos:

- Frontend

  cd Front
  npm run test

- Backend

  cd ../Back
  npm run test

## 🤝 Contribución

Este repositorio está configurado para trabajar con los submódulos de Frontend y Backend de manera eficiente. Si deseas contribuir, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama para tu funcionalidad (git checkout -b nombre-rama).
3. Realiza los cambios y haz commit (git commit -am 'Descripción de cambios').
4. Haz push a tu rama (git push origin nombre-rama).
5. Crea un Pull Request.

## 📜 Licencia

Este proyecto está bajo Licencia MIT.
