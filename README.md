# arquivos-latex
Lembretes de como compilar arquivos latex

Um documento LaTeX, salvo como um arquivo .tex, deve ser compilado para transformá-lo em um documento legível. Um arquivo .tex compilado produzirá um documento .dvi, .ps (PostScript) ou .pdf. A saída padrão da maioria das distribuições TeX é .dvi, mas documentos .ps ou .pdf também são relativamente fáceis de produzir.
There two general ways to compile a LaTeX document:

- Usando um editor/compilador LaTeX
- Usando a linha de comando/terminal
- Usando um editor/compilador LaTeX

Um editor LaTeX como o TeXmaker ou TeXworks inclui a funcionalidade de compilar um documento LaTeX com o apertar de um botão. O editor específico que está sendo usado deve incluir informações sobre como isso é feito, então é melhor consultar diretamente o site do editor escolhido para obter informações sobre sua operação.

## Usando a linha de comando/terminal
Os comandos listados abaixo devem funcionar igualmente bem em um ambiente Windows, Unix/Linux ou Mac.

Na linha de comando ou terminal, navegue primeiro até o local onde seu arquivo `.tex` está salvo. 
Os seguintes comandos podem ser usados:

**latex** [nome do arquivo].tex irá compilar [nome do arquivo].tex e gerar o arquivo [nome do arquivo].dvi
**pdflatex** [nome do arquivo].tex irá compilar [nome do arquivo].tex e gerar o arquivo [nome do arquivo].pdf



Você também pode usar a linha de comando/terminal para converter entre diferentes tipos de arquivo. 
Por exemplo:

**dvips** -o [nome do arquivo].ps [nome do arquivo].dvi converterá [nome do arquivo].dvi em um arquivo PostScript chamado [nome do arquivo].ps
**dvipdfm** [nome do arquivo].dvi converterá [nome do arquivo].dvi em um arquivo PDF chamado [nome do arquivo].pdf
