# Creando un Ambiente Virtual en Python

En este documento, te explicaremos de manera sencilla cómo crear un ambiente virtual en Python. Un ambiente virtual es una herramienta que te permite tener un entorno de trabajo aislado, donde puedes instalar y utilizar diferentes versiones de paquetes y librerías de Python sin afectar a otros proyectos en tu computadora. Aquí te mostraremos dos formas populares de crear un ambiente virtual: con Conda y con venv.

## Creando un Ambiente Virtual con Conda

Conda es una herramienta muy útil que permite gestionar ambientes virtuales y paquetes en Python de manera sencilla. Puedes descargar e instalar Conda desde el [portal oficial de Conda](https://conda.io/projects/conda/en/latest/index.html).

A continuación, se muestra cómo crear y utilizar un ambiente virtual con Conda:

1. Abre la terminal o línea de comandos en tu computadora.

2. Ejecuta el siguiente comando para crear un nuevo ambiente virtual con Conda:

   ```bash
   conda create --name mi_ambiente_virtual
   ```

   Puedes elegir cualquier nombre para tu ambiente virtual, por ejemplo, "mi_ambiente_virtual".

3. Una vez que se haya creado el ambiente virtual, actívalo ejecutando el siguiente comando:

   ```bash
   conda activate mi_ambiente_virtual
   ```

   Ahora estás dentro de tu ambiente virtual.

4. Puedes instalar paquetes y librerías en tu ambiente virtual utilizando el comando `conda install`.

5. Cuando hayas terminado de trabajar en tu ambiente virtual, puedes desactivarlo ejecutando el siguiente comando:

   ```bash
   conda deactivate
   ```

   Esto te llevará de regreso al entorno normal de tu computadora.

## Creando un Ambiente Virtual con venv

Python también incluye una herramienta llamada venv, que te permite crear ambientes virtuales de manera nativa.

1. Abre la terminal o línea de comandos en tu computadora.

2. Ejecuta el siguiente comando para crear un nuevo ambiente virtual con venv:

   ```bash
   python -m venv mi_ambiente_virtual
   ```

   Puedes elegir cualquier nombre para tu ambiente virtual, por ejemplo, "mi_ambiente_virtual".

3. Activa el ambiente virtual ejecutando el siguiente comando:

   - En Windows:

     ```bash
     mi_ambiente_virtual\Scripts\activate
     ```

   - En macOS y Linux:

     ```bash
     source mi_ambiente_virtual/bin/activate
     ```

   Ahora estás dentro de tu ambiente virtual.

4. Puedes instalar paquetes y librerías en tu ambiente virtual utilizando el comando `pip install`.

5. Cuando hayas terminado de trabajar en tu ambiente virtual, puedes desactivarlo ejecutando el siguiente comando:

   ```bash
   deactivate
   ```

   Esto te llevará de regreso al entorno normal de tu computadora.

## ¡Listo para Explorar!

Ahora que sabes cómo crear ambientes virtuales con Conda y venv, puedes comenzar a explorar y experimentar con diferentes paquetes y librerías de Python en entornos aislados. Los ambientes virtuales te permiten mantener tus proyectos separados y evitar conflictos entre versiones de paquetes.

¡Diviértete programando en tus ambientes virtuales! 🚀🐍
