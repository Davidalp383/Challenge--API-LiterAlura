# Challenge--API-LiterAlura📚📒

Una aplicación Java diseñada para ofrecer una experiencia integral de búsqueda literaria utilizando APIs externas. Construida con Spring Boot, LiterAlura permite a los usuarios buscar libros, autores y filtrar resultados por idioma u otros criterios. La aplicación utiliza la API de Gutendex para obtener datos literarios y Jackson para procesar JSON.  

## Funcionalidades 🌟  
- **Buscar libros por título:** Obtén información detallada sobre libros ingresando un título. La aplicación consulta la API de Gutendex para encontrar libros basados en el título proporcionado.  
- **Listar todos los libros:** Visualiza una colección completa de libros almacenados en el repositorio.  
- **Listar autores:** Muestra una lista de autores extraídos de los libros almacenados.  
- **Filtrar libros por idioma:** Busca libros disponibles en un idioma específico.  
- **Filtrar autores vivos en un año específico:** Encuentra autores que estuvieron vivos durante un año dado.  

## Requisitos ⚙️  
- Java 11 o superior  
- Spring Boot  
- Maven o Gradle  
- Jackson (para el procesamiento de JSON)  

## Instalación 🚀  
1. Clona el repositorio:  
   ```bash
   git clone https://github.com/Davidalp383/Challenge--API-LiterAlura.git
   ```  

2. Navega al directorio del proyecto:  
   ```bash
   cd Challenge--API-LiterAlura
   ```  

3. Instala las dependencias utilizando Maven o Gradle:  
   - **Maven:**  
     ```bash
     mvn install
     ```  
   - **Gradle:**  
     ```bash
     gradle build
     ```  

4. Ejecuta la aplicación:  
   - **Con Maven:**  
     ```bash
     mvn spring-boot:run
     ```  
   - **Con Gradle:**  
     ```bash
     gradle bootRun
     ```  

## Cómo funciona 🔧  
La aplicación se conecta a la API de Gutendex para recuperar datos sobre libros, autores e idiomas. La URL utilizada es:  
```java
private String urlBase = "https://gutendex.com/books?search=%20";
```  
Jackson se utiliza para analizar la respuesta JSON devuelta por la API y convertirla en objetos Java para su posterior procesamiento.  

## Uso 🖥️  
Una vez que la aplicación esté en ejecución, puedes interactuar con ella a través de la interfaz de línea de comandos. El menú te permitirá elegir entre diferentes opciones, como buscar libros por título, listar todos los libros o filtrar resultados por idioma.  

Por ejemplo, puedes buscar libros por su título. La aplicación enviará una solicitud a la API de Gutendex y mostrará los resultados, como el título del libro, el/los autor(es) y el/los idioma(s).  

## Cómo contribuir 🤝  
Siéntete libre de bifurcar el repositorio y enviar pull requests. Si encuentras algún problema o tienes sugerencias para mejorar, abre un issue en el repositorio de GitHub.  

## Licencia 📄  
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.  

## Agradecimientos 🙏  
- Spring Boot como framework para el backend  
- Jackson para el análisis de datos JSON  
- API de Gutendex por proporcionar acceso gratuito a una vasta colección de libros y datos literarios  
- APIs externas para datos de libros y autores  

¡Disfruta explorando el mundo de la literatura con LiterAlura! 😊  
```
