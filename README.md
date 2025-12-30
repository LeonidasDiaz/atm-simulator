# Cajero Automático en Python

Simulación de cajero automático con menú interactivo, manejo de saldo, depósitos, retiros y validación de errores.

## Tabla de Contenidos
- [Descripcion](#descripcion)
- [Características](#características)
- [Instalacion](#instalacion)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Tecnollogias Utilizadas](#tecnologias-utilizadas)
- [Autor](#autor)
## Descripción
Este proyecto simula las operaciones básicas de un cajero automático:
- Consultar saldo disponible
- Depositar fondos en la cuenta
- Retirar dinero (con validación de fondos)
- Salir del sistema
Cada operación incluye validación de entradas, manejo de errores y formato profesional de salida.
## Características
- Menú interactivo con 4 opciones principales
- Saldo inicial de $1,000.00
- Validación de entradas con try/except
- Formato monetario profesional (2 decimales)
- Manejo de errores para entradas no numéricas
- Validación de fondos en retiros
- Código modular con funciones específicas
- Documentación completa con docstrings

## Estructura del Código
### Funciones principales
```python
def menu()
```
#### Muestra el menú de opciones disponibles.
```python
def consultar_saldo(Saldo)
```
#### Muestra el saldo actual con formato monetario.
```python
def depositar(Saldo)
```
#### Permite depositar dinero con validación de montos positivos.
```python
def retirar(Saldo)
```
#### Permite retirar dinero con validación de fondos disponibles.
```python
def main()
```
#### Función principal que coordina todo el flujo del programa.

## Instalación y Ejecución
### Requisitos
- Python 3.8 o superior
- Terminal o línea de comandos
### Ejecución directa
```bash
# Clonar el repositorio (opcional)
git clone https://github.com/tuusuario/cajero-python.git
cd cajero-python

# Ejecutar el programa
python cajero.py
```
### Tecnologias
- Python 3 - Lenguaje principal

- Manejo de excepciones - Validación robusta con try/except

- Funciones modulares - Separación de responsabilidades

- Formato de strings - f-strings para salida formateada

- Control de flujo - Bucles while y condicionales if/elif/else

## Estructura del Proyecto
- `main()` controla el flujo del programa.
- Funciones separadas para cada operación:
  - `consultar_saldo()`
  - `depositar()`
  - `retirar()`

## Tecnologías usadas
- Python 3
- Manejo de errores
- Programación estructurada

## Ejecutar el programa
```bash
python atm.py
