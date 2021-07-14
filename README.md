# Proyecto 4: Resultados.
## Universidad de Costa Rica, Escuela de Ingeniería Eléctrica.
#### IE0405 - Modelos Probabilísticos de Señales y Sistemas
* Estudiante: **Laura Mata Mata**
* Carné: **B84689**
* Grupo: **1**

## Pregunta 1: 
### Realice una simulación del sistema de comunicaciones utilizando una modulación **16-QAM**. Deben mostrarse las imágenes enviadas y recuperadas y las formas de onda.
Los resultados son:

* La imagen recuperada:
![image](https://user-images.githubusercontent.com/85901448/125542256-a0a52e30-745b-4c20-bbfa-25b205aad0ab.png)


Como se puede observar, la imagen que se recuperó se aseja mucho a la original, pero se debe de tener en cuenta que al realizar la modulación 16-QAM se pierde información de la imagen. A la hora de correrlo se presentaron 2552 para un para un BER de 0.0060.


* Las formas de onda:
![image](https://user-images.githubusercontent.com/85901448/125542434-99332f6f-769d-4e2b-bf23-9c3f5b16eeeb.png)

## Pregunta 2: 
### Realice pruebas de estacionaridad y ergodicidad a la señal modulada `senal_Tx` y obtenga conclusiones sobre estas.
![image](https://user-images.githubusercontent.com/85901448/125543772-6c33fae2-c526-48b5-bc2d-0f92d591ce3b.png)

## Pregunta 3: 
### Determine y grafique la densidad espectral de potencia para la señal modulada `senal_Tx`.

\begin{equation}
\displaystyle
\mathcal{S}_{XX}(\omega) = \lim_{T \rightarrow \infty}\frac{E[\vert X_{T}(\omega) \vert^2]}{2T}
\end{equation}



