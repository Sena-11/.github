# Guía de Contribución

¡Gracias por tu interés en contribuir a Sena 11! Para asegurarnos de que el proceso de colaboración sea sencillo y efectivo, hemos creado esta guía de contribución.

## Cómo Contribuir

1. **Fork el repositorio**: Haz clic en el botón "Fork" en la esquina superior derecha del repositorio para crear una copia en tu cuenta de GitHub.

2. **Clona tu fork a tu máquina local**:
   ```sh
   git clone https://github.com/tu-usuario/sena11.git
   cd sena11
   ```
3. **Crea una nueva rama**: Crea una nueva rama para tu característica o corrección.
   ```sh
   git checkout -b nombre-rama
   ```
4. **Realiza tus cambios**: Realiza los cambios necesarios en el código. Asegúrate de seguir los estándares de codificación y de incluir comentarios claros y descriptivos.
5. **Realiza commits con mensajes descriptivos**:
  ```sh
  git add .
  git commit -m "Descripción clara de los cambios realizados"
  ```
6. **Envía tus cambios al repositorio remoto**:
  ```sh
  git push origin nombre-rama
  ```
7. **Abre una Pull Request**: Ve al repositorio original y abre una nueva Pull Request. Describe los cambios realizados y por qué son necesarios.

## Estándares de Codificación
  - **Calidad del Código**: Asegúrate de que tu código sea limpio y legible. Utiliza nombres de variables descriptivos y sigue los estándares de codificación del proyecto.
  - **Comentarios**: Incluye comentarios en tu código para explicar partes complejas o poco claras.
  - **Pruebas**: Si agregas una nueva característica, asegúrate de escribir pruebas para ella. Si corriges un error, agrega pruebas que verifiquen que el error ha sido corregido.

## Reporte de Errores
Si encuentras un error, por favor abre un issue en GitHub. Incluye tanta información como sea posible para ayudarnos a reproducir y solucionar el problema.
