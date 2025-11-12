```markdown
# 🧩 Desafio 2 — O Paradoxo do Navio de Teseu  
## O Navio que Nunca Parou  

---


### 5. Propósito pedagógico (Para o Mentor)  

Treinar o pensamento abstrato e a distinção entre diferentes critérios de identidade (material, funcional, histórica), além de introduzir o raciocínio lógico por invariantes — o que *permanece constante* apesar da mudança.

---

### 6. Resolução comentada  

O aprendiz deve construir uma tabela simples:

| Ano | Peças Originais no Navio | Peças Novas Inseridas | Continuidade Funcional | Continuidade Material |
|------|---------------------------|------------------------|------------------------|-----------------------|
| 1    | A1–A8                    | N1, N2                | ✅ (navio ainda opera) | 🔶 (20% substituído) |
| 2    | A1–A6                    | N1–N4                 | ✅                     | 🔶 (40%) |
| 3    | A1–A4                    | N1–N6                 | ✅                     | 🔶 (60%) |
| 4    | A1–A2                    | N1–N8                 | ✅                     | 🔶 (80%) |
| 5    | —                        | N1–N10                | ✅                     | ❌ (100%) |

O raciocínio lógico mostra duas linhas simultâneas de continuidade:

- **Linha funcional:** nunca se rompeu — o navio sempre navegou, nunca foi desmontado por completo.  
- **Linha material:** foi perdida gradualmente, até desaparecer no 5º ano.  

Logo, existem **dois navios válidos**, dependendo da definição adotada:  

- Se **função e história contínua** definem identidade, o *Navio Atual* é o verdadeiro.  
- Se **matéria original** define identidade, o *Navio Refeito* é o verdadeiro.  

Mas o Oráculo exige algo além da resposta: o **momento da ruptura**.  
Se procurarmos o ponto em que ambas as identidades se tornam mutuamente exclusivas, isso ocorre **no instante da última substituição** — quando o Navio Atual deixa de conter qualquer peça original, e o Navio Refeito começa a existir novamente.  

Matematicamente, poderíamos descrever a identidade como uma função **I(t)** com dois componentes:

> I(t) = f(continuidade) + m(materialidade)

Enquanto f(t) = 1 e m(t) > 0, ainda há ambiguidade.  
Quando m(t) = 0, I(t) depende unicamente da continuidade.  
Nesse ponto, a identidade "salta" de uma definição para outra — uma espécie de descontinuidade lógica.  

---

### 7. Resposta final  

Não há um único “verdadeiro” Navio de Teseu.  
Há dois — cada um fiel a uma definição distinta de identidade.  
A ruptura lógica ocorre no momento em que a última peça original é substituída.  

---

### 8. Extensões  

1. E se as peças substituídas **voltassem ao mar aos poucos**, misturando-se novamente? Seria possível que, ao fim de 100 anos, houvesse **um terceiro navio** — com partes de ambos?  
2. E se o navio tivesse **uma mente artificial** que armazenasse sua memória — ela seria o critério decisivo da identidade?  

---

> “O aprendiz que entende este paradoxo não apenas compreende o tempo —  
> mas também o que é permanecer o mesmo enquanto tudo muda.”
```
