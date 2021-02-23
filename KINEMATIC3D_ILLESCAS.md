# KINEMATIC3D_ILLESCAS
Se detalla a continuación el paso a paso para usar el software Kinematic3D instalado en el proyecto DIC-WLC A350 de Airbus Illescas.
1. Instalar el software necesario para la funcionalidad completa de la solución - [Download Software](#Software)
1. Descargar el proyecto `K3D_DIM-ILL` - [Download Solution](https://dev.azure.com/AritexSoftware/_git/K3D_DIM-ILL)
1. Descargar la carpeta de librerías externas necesarias para la compilación del proyecto. Se deberán ubicar en D:\PlatformSDK - [Download] 

      | | Descripción | Código | Docs |
      |-|:------------|:----:|:----:|
      |boost | ToDo |:white_check_mark:|:negative_squared_cross_mark:|
      |Dongle| ToDo |:white_check_mark:|:negative_squared_cross_mark:|
      |Eigen| ToDo |:white_check_mark:|:negative_squared_cross_mark:|
      |FARO64| ToDo |:white_check_mark:|:negative_squared_cross_mark:|
      |PCL| ToDo |:white_check_mark:|:negative_squared_cross_mark:|
      |scintilla| ToDo |:white_check_mark:|:negative_squared_cross_mark:|
      |VTK| ToDo |:white_check_mark:|:negative_squared_cross_mark:|
      |WTL| ToDo |:white_check_mark:|:negative_squared_cross_mark:|

4. Abrir la solución `D:\K3D_DIM-ILL\Kinematic3D.sln` y compilarla
1. Para lanzar el ejecutable (`D:\K3D_DIM-ILL\bin-x64\K3D-64.exe`) será necesario:
    * Añadir las siguientes librerías a su misma altura
      * GLUT64.dll
      * TRACKER.dll
      * TRACKERERRORSDLL.dll
      * pcl_sample_consensus_release.dll
      * pcl_segmentation_release.dll
      * pcl_io_release.dll
      * pcl_filters_release.dll
      * pcl_common_release.dll
      * pcl_kdtree_release.dll
      * pcl_search_release.dll
      * pcl_features_release.dll
      * pcl_surface_release.dll
      * pcl_ml_release.dll
      * pcl_io_ply_release.dll
      * vtkCommon.dll
      * vtkIO.dll
      * vtkImaging.dll
      * vtkFiltering.dll
      * OpenNI64.dll
      * pcl_octree_release.dll
      * vtkGraphics.dll
      * vtksys.dll
      * vtkDICOMParser.dll
      * vtkNetCDF.dll
      * vtkNetCDF_cxx.dll
      * vtkmetaio.dll
      * vtkpng.dll
      * vtkzlib.dll
      * vtkjpeg.dll
      * vtktiff.dll
      * vtkexpat.dll
      * vtkverdict.dll
    * Conectar la licencia USB a cualquiera de los puertos del ordenador

## Software
- Visual Studio 2012 - [Download](https://visualstudio.microsoft.com/es/vs/older-downloads/)
- Python 2.7.12 - [Download](https://www.python.org/downloads/release/python-2712/) (Instalar en C:\Python27)
- Visual Studio Code - [Download](https://code.visualstudio.com/)
- MeshLab - [Download](https://www.meshlab.net/#download)
- DBBrowser SQlite - [Download](https://sqlitebrowser.org/dl/)

[[Go to top]](#KINEMATIC3D_ILLESCAS)
