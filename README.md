#obligatorio
cp = input("Ingrese el código postal del lugar de destino: ")
direccion = input("Dirección del lugar de destino: ")
tipo = int(input("Tipo de envío (id entre 0 y 6 - ver tabla 2 en el enunciado): "))
pago = int(input("Forma de pago (1: efectivo - 2: tarjeta): "))

#verificamos destino
if len(cp) == 8:
    destino = "Argentina"

elif len(cp) == 9:
    destino = "Brasil"

elif len(cp) == 7:
    destino = "Chile"

elif len(cp) == 6:
    destino = "Paraguay"

elif len(cp) == 5:
    destino = "Uruguay"

elif len(cp) == 4:
    destino = "Bolivia"

else:
    destino = "Otro"

#verificamos provincia
if cp[0] == "a":
    provincia = "Salta"

elif cp[0] == "b":

elif cp[0] == "c":

elif cp[0] == "d":

elif cp[0] == "e":

elif cp[0] == "f":

elif cp[0] == "g":

elif cp[0] == "h":

elif cp[0] == "j":

elif cp[0] == "k":

elif cp[0] == "l":

elif cp[0] == "m":

elif cp[0] == "n":

elif cp[0] == "p":

#prints obligatorios
print("País de destino del envío:", destino)
print("Provincia destino:", provincia)
print("Importe inicial a pagar:", inicial)
print("Importe final a pagar:", final)
