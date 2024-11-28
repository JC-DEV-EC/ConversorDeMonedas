# Conversor de Monedas

![Estado del Proyecto](https://img.shields.io/badge/estado-finalizado-green.svg)
![Versión](https://img.shields.io/badge/versión-1.0.0-brightgreen.svg)
[![MIT License](https://img.shields.io/badge/licencia-MIT-blue.svg)](LICENSE)

**Conversor de Monedas** es una aplicación de consola que permite a los usuarios convertir entre diferentes monedas utilizando tasas de cambio en tiempo real. La aplicación soporta varias monedas y permite a los usuarios realizar conversiones rápidas desde la línea de comandos.

## 🚀 Descripción

Esta aplicación permite a los usuarios:

- **Convertir Monedas**: Ingresa el monto y selecciona la moneda de origen y la moneda destino.
- **Obtener el Tipo de Cambio**: La aplicación obtiene el tipo de cambio actual entre las monedas seleccionadas.
- **Visualizar Resultados**: Muestra el monto convertido junto con el tipo de cambio utilizado.

## 🛠️ Tecnologías Utilizadas

- **Java**: Lenguaje principal de desarrollo utilizado para implementar la lógica de la aplicación.
- **IDE**: Cualquier entorno de desarrollo integrado como **IntelliJ IDEA**, **Eclipse**, o **NetBeans** para escribir y ejecutar el código.
- **JDK (Java Development Kit)**: Necesario para compilar y ejecutar programas Java.
- **Scanner**: Clase de Java utilizada para la entrada de datos desde la consola.
- **API de Tasa de Cambio**: La aplicación obtiene tasas de cambio a través de una API externa (por ejemplo, API de tasas de cambio en tiempo real).
- **JSON**: Utilizado para procesar las respuestas de la API de tasas de cambio.

## 🏗️ Instalación

Para ejecutar este proyecto localmente, sigue estos pasos:

1. **Clona el repositorio**:

    ```bash
    git clone https://github.com/JC-DEV-EC/ConversorDeMonedas.git
    ```

2. **Navega al directorio del proyecto**:

    ```bash
    cd ConversorDeMonedas
    ```

3. **Compila y ejecuta el programa** usando tu IDE de Java favorito o desde la terminal:

    ```bash
    javac ui/MonedaConverter.java services/ExchangeRateService.java models/Currency.java
    java ui.MonedaConverter
    ```

## 🖥️ Uso

1. Al ejecutar la aplicación, se mostrará el menú principal.
2. Selecciona las monedas de origen y destino.
3. Ingresa el monto que deseas convertir.
4. La aplicación hará la conversión utilizando las tasas de cambio más recientes y te mostrará el monto convertido.
5. Si lo deseas, puedes realizar más conversiones o salir de la aplicación.

## 🔑 Estructura del Proyecto

- **ui**: Contiene la clase `MonedaConverter`, que gestiona la interfaz de usuario y el flujo principal de la aplicación.
- **models**: Incluye la clase `Currency`, que representa una moneda y sus características.
- **services**: Contiene la clase `ExchangeRateService`, que se encarga de obtener y procesar las tasas de cambio de la API.

## 🤝 Contribuciones

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/mi-feature`).
3. Realiza tus cambios y confirma (`git commit -m 'Agregué una nueva característica'`).
4. Envía un push a tu rama (`git push origin feature/mi-feature`).
5. Abre un Pull Request.

## 🙏 Agradecimientos

Este proyecto ha sido desarrollado como parte de un desafío personal para mejorar habilidades en Java.

## 👤 Autor

Este proyecto fue creado y es mantenido por [JC-DEV-EC](https://github.com/JC-DEV-EC).

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
