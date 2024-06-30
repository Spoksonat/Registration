# Códigos de registro de imágenes para Centro de Control de Cáncer (Bogotá)

En este repositorio se encuentran una variedad de cuadernos de Jupyter usados para realizar registro (alineamiento) de imágenes usando transformaciones afines con el fin de
analizar mapas de dosis obtenidos en el Centro de Control de Cáncer (CCC) en Bogotá.

## Tabla de Contenidos

- [Acerca del Proyecto](#acerca-del-proyecto)
- [Uso](#uso)
- [Contribuyendo](#contribuyendo)
- [Licencia](#licencia)
- [Contacto](#contacto)
- [Agradecimientos](#agradecimientos)

## Acerca del Proyecto

En este repositorio puede encontrar una variedad de cuadernos de Jupyter que fueron usados para hacer registro (alineamiento) y cuantificación de mapas de dosis obtenidos en el CCC. 
En la primera parte de los cuadernos de Jupyter, se hace uso de la librería SimpleITKde Python para realizar las transformaciones afines a una imagen de dosis, tomando como referencia otra similar. 
Al final, se hace uso de la librería pymedphys para hacer cuantificación de las imágenes registradas usando el coeficiente Gamma. 

## Uso

Solo deben abrir los cuadernos de Jupyter que deseen, ejecutarlos y observar los resultados. El cuaderno de Jupyter más importante es [Affine3_prime.ipynb](Registration/Affine3_prime.ipynb).

## Contribuyendo

Las contribuciones son lo que hace que la comunidad de código abierto sea un lugar increíble para aprender, inspirar y crear. **Cualquier contribución que hagas es muy apreciada**.

1. Haz un Fork del Proyecto.
2. Crea una Rama para tu Funcionalidad (\`git checkout -b feature/FuncionalidadAsombrosa\`).
3. Realiza tus Cambios (\`git commit -m 'Añadir una Funcionalidad Asombrosa'\`).
4. Haz un Push a la Rama (\`git push origin feature/FuncionalidadAsombrosa\`).
5. Abre un Pull Request.

## Licencia

Distribuido bajo la Licencia MIT. Consulta [LICENSE.txt](LICENCE.txt) para más información.

## Contacto

Manuel Fernando Sánchez Alarcón  - mf.sanchez17@uniandes.edu.co

Enlace al Proyecto: [https://github.com/Spoksonat/Articulo-Phantoms/tree/main](https://github.com/Spoksonat/Articulo-Phantoms/tree/main)

## Agradecimientos

- [Paula Andrea Pardo Ramos](https://www.linkedin.com/in/paula-andrea-pardo-ramos/?originalSubdomain=co)
