# Análisis nutricional y económico de productos de Mercadona

## Descripción del problema
En los supermercados hay una gran cantidad de productos y cada uno tiene unos valores nutricionales y precio. Esta información está distribuida entre los distintos productos y es complicado comparar productos por valores nutricionales y precio.
Entre los estudiantes es bastante común que al estar estudiando fuera de casa queremos mantener una dieta saludable intentando no gastar mucho dinero en la compra.
Sin embargo, muchos productos de gama fitness pueden tener un coste elevado y ni siquiera sabemos si realmente nos estan ofreciendo una mejora en cuanto a valores nutricionales por este alto precio que estamos pagando, ya que comparar manualmente sus características es costoso y requiere consultar muchos productos.
Por ello se plantea un sistema que recopile la información de productos de Mercadona y permita analizar la relación entre su precio y sus valores nutricionales. Así podremos identificar y comparar alimentos según indicadores como la cantidad de proteínas, calorías, grasas o hidratos de carbono que aportan con relación a su coste, facilitando encontrar alternativas con una buena relación nutricional/precio sin tener que analizar los productos uno a uno. 

## Datos disponibles
La información necesaria para realizar el análisis se obtendrá de la tienda online de Mercadona. La página contiene información de cada alimento (nombre, categoría, cantidad, precio...) además de la información nutricional asociada a los productos, por lo que esta se incorpora al análisis de cantidad de proteínas, hidratos de carbono, calorías y otros valores nutricionales.

## Lógica del problema
El problema consiste en poder comparar productos que pueden tener diferentes precios y características nutricionales. Para realizar una comparación será necesario normalizar las cantidades de los productos a unas mismas unidades. A partir de estos datos se podrán calcular diferentes indicadores que relacionen el precio con los valores nutricionales de cada producto (cantidad de proteínas por 100 gramos, cantidad de calorías por 100 gramos, precio por 100 gramos...).
Estos cálculos permitirán analizar productos y comparar sus características nutricionales y cuánto cuestan.

## Role-play
![Foto del role-play](docs/role-play/roleplay.jpeg)

## Configuración del repositorio 
- [Configuración del entorno](docs/configuracion/configuracion.md)