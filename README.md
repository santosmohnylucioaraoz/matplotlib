# matplotlib

## 1. Tipos de Gráficos en Matplotlib

### Matplotlib ofrece una amplia variedad de gráficos para visualizar datos. Algunos de los más comunes son:


## Gráficos de Línea: 
 - ### Útiles para mostrar tendencias a lo largo del tiempo.
~~~
import matplotlib.pyplot as plt

plt.plot(x, y)
plt.title('Gráfico de Línea')
plt.show()
~~~
![grafico-areas-apiladas-colores-matplotlib](https://github.com/user-attachments/assets/8a1d59d0-efd6-4d31-b179-f9b6bc71bae4)


## Gráficos de Barras: 
- ### Ideal para comparar diferentes categorías.
~~~
plt.bar(x, height)
plt.title('Gráfico de Barras')
plt.show()
~~~

## Gráficos de Dispersión (Scatter): 
- ### Útiles para observar la relación entre dos variables.
~~~
plt.scatter(x, y)
plt.title('Gráfico de Dispersión')
plt.show()
~~~

## Histogramas: 
- ### Muestran la distribución de un conjunto de datos.
~~~
plt.hist(data, bins=10)
plt.title('Histograma')
plt.show()
~~~

## Gráficos de Pastel (Pie): 
- ### Útiles para mostrar proporciones dentro de un todo.
~~~
plt.pie(sizes, labels=labels)
plt.title('Gráfico de Pastel')
plt.show()
~~~
# 2. Estilos para una Presentación Más Profesional

### Para que tus gráficos se vean más profesionales, puedes aplicar diferentes estilos y configuraciones:

### Uso de Estilos: Matplotlib ofrece varios estilos predefinidos. Puedes cambiar el estilo con:
~~~
plt.style.use('ggplot')  
~~~

## Personalización de Colores y Líneas: 
- ### Ajusta colores, grosores y tipos de líneas para que se adapten a tu presentación.
~~~
plt.plot(x, y, color='blue', linestyle='--', linewidth=2)
~~~

## Etiquetas y Títulos: 
- ### Siempre incluye etiquetas y títulos descriptivos.
~~~
plt.title('Título del Gráfico', fontsize=16)
plt.xlabel('Eje X', fontsize=12)
plt.ylabel('Eje Y', fontsize=12)
~~~

## Leyendas: 
- ### Incluye leyendas para ayudar a interpretar el gráfico.
~~~
plt.legend(['Serie 1', 'Serie 2'])
~~~

## Tamaño de la Figura: 
- ### Ajusta el tamaño de la figura para que se ajuste mejor a tu presentación.
~~~
plt.figure(figsize=(10, 5))
~~~

## Grid y Fondo: 
- ### Agregar una cuadrícula o cambiar el fondo puede mejorar la legibilidad.
~~~
plt.grid(True)
plt.gca().set_facecolor('lightgrey')
~~~
