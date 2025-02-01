# Redução de Dimensionalidade em Imagens para Redes Neurais
Este projeto converte uma imagem do castelo Hohenzollern colorida (RGB) para tons de cinza e, em seguida, a binariza (preto e branco). Desenvolvido para o Google Colab, o código é simples e eficiente para processamento básico de imagens.

# Funcionalidades
Conversão para Tons de Cinza:

* Usa a fórmula: gray = 0.2989 * R + 0.5870 * G + 0.1140 * B.

* Gera uma imagem em escala de cinza (valores de 0 a 255).

# Binarização:
 * Converte a imagem em tons de cinza para preto e branco usando um limiar (threshold).

 * Pixels acima do limiar viram branco (255); abaixo, preto (0).

# Visualização:

Exibe três imagens lado a lado: original, tons de cinza e binarizada.

* Bibliotecas Utilizadas:

 * numpy: Para manipulação de arrays.

 * matplotlib.pyplot: Para exibição das imagens.

 * PIL (Pillow): Para carregar a imagem.
