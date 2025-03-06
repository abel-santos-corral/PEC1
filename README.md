# PEC1
Repositorio de Github para hacer la PEC1 de la asignatura de Inteligencia artificial

# Configuración de VS Code

Para configurar VS Code y tener el entorno listo, sigue estos pasos.

## Crear el entorno virtual

Primero, ve a la carpeta del proyecto y ejecuta:

``` 
python -m venv venv
```

## Activar el entorno virtual

Depende del sistema operativo (OS).

__Linux__

```
source venv/bin/activate
```

__Windows (Power shell)__

```
venv\Scripts\Activate.ps1
```

__Windows (Command prompt)__

```
venv\Scripts\activate
```

## Instalar dependencias

En este caso no es necesario, pero lo dejamos comentado para reutilizarlo en otros proyectos:

```
pip install -r requirements.txt
```

# Ejecutar analisis

Para ejecutar el programa haremos desde la terminal:

```
python3 arboles_cast_enunciado.py
```

Para poder cambiar el algoritmo podemos cambiar en el programa los valores de profundidad y de ramificación del árbol.
