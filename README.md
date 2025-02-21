##Proyecto de Cifrado y Descifrado con Pycrytodome

## Descripción
Este proyecto permite cifrar y descifrar mensajes de texto utilizando el algoritmo de cifrado simétrico AES en modo EAX. Se genera una clave aleatoria de 16 bytes y un vector de inicialización (IV) para asegurar la seguridad del mensaje. Además, se guardan tanto el mensaje cifrado como el mensaje descifrado en archivos de texto dentro de un directorio llamado `archivos`.

## Requisitos
Este proyecto requiere Python y la biblioteca `pycryptodome`. Si no la tienes instalada, puedes hacerlo con el siguiente comando:

```sh
pip install pycryptodome
```

## Uso
1. Ejecuta el script en la terminal:
   ```sh
   python script.py
   ```
2. Introduce el texto que deseas cifrar cuando se te solicite.
3. El programa cifrará el mensaje, lo mostrará en pantalla y lo guardará en `archivos/cifrado.txt`.
4. Luego, el programa descifrará el mensaje y lo guardará en `archivos/descifrado.txt`.
5. Finalmente, se mostrará en pantalla el mensaje original descifrado.

## Estructura del Proyecto
```
.
|-- script.py
|-- archivos/
    |-- cifrado.txt
    |-- descifrado.txt
```

## Notas
- Asegúrate de que el directorio `archivos` existe o será creado automáticamente.
- Si deseas compartir un mensaje cifrado, debes compartir también la clave y el `nonce` generado.

## Autor
Jorge Bernal Liarte

