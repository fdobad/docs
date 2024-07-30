En esta seccion se detalla un ejemplo de uso utilizando una instancia descargada del Instance Donwloader correspondiente a la zona de Villarica. Tambien se muestra la obtencion de distintos resultados y su visualizacion dentro de QGIS.

Si no se dispone de un raster de modelo de combustible, es posible obtener uno siguiendo los siguientes pasos:

* Para utilizar las funciones de la caja de herramientas es necesario contar con un set de datos geográficos y meteorológicos. Si ud. no dispone de dichos recursos puede utilizar el algoritmo ``Instance Downloader`` para descargar una instancia preparada. Para este proyecto de prueba descargaremos la zona de Villarica correspondiente al modelo de combustibles de Kitral.
![Descargador de instancias](images/foto_instancia.png)
![Cuadro de descarga](images/foto_instancia2.png)

* Guarde un proyecto vacío en la carpeta descargada (donde están los archivos fuels, elevation y Weather.csv).
![Guardar proyecto](images/foto_instancia3.png)

* Arrastre y suelte capas desde el proyecto principal (Panel del Explorador de Archivos) al Panel de Capas.
![Guardar proyecto](images/capas_2.png)

* Establezca el mismo CRS (Sistema de Referencia de Coordenadas) para las capas y el proyecto (cualquiera en metros es suficiente para obtener los resultados, sin embargo para una correcta geo-referencia se necesita el sistema de coordenadas adecuado).

![Sistema de coordenadas proyecto](images/foto_instancia4.png)
![Sistema de coordenadas capas](images/foto_instancia5.png)

* Abra el algoritmo del simulador, seleccione el modelo de combustible adecuado (Canada, Kitral o S&B), seleccione la capa de combustible en el menú desplegable de combustible y presione ejecutar.



\begin{enumerate}
    \item Para utilizar las funciones de la caja de herramientas es necesario contar con un set de datos geográficos y meteorológicos. Si ud. no dispone de dichos recursos puede utilizar el algoritmo ``Instance Downloader`` para descargar una instancia preparada. Para este proyecto de prueba descargaremos la zona de Villarica correspondiente al modelo de combustibles de Kitral.
    
    \begin{figure}[H]
    \centering
    \includegraphics[width=0.45\textwidth]{images/foto_instancia.png}
    \caption{\label{fig:frog} Descargador de instancias}
    \end{figure}

    \begin{figure}[H]
    \centering
    \includegraphics[width=0.5\textwidth]{images/foto_instancia2.png}
    \caption{\label{fig:frog} Cuadro de descarga}
    \end{figure}
    
    \item Guarde un proyecto vacío en la carpeta descargada (donde están los archivos fuels, elevation y Weather.csv).

    \begin{figure}[H]
    \centering
    \includegraphics[width=0.5\textwidth]{images/foto_instancia3.png}
    \caption{\label{fig:frog} Guardar proyecto}
    \end{figure}
    
    \item Arrastre y suelte capas desde el proyecto principal (Panel del Explorador de Archivos) al Panel de Capas.

    \begin{figure}[H]
    \centering
    \includegraphics[width=0.3\textwidth]{images/capas_2.png}
    \caption{\label{fig:frog} Guardar proyecto}
    \end{figure}
    
    \item Establezca el mismo CRS (Sistema de Referencia de Coordenadas) para las capas y el proyecto (cualquiera en metros es suficiente para obtener los resultados, sin embargo para una correcta geo-referencia se necesita el sistema de coordenadas adecuado).

    \begin{figure}[H]
    \centering
    \includegraphics[width=0.7\textwidth]{images/foto_instancia4.png}
    \caption{\label{fig:frog} Sistema de coordenadas proyecto}
    \end{figure}

    \begin{figure}[H]
    \centering
    \includegraphics[width=0.7\textwidth]{images/foto_instancia5.png}
    \caption{\label{fig:frog} Sistema de coordenadas capas}
    \end{figure}
    
    \item Abra el algoritmo del simulador, seleccione el modelo de combustible adecuado (Canada, Kitral o S\&B), seleccione la capa de combustible en el menú desplegable de combustible y presione ejecutar.
\end{enumerate}