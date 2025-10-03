# CALPES – Calculadora de Leiturabilidade em Português para Materiais Educativos em Saúde

A **CALPES (Calculadora de Leiturabilidade em Português para Materiais Educativos em Saúde)** é uma ferramenta desenvolvida para avaliar a leiturabilidade de textos em português, baseada no **Índice de Flesch adaptado**.  

Ela foi criada com foco na análise de materiais educativos em saúde, mas pode ser utilizada em diferentes contextos para verificar a complexidade de leitura de um texto.

🌐 Versão online: [Acesse aqui](https://borgestefani.github.io/calpes/)  

---

## 🔢 Fórmula utilizada

O índice de Flesch adaptado ao português é calculado como:

Índice = 248,835 − (1,015 × (palavras/frases)) − (84,6 × (sílabas/palavra))


- **Palavras/frases** = número médio de palavras por frase  
- **Sílabas/palavra** = número médio de sílabas por palavra  

---

## 🛠️ Como usar

1. Cole ou digite o texto que deseja avaliar.  
2. Clique em **Calcular**.  
3. O sistema exibirá o número de frases, palavras, sílabas e o **índice de leiturabilidade**.  
4. Também é possível inserir manualmente as contagens (se você já tiver os valores).  

---

## 📊 Interpretação sugerida

- **>75 a 100** → Muito fácil (nível fundamental, 1º ao 5º ano)  
- **>50 a 75** → Fácil (nível fundamental, 6º ao 9ª ano)  
- **>25 a 50** → Difícil (nível médio)  
- **0 a 25** → Muito difícil (nível superior)  

---

## 📥 Resultados

- É possível **baixar os resultados em Excel**.  Os botões “Exportar todas” e “Baixar resultados” geram arquivos em formato de planilha. Por padrão, o formato é .xlsx. Caso a biblioteca externa não esteja disponível, o sistema exporta em .csv, que pode ser aberto normalmente no Excel, Google Sheets ou LibreOffice. Isso garante que você sempre consiga salvar seus resultados, independentemente da disponibilidade de bibliotecas externas.
- Também é possível **copiar um resumo em texto** da análise em tela, para colar em relatórios ou artigos.  
  
---

## 📖 Histórico de desenvolvimento

A CALPES foi originalmente desenvolvida em VBA (Visual Basic for Applications) para Excel, com o objetivo de analisar a legibilidade de materiais educativos em saúde.

Posteriormente, o código foi adaptado e transformado em uma aplicação web (HTML, CSS e JavaScript) com apoio do ChatGPT (OpenAI, versão GPT-5), mantendo a lógica original e ampliando a acessibilidade da ferramenta para uso direto no navegador.

---

## 📄 Citação

Se utilizar a CALPES em trabalhos acadêmicos, indique a seguinte referência:

BORGES, S.S. CALPES – Calculadora de Leiturabilidade em Português para Materiais Educativos em Saúde (versão web). 2025.
Disponível em: https://borgestefani.github.io/calpes/

---

## 📜 Licença

Este projeto é distribuído sob a Licença MIT (MIT License).
Você pode usar, modificar e distribuir livremente, desde que mantenha a atribuição.  

---

✉️ Dúvidas ou sugestões: envie um e-mail para borgestefani@gmail.com



