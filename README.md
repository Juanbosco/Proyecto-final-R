# README
Este archivo Readme está creado para dar ciertas instrucciones en el y poder poner en funcionamiento el proyecto.

## Instalación de paquetes en RStudio
Estos son los paquetes necesarios para el correcto funcionamiento del archivo `Rmd.`
```
install.packages('dplyr')
install.packages('ggplot2')
install.packages('plotly')
install.packages('gapminder')
install.packages('rvest')
install.packages('magrittr')
install.packages('kableExtra')
install.packages('googledrive')
```
## Librerías utilizadas
```
library(dplyr)
library(ggplot2)
library(plotly)
library(gapminder)
library(rvest)
library(magrittr)
library(kableExtra)
library(googledrive)
```
## Lectura fichero`.csv`
Este archivo está subido en GoogleDrive. Para la correcta lectura del fichero `.csv`será necesario dar permisos a la API Tidyverse para descargar el archivo desde GoogleDrive.
