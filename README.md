# Caminhos Analíticos e Construção de Soluções em EDP II 📚

Este repositório contém um registro pessoal de estudos e um processo de aprofundamento na disciplina de **Equações Diferenciais Parciais II (EDP II)** do semestre **2026.1**, do Programa de Pós-Graduação em Matemática (**PPGMAT**) da **UFCG**, ministrada pelo **Professor Marco Aurelio Souto**.

## 🎯 Filosofia do Projeto

Diferente de um solucionário convencional, este trabalho é concebido como um **estudo de construção**. A premissa fundamental é que a resolução de um problema matemático não deve ser vista apenas como a entrega de um resultado, mas como a materialização de um raciocínio.

Busco aqui visualizar a construção de cada solução, refletindo sobre o **"porquê"** e o **"para que"** de cada etapa. Compreendo que cada questão, para além do resultado final, carrega fatos matemáticos essenciais que servem de alicerce para a construção do pensamento matemático.

A estruturação do projeto segue rigorosamente o fluxo das listas de exercícios da disciplina, fundamentando-se nas discussões em sala de aula e nas referências bibliográficas de:
- **Lawrence C. Evans** (*Partial Differential Equations*)
- **Haim Brezis** (*Functional Analysis, Sobolev Spaces and Partial Differential Equations*)
- **Gilbarg & Trudinger** (*Elliptic Partial Differential Equations of Second Order*)

---

## 🪜 Metodologia de Construção (A Escada Analítica)

Para garantir a clareza e a reprodutibilidade do raciocínio, cada problema é resolvido seguindo um fluxo modular, desenhado como uma escada de complexidade:

1. **Enunciado da Questão:** Transcrição literal do problema para definição do desafio.
2. **Análise e Fundamentação Teórica:** Identificação dos fatos matemáticos envolvidos e a base teórica necessária.
3. **Estratégia para Solução:** O roteiro lógico e o plano de ataque antes da execução formal.
4. **Solução:** O desenvolvimento exaustivo e rigoroso, sem omissões e com referências cruzadas.
5. **Síntese da Construção:** Um fechamento reflexivo sobre a lógica da montagem e a lição extraída.

---

## ⚙️ Guia Técnico e Compilação

O projeto foi desenvolvido em $\LaTeX$ utilizando o motor **LuaLaTeX**, visando a máxima qualidade tipográfica e modularidade.

### 🛠️ Estrutura de Compilação
Para garantir a renderização correta da bibliografia e do sumário, a sequência de compilação recomendada é:
`LuaLaTeX` $\rightarrow$ `Biber` $\rightarrow$ `LuaLaTeX` $\rightarrow$ `LuaLaTeX`

*Dica: Recomenda-se o uso do `latexmk` no TeXstudio para automatizar este processo.*

### 🧩 Modularidade com `subfiles`
Para otimizar o tempo de compilação, utilizei o pacote `subfiles`. Isso permite que você compile:
- **O Documento Completo:** Compilando o arquivo principal `caminhos_analiticos_edp.tex`.
- **Um Tópico Específico:** Compilando diretamente o arquivo `.tex` da seção desejada (ex: `solucao_eqonda.tex`), herdando automaticamente todo o preâmbulo.

### 👁️ Customização de Visibilidade
No arquivo `preambulo.tex`, implementei "interruptores" lógicos que permitem gerar versões diferentes do PDF (estudo aprofundado vs. versão resumida):

- `\setbool{showanalise}{true/false}` $\rightarrow$ Controla a exibição da **Análise e Fundamentação**.
- `\setbool{showsintese}{true/false}` $\rightarrow$ Controla a exibição da **Síntese da Construção**.

---

## 📜 Licença e Contribuições

Este material é distribuído sob a **Licença CC BY-NC-SA 4.0** (Atribuição-NãoComercial-CompartilhaIgual).

Sugestões, críticas ou correções são muito bem-vindas e podem ser enviadas via:
👉 [Formulário de Observações](https://forms.gle/UcBrKWL7YxdXCX7y9)

---
Campina Grande - PB, 2026
