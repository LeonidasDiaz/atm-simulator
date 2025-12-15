# Simulador de Cajero Automático en Python

Una simulación de cajero automático desarrollada en Python con menú interactivo, manejo de saldo, depósitos, retiros y validación de errores.
## Tabla de Contenidos
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
