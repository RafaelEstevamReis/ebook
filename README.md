# ebook
Livro de Impressão 3D em português, escrito usando a linguagem markup asciidoc (depois de convertido do original em formato libreoffice writer). Para visualizar a edição "renderizada" deste livro em PDF, você precisa usar o [asciidoctor-pdf](https://github.com/asciidoctor/asciidoctor-pdf), que por sua vez exige o pacote asciidoctor. Outros formato de saída em breve serão suportados.

No momento o repositório *não está pronto para uso*. O arquivo-texto do livro ainda está sendo modificado para seguir o documento .odt. Em especial as legendas das imagens terão que ser todas refeitas.

Para a conversão do .adoc para qualquer formato, devem-se usar os flags -a stem (para permitir extensão STEM) e -r asciidoctor-mathematical (para permitir a transformação das fórmulas latex em figuras embutidas).
