# Modelo de Relatório de Laboratório - LaTeX (IEEEtran)

Este repositório contém um modelo não oficial em LaTeX para a elaboração de pré-relatórios e relatórios de laboratório, utilizando a classe **IEEEtran**.

O template foi desenvolvido para seguir normas técnicas comuns em cursos de engenharia (especialmente na UnB), facilitando a escrita de experimentos com estrutura acadêmica profissional.

### 📄 Exemplo de Resultado

Você pode visualizar o documento final compilado (com exemplos de gráficos, circuitos e textos) no link abaixo:

🔗 **[Visualizar Relatório Compilado (Resultado.pdf)](https://github.com/rubensbraz/rel_latex/blob/master/Resultado.pdf)**

---

## 🚀 Funcionalidades do Modelo

Este modelo baseado na classe `IEEEtran` já vem configurado com:

* **Formatação IEEE:** Utiliza o padrão de colunas e fontes da classe `IEEEtran` (`10pt`, `final`, `a4paper`).
* **Suporte a Idioma:** Configurado para Português (Brasil) com hifenização correta (`babel`, `hyphenat`).
* **Elementos Gráficos:** Suporte nativo para inclusão de imagens (`graphicx`), legendas (`caption`) e tabelas avançadas (`mdwtab`).
* **Códigos Fonte:** Pacote `listings` incluído para inserir trechos de código de programação no relatório.
* **Referências Bibliográficas:** Configurado para uso do BibTeX com estilo IEEE.

## 📂 Estrutura dos Arquivos

* **`main.tex`**: O arquivo mestre do projeto. Contém todo o código LaTeX, estrutura do texto e bibliografia.
* **`Resultado.pdf`**: Arquivo PDF gerado a partir da compilação do script, servindo de referência visual.
* **`imagens/`**: Pasta (necessária criar) onde você deve salvar as figuras (JPG, PNG, PDF) citadas no texto.
## 🛠️ Como Utilizar

### Opção 1: Overleaf (Online)

1.  Faça um cópia do projeto e começe a editar: https://www.overleaf.com/read/ncxmgshmrnzz

### Opção 2: Editor Local (VS Code / TeXShop)

1.  Clone este repositório ou baixe os arquivos.
2.  Certifique-se de ter uma distribuição LaTeX instalada (TeX Live, MiKTeX, etc.).
3.  Abra o arquivo `script.tex` e compile.

## 📝 Editando o Relatório

Para personalizar o relatório com seus dados, edite o início do arquivo `main.tex`:

```latex
% Título do Experimento
\title{Experiência Nº X: Título da Experiência}

% Autores e Afiliação
\author{
    Seu Nome - Matrícula\\
    Nome do Colega - Matrícula\\
    Departamento de Engenharia Elétrica - ENE\\
    Universidade de Brasília - UnB
}
```

Inserindo Figuras:

```latex
\begin{figure}[ht!]
    \captionsetup{justification=centering}
    \centering
    \includegraphics[width=0.8\linewidth]{imagens/sua_imagem.png}
    \caption{Legenda da imagem.}
    \label{fig:exemplo}
\end{figure}
```

## 📄 Licença

Este modelo é de uso livre. Desenvolvido por Rubens Braz.
