Números mayores o iguales a 1000
Escribir un programa que lea n números enteros y determine cuántos de ellos son mayores o iguales a 1000
```python
n = int(input("cuantos numeros quiere ingresar: "))
contador = 0
for i in range(n):
    numero = int(input(f"ingresa el numero {i+1}: "))
    if numero >= 1000:
        contador += 1
print(f"la cantidad de numeros mayores a 1000 son: {contador}")
```
Cálculo de áreas de triángulos
Confeccionar un programa que lea n pares de datos (base y altura) correspondientes a triángulos. Debe mostrar:
 Base, altura y superficie de cada triángulo.
    Cantidad de triángulos con superficie mayor a 12.
```python
n = int(input("cuantos triangulos quiere ingresar: "))
contador = 0
for i in range(n):
    base = float(input(f"ingrese la base del triangulo {i+1} "))
    altura = float(input(f"ingrese la altura del triangulo {i+1} "))
    superficie = (base*altura)/2
    print(f"triangulo {i+1}: base = {base}, altura = {altura}, superficie = {superficie}")
    if superficie > 12 :
        contador += 1
print(f"la cantidad de triangulos con superficie mayor a 12 son: {contador}")
```
