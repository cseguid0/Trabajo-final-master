# Trabajo de Final de Master
## Índice
[Descripción del proyecto](#descripción-del-proyecto)  
[Preparación del Entorno](#preparación-del-entorno)  
[Descarga del proyecto](#descarga-del-proyecto)  
## Descripción del proyecto
Este proyecto consiste en un sencillo juego de rol siguiendo las reglas de Dragones y Mazmorras
## Preparación del entorno
1.	Instalar Visual Studio siguiendo las [indicaciones de Epic Games](https://dev.epicgames.com/documentation/unreal-engine/setting-up-visual-studio-development-environment-for-cplusplus-projects-in-unreal-engine)
2.	Instalar [Epic Games Store](https://launcher-public-service-prod06.ol.epicgames.com/launcher/api/installer/download/EpicGamesLauncherInstaller.exe)
3.	Desde Epic Games Store, instalar Unreal Engine 5.7.4
4.	Cuando finalice la instalación, hacer clic en la flecha apuntando hacia abajo al lado de Iniciar dentro del apartado versiones de Unreal Engine en Unreal Engine > Biblioteca. Seleccionar opciones y activar “Datos esenciales para Metahuman Creator”
## Descarga del proyecto
1.	Descargar el proyecto desde el repositorio de Github
2.	Descargar el archivo Media.zip desde [Google Drive](https://drive.google.com/drive/u/0/folders/17r5gMDgQ4i19u7kGWGpQt0l0ac8y9fuU)
3.	Extraer la carpeta Media de Media.zip dentro de la carpeta Content del proyecto
4.	Si no se enlaza la terminación .uproject con Unreal Engine, volver a Versiones de Unreal Engine y hacer clic en complementos instalados, esto suele reparar la asociación de archivos .uproject. Si no funciona reiniciar el ordenador
5.	Abrir TFM.uproject. Aparecerá una ventana preguntando si queremos compilar el proyecto, seleccionar aceptar. Si no se compila automáticamente, hacer clic derecho sobre TFM.uproject y seleccionar Generate Visual Studio Project Files. Esto generará un proyecto de Visual Studio que podemos compilar. En Visual Studio compilar para Developer editor y win64. Una vez compilado volver a  abrir el archivo
