print (" ") #Esta linea da el espacio para el nombre
print ("Cristian David Salas De La O 3-W") # Esta linea muestra el nombre 
print (" ") #Esta linea da el espacio para el nombre
ruta_archivo = "D:\\myfiles\\welcome.txt" #Esta linea define el archivo

try: #Esta linea hace el intento 
    with open(ruta_archivo, "r") as f: #Esta linea lee el archivo
        contenido = f.read() #Esta linea define el contenido 
        print(contenido) #Esta linea muestra el contenido 
except FileNotFoundError: #Esta linea programa el error
    print(f"El archivo no se encontró en la ruta: {ruta_archivo}") #Esta linea muestra el error que no se encontro la ruta
except Exception as e: #Esta linea hace la exepcion
    print(f"Ocurrió un error: {e}") #Esta linea muestra el error
![image](https://github.com/user-attachments/assets/6aebad42-bb23-4c7f-9d6f-6847365bab2a)
![image](https://github.com/user-attachments/assets/de261964-ce49-44b1-8a77-8fcdb8ede3c2)
