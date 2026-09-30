# ExpresoFast

Proyecto de gestión de envíos para la asignatura Desarrollo de Software IV.

## Estructura

- [`expresofast-backend/`](./expresofast-backend): API REST desarrollada con Spring Boot, Spring Data JPA y H2.
- [`expresofast-frontend/`](./expresofast-frontend): archivos de la interfaz web del proyecto.

## Requisitos

- Java 21
- Maven Wrapper incluido en el backend
- Navegador web moderno

## Ejecutar el backend

Desde la carpeta `expresofast-backend`:

### Windows

```powershell
.\mvnw.cmd spring-boot:run
```

### Linux o macOS

```bash
./mvnw spring-boot:run
```

La API quedará disponible en `http://localhost:8080`.

Para compilar y ejecutar las pruebas:

```bash
./mvnw clean test
```

En Windows se puede usar el equivalente `.\mvnw.cmd clean test`.

## Ejecutar el frontend

Abra [`expresofast-frontend/dashboard_paginado.html`](./expresofast-frontend/dashboard_paginado.html) en un navegador o sirva la carpeta con un servidor HTTP local. El frontend utiliza la API del backend en `http://localhost:8080`.
