# Archivo CMakeLists.txt

cmake_minimum_required(VERSION 3.17)
project(Ejercicio1)

# Agrega los archivos fuente al proyecto
set(SOURCE_FILES
        Funciones.cpp
        EJ1.cpp)

# Indica al compilador que debe incluir estos archivos
add_executable(Ejercicio1 ${SOURCE_FILES})