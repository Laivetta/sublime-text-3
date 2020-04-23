# sublime-text-3
Python input
En Sublime Text hay que instalar primero el paquete Terminus
Despues hay que crear un Build System Nuevo con el siguiente contenido:

{
    "target":"terminus_open",
    "cmd": ["python3", "-i", "-u", "$file"],
    "auto_close":false,
    
    "selector": "source.python"
    }
 
 Esto lo que va a hacer es cuando oprimamos Ctrl+b, ejecutar en una nueva ventana el archivo de Python y nos va a dejar completar los input que nos requiera el programa.
 
