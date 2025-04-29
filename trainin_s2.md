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
Puntos en el plano cartesiano
Escribir un programa que pida ingresar coordenadas (x, y) y determine cuántos puntos se encuentran en cada cuadrante (I, II, III, IV).
Nota: Al inicio, el programa debe solicitar la cantidad de puntos a procesar.
```python
n = int(input("cuantos puntos quiere ingresar: "))
contador1 = contador2 = contador3 = contador4 = 0
for i in range(n):
    x = float(input(f"ingresa las coordenadas x del punto {i+1} "))
    y = float(input(f"ingrese las coordenadas y del punto {i+1} "))
    if x > 0 and y > 0:
        contador1 += 1
    elif x < 0 and y > 0:
        contador2 += 1
    elif x < 0 and y < 0:
        contador3 += 1
    elif x > 0 and y < 0:
        contador4 += 1
print(f"la cantidad de puntos en cada cuadrante son: cuadrante 1 = {contador1},cuadrante 2 = {contador2}, cuadrante 3 = {contador3},cuadrante 4 = {contador4} ")
```
