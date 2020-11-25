# Livro
Repositório com meu livro de matemática.

O livro está escrito em TEX. Existe um arquivo principal, chamado "livro.tex", em que a estrutura do livro está escrita. O arquivo é separado em duas partes, como qualquer arquivo LATEX: o "Preâmbulo" e o "Documento". No preâmbulo estão informações gerais de estilo do documento e título etc. Os pacote "estilomeu.sty" e "matematica.sty" são usados.

O ducumento consiste no livro em si. O livro é separado em vários arquivos que são incluídos no "livro.tex" pelo comando "\include{<arquivo>}". Esse comando permite organizar melhor o livro e separar as partes do livro em diferentes arquivos. No preâmbulo, pode-se escolher quais arquivos compilar num determinado momento de trabalho indicando o nome do arquivo no comando "\includeonly{}". (Para mais informações, conferir https://en.wikibooks.org/wiki/LaTeX/Modular_Documents .) Só disponibilizei os arquivos principais de texto aqui no repositório.

O livro consiste de "Capa", "Elementos Pré-Textuais", "Elementos Textuais" e "Elementos Pós-Textuais". Os elementos textuais estão separados em três partes: "Conjuntos", "Álgebra", "Geometria".
