# Aritmética do Computador — Cap. 10 (Grupo 6)

Material de seminário da disciplina **Bases da Computação 6B** (Sistemas de Informação), referente ao **Capítulo 10 — Aritmética do Computador** do livro de William Stallings, *Arquitetura e Organização de Computadores* (10ª ed.).

> **Grupo 6** · Apresentação em **16/07/2026**

---

## 🎯 Sobre

Este repositório reúne os materiais de apoio para o seminário: o laboratório interativo, os documentos da disciplina e a referência bibliográfica. O tema cobre como o processador representa números e executa operações aritméticas usando apenas dígitos binários.

### Tópicos abordados
- **ALU** — Unidade Lógica e Aritmética e suas flags (Zero, Sinal, Overflow)
- **Representação de inteiros** — sinal-magnitude × complemento de dois
- **Aritmética com inteiros** — adição/subtração, regra de overflow, multiplicação (Algoritmo de Booth) e divisão
- **Ponto flutuante** — notação científica binária e o padrão **IEEE 754** (binário32/64/128)
- **Aritmética em ponto flutuante** — alinhamento, bits de guarda, arredondamento, NaN e números subnormais
- **Impacto no software** — overflow de inteiros, Bug do Ano 2038, `0.1 + 0.2 ≠ 0.3`, desastre do Ariane 5

---

## 🧪 Laboratório interativo

[`atividade-pratica-cap10.html`](atividade-pratica-cap10.html) — uma página **100% offline** (sem dependências) com 4 simuladores:

| Simulador | O que faz |
|-----------|-----------|
| **Complemento de Dois** | Conversor com "caixa de valores"; clique nos bits e veja o peso negativo do bit de sinal |
| **Algoritmo de Booth** | Multiplicação passo a passo mostrando os registradores A, Q, Q₋₁ e M |
| **IEEE 754** | Decompõe um número de 32 bits em sinal · expoente (bias) · significando |
| **Armadilhas do Float** | Demonstra `0.1 + 0.2` e o overflow de inteiros (int32 wrap-around) |

### Como abrir
Basta dar duplo clique no arquivo ou abri-lo em qualquer navegador:

```bash
# Windows
start atividade-pratica-cap10.html

# macOS
open atividade-pratica-cap10.html

# Linux
xdg-open atividade-pratica-cap10.html
```

---

## 🎨 Slides

A apresentação foi montada no **Canva** (15 slides, estilo geométrico com imagens):
- 👉 [Abrir apresentação](https://www.canva.com/d/0OFHIZhPfBkUHN4)

## 📝 Notion

Material complementar do grupo no Notion:
- 👉 [Aritmética do Computador](https://app.notion.com/p/Aritm-tica-do-Computador-38e62d7b06be80c29762c6734d8d37e4?pvs=3)

---

## 📂 Conteúdo do repositório

| Arquivo | Descrição |
|---------|-----------|
| `atividade-pratica-cap10.html` | Laboratório interativo (atividade prática) |
| `Questionario_Cap10_Aritmetica.pdf` | Questionário avaliativo — 8 questões (A–D) + gabarito |
| `Seminarios_Praticas_e_Cronograma.pdf` | Guia de seminários, práticas e cronograma da disciplina |
| `PID Bases 6B SI.pdf` | Plano Interdisciplinar Docente (PID) |

> ℹ️ O livro-texto (Stallings, 10ª ed.) **não é versionado** neste repositório por questões de direitos autorais — veja a referência abaixo.

---

## ✅ Entregas do grupo

Conforme o guia da disciplina, cada grupo deve entregar: **seminário**, **atividade prática**, **questionário avaliativo** e o **material no Notion**. A avaliação considera o seminário + material (60%) e a participação individual (40%).

---

## 📚 Referência

STALLINGS, William. *Arquitetura e Organização de Computadores*. 10. ed. São Paulo: Pearson Education do Brasil, 2017. Capítulo 10 — Aritmética do Computador.
