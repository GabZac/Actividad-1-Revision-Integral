# Proyecto Integrador Anual - LPR 2026

## Institución
**EEST N.º 1 "Eduardo Ader" - Vicente López** **Curso:** 5° Año 
**Materia:** Laboratorio de Programación (LPR)  
**Profesores:** York
---

## Descripción del Proyecto
**Presentación de la Actividad**
Van a realizar un repaso de los conceptos de lógica y algoritmos que trabajaron el año pasado pero esta vez lo trabajaran en Python, y los van a comparar con el lenguaje estructurado de bajo nivel en C++.
**El objetivo:** Escribir un programa que calcule la edad exacta de una persona restando su año de nacimiento con el año actual. El programa debe verificar que las fechas ingresadas existan en el calendario real (bisiestos y cantidad de días de cada mes)


## Integrantes (Grupo N.º 3)
* **Zacarias, Gabriel** 
* **Mojica, Sofia** 
* **De Armas, Leonel** 
 **Roberts, Mateo** 

## Requisitos e Instalación
1. Tener instalado **Python 3.12+** y **Git**.
2. Clonar el repositorio:  
   `git clone https://github.com/GabZac/Actividad-1-Revision-Integral.git`
3. Instalar Flask desde la terminal de VSCode:  
   `pip install flask`

## Ejecución
Para encender el servidor, situarse en la carpeta del proyecto y ejecutar:
```bash
python backend/app.py
```bash

## Estructura Obligatoria del Repositorio

```text
/Edad_Calculadora/
├── .gitignore              <-- Archivo para que Git ignore los archivos pesados
├── README.md      <-- Descripción breve del ejercicio de revisión
├── LICENSE            <-- Descripción breve de la licencia
├── docs/                   <-- Carpeta exclusiva para documentación
│  └── InformeProyectoCalculadoraEdad.pdf         <-- Archivo de información del Proyecto
├── proyecto_cpp/                   <-- Carpeta exclusiva para código
│  └── main.cpp                   <-- Archivo de código en C++
└── proyecto_python/                <-- Carpeta exclusiva para el código
    └── main.py          <-- Archivo de código en Python
