**1. Título**
**O Enigma dos Pontos e Triângulos**


**7. Resolução comentada**

O problema parece geométrico, mas é puramente **combinatório**.
Formar um triângulo exige escolher **3 pontos diferentes** dentre os ( n ) disponíveis.

Logo, para cada grupo de 3 pontos, há **exatamente um triângulo possível** (porque não há três colineares).

A pergunta então se transforma em:
“Quantos grupos diferentes de 3 pontos posso escolher entre ( n )?”

A contagem é feita por meio de combinações, pois **a ordem dos pontos não importa** (o triângulo formado pelos pontos A, B e C é o mesmo que o formado por C, B e A).

A fórmula das combinações é:

[
C(n, 3) = \frac{n!}{3!(n - 3)!}
]

ou, simplificando:

[
C(n, 3) = \frac{n \times (n - 1) \times (n - 2)}{6}
]

Aplicando:

* Para ( n = 5 ):
  [
  C(5, 3) = \frac{5 \times 4 \times 3}{6} = 10
  ]
  **10 triângulos.**

* Para ( n = 7 ):
  [
  C(7, 3) = \frac{7 \times 6 \times 5}{6} = 35
  ]
  **35 triângulos.**

* Para ( n = 10 ):
  [
  C(10, 3) = \frac{10 \times 9 \times 8}{6} = 120
  ]
  **120 triângulos.**

Mas aqui está a **complexidade oculta**:
a fórmula **só é verdadeira** se **nenhum trio de pontos estiver alinhado**.
Se 3 ou mais pontos estiverem na mesma linha, é preciso **subtrair** as combinações desses pontos “inválidos”, pois eles não formam triângulos.

Por exemplo, se entre os 10 pontos houver 4 alinhados, o número de combinações inválidas é:
[
C(4, 3) = 4
]
Então o número real de triângulos seria:
[
120 - 4 = 116
]

Assim, a mente do aprendiz deve compreender tanto o padrão geral quanto a fragilidade das suposições. O verdadeiro domínio não está apenas em aplicar a fórmula, mas em **saber quando ela falha**.

---

**8. Resposta final**

* Com 5 pontos: **10 triângulos.**
* Com 7 pontos: **35 triângulos.**
* Com 10 pontos: **120 triângulos.**
* Fórmula geral:
  [
  T(n) = \frac{n \times (n - 1) \times (n - 2)}{6}
  ]

---

**9. Extensões**

1. E se **3 dos pontos estiverem alinhados** — como ajustar a contagem?
2. E se os pontos estiverem em uma **circunferência** — o que muda (ou não) na lógica?
3. E se o Oráculo pedisse o número de **quadriláteros possíveis**? Qual seria a nova fórmula?

(O aprendiz descobrirá que, nesse caso, o universo cresce com ( C(n, 4) ).)
