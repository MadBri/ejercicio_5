# ejercicio_5
 
 ### main.py

```python
if __name__ == "__main__":
    # Genera la lista con el cuadrado de los números pares y el cubo de los impares
    lista = [(i**2 if i % 2 == 0 else i**3) for i in range(1, 101)]
    suma_total = 0
    contador = 0

    # Calcula cuantos números se deben sumar para que el resultado sea cercano a un millón
    for numero in lista:
        if suma_total + numero < 1000000:
            suma_total += numero
            contador += 1
        else:
            break

    print(f"Se suman {contador} números para alcanzar la suma más cercana a un millón, que es {suma_total}")
```

### Rama 1: `generar_lista`

```python
if __name__ == "__main__":
    # Genera la lista con el cuadrado de los números pares y el cubo de los impares
    lista = [(i**2 if i % 2 == 0 else i**3) for i in range(1, 101)]
    print("Lista generada:", lista)
```

### Rama 2: `calcular_suma`

```python
if __name__ == "__main__":
    # Genera la lista con el cuadrado de los números pares y el cubo de los impares
    lista = [(i**2 if i % 2 == 0 else i**3) for i in range(1, 101)]
    suma_total = 0
    contador = 0

    # Calcula cuantos números se deben sumar para que el resultado sea cercano a un millón
    for numero in lista:
        if suma_total + numero < 1000000:
            suma_total += numero
            contador += 1
        else:
            break

    print(f"Se suman {contador} números para alcanzar la suma más cercana a un millón, que es {suma_total}")
```

### Rama 3: `funciones_generales`

```python
if __name__ == "__main__":
    # Genera la lista con el cuadrado de los números pares y el cubo de los impares
    lista = [(i**2 if i % 2 == 0 else i**3) for i in range(1, 101)]
    suma_total = 0
    contador = 0

    # Calcula cuantos números se deben sumar para que el resultado sea cercano a un millón
    for numero in lista:
        if suma_total + numero < 1000000:
            suma_total += numero
            contador += 1
        else:
            break

    print(f"Se suman {contador} números para alcanzar la suma más cercana a un millón, que es {suma_total}")
```

