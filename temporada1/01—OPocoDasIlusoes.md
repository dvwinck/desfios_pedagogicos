# 🧩 Desafio 1 — O Poço das Ilusões

Um sapo está preso num poço de **30 metros de profundidade**.

Ele **sobe 3,5 metros** durante o dia, mas à noite **escorrega 2 metros**.

A cada **5 dias**, o sapo fica **mais cansado** e passa a:

* subir **0,2 metro a menos por dia**;
* escorregar **0,1 metro a menos por noite**.

Pergunta:
**Em quantos dias o sapo sairá do poço, considerando todos esses fatores?**


## Pergunta:

**Em quantos dias o sapo conseguirá sair do poço, considerando todas as variações acima?**

---

## Complementos

### 🎯 Dicas (para quem quiser explorar mais fundo)

1. Faça uma **tabela dia a dia** até perceber o **padrão** do progresso líquido.
2. Observe que há **duas progressões sobrepostas**: o esforço (que decresce) e a água (que oscila ciclicamente).
3. Quando o sapo atingir ou ultrapassar os 30 metros **ao fim do dia**, ele **não escorrega à noite** — porque já saiu.

---

###💡 Extensão (nível avançado)

Transforme o problema em uma **expressão algébrica ou algoritmo** que possa:

* Calcular o número de dias para **qualquer** profundidade `D`.
* Considerar **funções de fadiga** (por exemplo, sobe `3 - 0.1 * (dia // 5)` metros por dia).

---

## 🧠 Notas para o mentor 

Esse desafio estimula:

* Pensamento **sequencial e lógico** (progresso diário).
* Noção de **padrão e periodicidade**.
* Introdução à **modelagem matemática e algoritmos**.
* Capacidade de **abstração** (generalizar regras e simular casos).

