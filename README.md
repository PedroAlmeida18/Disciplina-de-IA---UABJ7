# Disciplina-de-IA---UABJ7
Atividade 7 : Perceptron  Aluno : Pedro Henrique de Almeida Santos 
TREINAMENTO DO PERCEPTRON — MODELO IGUAL AO DA AULA

Pesos iniciais: θ0=0, θ1=0, θ2=0



============================
CICLO 1
============================


Entrada: Joãozinho
x = [1, 0, 0], y = 0
s_out = h(0.0*1 + 0.0*0 + 0.0*0) = h(0.0) = 1
Erro: E = 0 - 1 = -1
Atualização dos pesos:
θ0 = 0.0 + 0.1 * -1 * 1 = -0.1
θ1 = 0.0 + 0.1 * -1 * 0 = 0.0
θ2 = 0.0 + 0.1 * -1 * 0 = 0.0

Entrada: Huguinho
x = [1, 0, 1], y = 0
s_out = h(-0.1*1 + 0.0*0 + 0.0*1) = h(-0.1) = 0
Erro: E = 0 - 0 = 0
Sem atualização (E = 0)

Entrada: Zezinho
x = [1, 1, 0], y = 1
s_out = h(-0.1*1 + 0.0*1 + 0.0*0) = h(-0.1) = 0
Erro: E = 1 - 0 = 1
Atualização dos pesos:
θ0 = -0.1 + 0.1 * 1 * 1 = 0.0
θ1 = 0.0 + 0.1 * 1 * 1 = 0.1
θ2 = 0.0 + 0.1 * 1 * 0 = 0.0

Entrada: Luizinho
x = [1, 1, 1], y = 1
s_out = h(0.0*1 + 0.1*1 + 0.0*1) = h(0.1) = 1
Erro: E = 1 - 1 = 0
Sem atualização (E = 0)

============================
CICLO 2
============================


Entrada: Joãozinho
x = [1, 0, 0], y = 0
s_out = h(0.0*1 + 0.1*0 + 0.0*0) = h(0.0) = 1
Erro: E = 0 - 1 = -1
Atualização dos pesos:
θ0 = 0.0 + 0.1 * -1 * 1 = -0.1
θ1 = 0.1 + 0.1 * -1 * 0 = 0.1
θ2 = 0.0 + 0.1 * -1 * 0 = 0.0

Entrada: Huguinho
x = [1, 0, 1], y = 0
s_out = h(-0.1*1 + 0.1*0 + 0.0*1) = h(-0.1) = 0
Erro: E = 0 - 0 = 0
Sem atualização (E = 0)

Entrada: Zezinho
x = [1, 1, 0], y = 1
s_out = h(-0.1*1 + 0.1*1 + 0.0*0) = h(0.0) = 1
Erro: E = 1 - 1 = 0
Sem atualização (E = 0)

Entrada: Luizinho
x = [1, 1, 1], y = 1
s_out = h(-0.1*1 + 0.1*1 + 0.0*1) = h(0.0) = 1
Erro: E = 1 - 1 = 0
Sem atualização (E = 0)

Pesos finais:
θ0 = -0.1, θ1 = 0.1, θ2 = 0.0


Arquivo gerado: Resultados_Perceptron.txt
