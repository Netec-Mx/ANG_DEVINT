# Práctica 7. Depuración de la aplicación de Angular usando Visual Studio Code

En este laboratorio usaremos las herramientas de depuración de código para válidar el funcionamiento y flujo de ejecución de una aplicación de Angular. 

## Objetivos de la práctica:
- Depurar el código de Angular.
- Usar el debug de Visual Studio.

## Duración aproximada:
- 30 minutos.

---

<div style="width: 400px;">
        <table width="50%">
            <tr>
                <td style="text-align: center;">
                    <a href="../Capitulo6/"><img src="../images/anterior.png" width="40px"></a>
                    <br>anterior
                </td>
                <td style="text-align: center;">
                   <a href="../README.md">Lista Laboratorios</a>
                </td>
<td style="text-align: center;">
                    <a href="../Capitulo8/"><img src="../images/siguiente.png" width="40px"></a>
                    <br>siguiente
                </td>
            </tr>
        </table>
</div>

---



## Diagrama
Al final de la práctica el alumno podrá observar el proceso de depuración que ofrece Visual Studio Code.

![alt text](../images/7/diagrama.png)


## Instrucciones
Paso 1. Abre cualquier aplicación de Angular en **Visual Studio Code**.

> **IMPORTANTE:** Este proceso que aprenderemos será útil para cualquier aplicación de Angular. Nos da la posibilidad de encontrar errores de cualquier flujo, incluso, nos permite entender el proceso de ejecución de nuestra aplicación. 

Paso 2. Dentro del proyecto de Angular vamos a agregar breakpoints. 

> **NOTA:** Los breakpoins son herramientas que permiten detener la ejecución de un programa en una línea específica de código durante la depuración. Esto permite que podamos inspeccionar variables, ver el flujo del programa y encontrar errores de manera más efectiva. 

Paso 3. Se recomienda agregar los breakpoints en puntos importantes de nuestro código, cómo por ejemplo: **variables dentro de un componente, funciones, servicios** y esto permitirá que podamos ver el flujo de ejecución de nuestro programa. 

Paso 4. Para este ejemplo utiliza la aplicación de **shop** que realizamos en el tema **3 y 4**. Agrega breakpoints en las variables que estan en los componentes: 

![alt text](../images/7/1.png)

Paso 5. Selecciona los puntos de interés dentro de tu aplicación. 

Paso 6. Después, selecciona la opción de depuración de **Visual Studio Code**.

![alt text](../images/7/2.png)

Paso 7. Inicia la depuración:

![alt text](../images/7/3.png)

Paso 8. Al iniciar la depuración nos abrirá el menú de depuración de VSCode, donde podremos controlar la ejecución de cada breakpoint.

![alt text](../images/7/4.png)

Paso 9. A este proceso se le conoce cómo depuración y en la mayoría de los editores de código podremos encontrar herramientas similares. 


## Resultado esperado [Instrucciones](#instrucciones)

Si hemos llegado hasta aquí deberíamos observar la herramienta de depuración en ejecución. 

![final](../images/7/4.png)
