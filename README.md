def  calcular_ecuacion(x):
     resultado = (x * 3 + 5 ) / 2
     return  resultado

if __name__ == '__main__':
    x = float(input("colocale un valor a x:"))
    print(f"el resultado es:{calcular_ecuacion(x)}")
