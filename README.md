# Readme de entornos y necesidades para correr notebooks

## PARA LABORATORIO 1:
1. Crear entorno virtual:
   ```bash
   python -m venv deep-env
   ```

2. Descargar data de:
    https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification

    y guardarla en:
   ```bash
   data/lab1/
   ```

3. Activar entorno:
    ```bash
    deep-env\Scripts\activate

    ```

4. Instalar dependencias:
    ```bash
    pip install -r requirements.txt

    ```

5. Para el laboratorio 1 con entorno activado
   ```bash
    pip install -U --force-reinstall --no-cache https://github.com/johnhw/jhwutils/zipball/master
    ```

6. Para el laboratorop 3 con entorno  activado
    ```bash
    pip install -U --force-reinstall --no-cache https://github.com/AlbertS789/lautils/zipball/master
    ```
