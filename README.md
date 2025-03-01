

https://github.com/user-attachments/assets/72d03ba6-a4d6-4996-a848-9eeb2f69ca97

importar random
import string
def generar_clave():
   caracteres =
   string.digits+string.punctuation
   clave=".join(random.choice(caracteres)
for_in range(25))
   return clave

print(generar_clave())

#validaciones
if not an(char.islower() for char in clave):
print(Advertencia la clave no contiene minusculas.Generando nuevamente",)
   return generar_claves()
 if not any(char.is upper() for char in clave
 print("Advertencia:La clave no contiene numeros.Generando nuevamente.")
     return generar_clave()
  if not any(char in string.punctuation for char in clave):
                   print()
