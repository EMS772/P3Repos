# correccion_error.py
def dividir(a, b):
    if b == 0:
        return "Error: No se puede dividir por cero"
    return a / b

print(dividir(10, 2))
print(dividir(5, 0))
