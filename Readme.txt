Instrucciones para activar docker y poder ver pagina
-Tener instalado docker desktop si no instalarlo
-Tener docker desktop corriendo de fondo(se puede saber si esta corriendo si aparece el simbolo de ballena en la barra de tareas) 
-abrir el cmd/powershell en la carpeta de PROYECTO-2 o usar el terminal de visual estudio code en la carpeta PROYECTO-2
-escribir en el CMD/Powershell/terminal "docker build -t laboratorio_2 ." (no olvidar el punto al final) 
-escribir en el CMD/Powershell/terminal cuando termine de cargar lo anterior " docker run -d -p 8080:80 --name lab2 laboratorio_2"
-por ultimo abrir docker y donde aparece el contenedor dar click en 8080:80