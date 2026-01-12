# 20-question
pequenas questoes para treino de python


#1 imprimindo meu nome
print("Julye")

#2 peca um n° e dps o informe
p=int (input("fale um numero de 0 a 10 "))
a=print(f"o numero informado foi {p}")

#3 peca 2 n° e dps some 
q= int(input("primeiro numero: "))
w= int (input("segundo numero: "))
e= q+w
print(e)

#4 peca a idd e dps a informe
r=int(input("qual sua idade? " ))
print(f"sua idade seria {r} correto?")

#5 add 2 zeros
i=float(input("what? " ))
print("%.2f"%i)

#6 some diminua multiplique e divida
t= int(input("number one: "))
y= int (input("number two: "))
u= t+y, t-y, t*y,t/y
print(u)

#7 valor aumentado em 10%
b = float(input("Qual o preço? "))
c = b * 1.10
print(f"O valor com aumento de 10% é: R$ {c:.2f}")

#8 media
v=int(input("number: "))
z= int (input("outro numero: "))
f= v+z
g=f/2
print(f"media desses numeros sao: {g} ")

#9 faca a media 3 n°
l=int(input(": "))
k= int (input(": "))
h=int (input(": "))
j= l+k+h
d=j/3
print(f"soma seria {j} e media {d} ")

#10 desconto de 15%
s= float(input("Qual o preço do produto? "))
m = s * 0.85
print(f"preço com desconto de 15%: R$ {m:.2f}")

#11 media 4 n°
A=int(input("um: "))
B= int (input("dois: "))
C=int (input("tres: "))
F=int(input("quatro: "))
D= A+B+C+F
E=D/4
print(f"A media seria {E} ")

#12 velocidade media de um percurso
distancia=int(input("quantos Km? "))
tempo=int(input("quantas horas? "))
Q=distancia/tempo
print(f"a velocidade media seria {Q}")

#13 preco com desconto
S=float(input("preço: "))
M=int(input("porcentual de desconto: "))
N=M/100
n=S*N
ab=S-n
print(f"igual a {ab}")

#14 quantos gasto de gasolina
km= int(input("distancia total: "))
kml=int(input("consumo medio: "))
tu=km/kml
print(f"serao necessarios: {tu}")

#15 descobre os segundos totais
horas=int(input(" horas: "))
minutos=int(input(" minutos: "))
segundos=int(input(" segundos: "))
maiegundos=(horas*3600) + (minutos*60)+segundos
print(f"total em seguntos é {maiegundos}")

#16 media de notas
bi=int(input("primeiro bimestre: "))
mes=int(input("segundo bimestre: "))
tra=int(input("terceiro bimestre: "))
iz= int(input("quarto bimestre: "))
notas=(bi+mes+tra+iz)/4
print(f"a media fica em {notas}")

#17 metros p/ cm
Metros=int(input("quantos metros? "))
cm= Metros*100
print(f"fico um total de {cm} centimetros")

#18 faz teu salario
hor=float(input("quanto voce ganha por hora? "))
az=int(input("quantas horas voce trabalhou? "))
tota=hor*az
print(f"voce ganhara mais ou menos {tota}")

#19 f° 
F=int(input("quantos graus Fahrenheit? "))
C=5*((F-32)/9)
print(f"em graus celsius ficaria {C}")

#20 imc
import tkinter as tk
janela = tk.Tk()
janela.title("Botoes sexo")
H= float( input("sua altura: "))
homem=(H*72.7)-58
mulher=(62.1*H)-44.7
btman= tk.Button(janela, text="homem", command=lambda: print(f"press man = {homem}"))
btwon= tk.Button(janela, text="mulher", command= lambda: print(f"press woman = {mulher}"))
btman.pack()
btwon.pack()
janela.mainloop()