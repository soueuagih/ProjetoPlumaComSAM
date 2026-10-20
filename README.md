# Projeto Pluma com SAM

Projeto desenvolvido para a disciplina de **Modelagem Computacional**, com o objetivo de utilizar o modelo de inteligência artificial SAM 2 (*Segment Anything Model*) para identificar e delimitar uma pluma de fumaça em uma imagem.

## Sobre o projeto

A atividade consiste em testar diferentes formas de orientar o modelo durante a segmentação, buscando identificar a fumaça e evitar que outras regiões da imagem, como o céu e os edifícios, sejam incluídas na máscara.

Foram realizados três experimentos:

1. Segmentação utilizando apenas uma caixa delimitadora.
2. Segmentação com caixa delimitadora e pontos positivos.
3. Segmentação com caixa delimitadora, pontos positivos e negativos.

## Resultados

Os três testes conseguiram identificar grande parte da pluma de fumaça, apresentando pequenas diferenças nos contornos.

O primeiro teste, utilizando apenas a caixa delimitadora, apresentou um resultado visual satisfatório. A inclusão de pontos adicionais não trouxe melhorias muito significativas para a imagem utilizada.

## Tecnologias utilizadas

- Python
- Google Colab
- SAM 2 (Meta)
- PyTorch
- NumPy e Matplotlib
