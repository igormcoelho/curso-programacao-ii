## Programação II

Materiais gerais de Programação II do [Prof. Igor Machado Coelho](https://igormcoelho.github.io), bem como suas respectivas aplicações em períodos recentes.

![last-commit](https://img.shields.io/github/last-commit/igormcoelho/curso-programacao-ii)

Lista completa de módulos (PREVISTOS) no repositório:

- Introdução à linguagem C
   - TIPOS PRIMITIVOS DE DADOS; TIPOS ESTRUTURADOS DE DADOS; OPERADORES ARITMÉTICOS, CONDICIONAIS, LÓGICOS E DE ATRIBUIÇÃO; ENTRADA E SAÍDA PADRÃO; ESTRUTURAS DE SELEÇÃO E REPETIÇÃO; PROCEDIMENTOS E FUNÇÕES; ESCOPO E VARIÁVEIS GLOBAIS
   - Tópico avançado: otimização de código e flags de compilação
- Gerência de Memória
   - ALOCAÇÃO ESTÁTICA; PONTEIROS
   - PASSAGEM DE PARÂMETROS POR VALOR E POR REFERÊNCIA (tópico híbrido em C/C++)
   - Alocação Dinâmica (?) - (tópico híbrido em C/C++)
- PROGRAMAÇÃO COM MÓDULOS
   - Tópico avançado: GNU make e bazel
- RECURSIVIDADE (EDSI?)
- TAD
   - Conceitos e Implementações diversas
   - Implementações de Listas
      - Tópico avançado: Sacos e Listas (ED)
      - Tópico avançado: Fila e Pilha (ED)
   - Matriz
- ARQUIVOS
   - Tópico avançado: leitura de arquivos de grande porte

Materiais PDF-HTML:

- TBD


***Observação:*** **alguns módulos só são oferecidos para cursos específicos.*

-------

## Cursos recentes

- Programação de Computadores II para Sistemas de Informação - TCC00218
   * [Graduação UFF 2021.1](./uff-pc2si-2021-1) (jun./2021-set./2021)
   * Instituto de Computação (IC) - Universidade Federal Fluminense (UFF)

-------

## Sobre gravações

Gravações disponibilizadas no YouTube e Classroom foram feitas com OBS (obrigado pelas dicas Mateus Nazário). Algumas dicas:

- https://medium.com/@igormcoelho/dicas-para-obs-no-linux-para-google-meet-8ac102972183

Utilizei o Okular para marcação do PDF (obrigado Matheus Nohra Haddad pelas dicas).

## Como esses slides foram feitos?

Estes slides foram feitos em `markdown` e `pandoc` (super fácil!) de acordo com o tutorial [ilectures-pandoc](https://github.com/igormcoelho/ilectures-pandoc).

Basicamente, é necessário instalar o pandoc e, opcionalmente, copiar alguns filtros úteis do tutorial (dois arquivos python). Então, é possível gerar, a partir do `markdown`, uma versão PDF LaTeX+Beamer, e outra web utilizando RevealJS. O tutorial explica tudo em detalhes.

O mais legal é que a edição do slide tem uma visualização em tempo real, com plugins disponíveis para editores populares como Atom e VSCode.
Uma demonstração foi colocada no site do ilectures: [https://github.com/igormcoelho/ilectures-pandoc#demonstrations](https://github.com/igormcoelho/ilectures-pandoc#demonstrations).


### Deps

Pandoc + LaTeX

`python3 -m pip install pandoc-source-exec`
`python3 -m pip install pandoc-latex-color`

[pandoc 2.10.1](https://github.com/jgm/pandoc/releases/tag/2.10.1)



### Licença CC-BY 4.0

Você pode: (Share) copiar e redistribuir esse material em qualquer formato; (Adapt) adaptar esse material, mesmo que para uso comercial.

Você deve: (Attribution) dar crédito apropriado, bem como um link para o original e a indicação das mudanças que você fez.

Veja licença original [CreativeCommons CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

```
curso-programacao-ii (c) by Igor M. Coelho

curso-programacao-ii is licensed under a
Creative Commons Attribution 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by/4.0/>.
```


Copyleft 2021
