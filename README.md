# SemillasFund (Documentación)
# Tipografias
- titulos
  - Dosis
- parrafos
  - Playfair Display
# colores
  - Green-Darker
    - Hex #009458
    - RBG( 0 - 148 - 88 )
    - rgba(0, 148, 88, 1)
  - Green-Light
    - Hex #69BF97
    - RBG( 105 - 191 - 151 )
    - rgba(105, 191, 151, 1)
  - White
    -Hex #FFFFFF
    - RBG( 255 - 255 - 255)
    - rgba(255, 255, 255, 1)
 # Estructura Barra de Navegación y Header
 Mediante un grid y su propiedad grid-area se realizó la división de las columnas, tanto la lateral(aside) como la superior(header).

![image](https://user-images.githubusercontent.com/114504563/199037047-6fc5a2e7-afd1-4118-be18-eb69b69bf0b8.png)

 # Barra de Navegación Lateral
 Se realizó una división de contenido dentro de la barra para la inserción de dos figuras en la parte superior que formaran la estructura de un ícono de usuario como foto de perfil, mientras  que la sección inferior fue ocupada por una lista de opciones.

![image](https://user-images.githubusercontent.com/114504563/199038768-c84e7afa-a422-4e24-9317-09c1a4acdeee.png)

Las dos formas que se realizaron para dar contexto de ícono de usuario fueron hechas mediante la utilización de dos div contenidos en uno solo usando la propiedad border radius.

![image](https://user-images.githubusercontent.com/114504563/199039738-18f52b1a-2c5b-48bc-9023-01ca7f794086.png)

En la lista de la sección inferior se utilizó íconos de windows por su variedad y su facilidad de implementación.

![image](https://user-images.githubusercontent.com/114504563/199042002-22a1d905-061c-4794-accb-edff8aa86566.png)

 # Header
 En esta sección se uso una división de tres columnas para el ícono de la barra lateral, el título, y un mini apartado que simula el log out de una sesión de usuario.
 
 ![image](https://user-images.githubusercontent.com/114504563/199041585-edab6667-3aa3-4eb0-a517-b3472937defd.png)

 Al igual que en la barra lateral se utilizó un ícono de Windows, el cual fue embebido por una etiqueta "< p >".
 
 ![image](https://user-images.githubusercontent.com/114504563/199042850-c3b0d845-f25d-4b30-ad1d-a57e9def584d.png)
 
 # Responsive
 Para la implementación de la web responsive utilizamos un label que embebia el ícono izquierdo del header, el cual estaba enlazado mediante un for, a su vez este llevaba el  id de a un input checkbox, esta etiqueta se encontraba en la parte superior de la barra lateral.
 
 ![image](https://user-images.githubusercontent.com/114504563/199050082-e40b62ad-d621-44c7-a327-9a6ff72551b6.png)
 
 Checkbox:
 
 ![image](https://user-images.githubusercontent.com/114504563/199058102-11b0270f-ddbc-4ff8-9b5f-02df357fadd3.png)

 Al aplicar propiedades de Css como display: none, al accionar el checkbox(ícono izquierdo, Header), se ocultaba la barra lateral y el resto de contenido tomaba el campo sobrante.
 
 ![image](https://user-images.githubusercontent.com/114504563/199058974-155cc824-f31c-4e6a-87a6-824441d83bee.png)

Esta implementación se utiliza en las dos medidas responsive (768px y 320px).


