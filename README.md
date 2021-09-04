# Projeto de Deteccao de Cancer do modulo de Redes Neurais 

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/RicardoNagamatsu/Detec-o_C-ncer---Redes_Neurais/blob/master/LICENSE) 

# Sobre o projeto

https://www.kaggle.com/rychardguedes/isic-20172018

Contextualização

A PyCoders Ltda., cada vez mais especializada no mundo da Inteligência Artificial e
Ciência de Dados, foi procurada por uma empresa de Diagnóstico Médico por
Imagem para auxiliar os médicos em suas decisões. O case passado pela
contratante se refere a detectar câncer de pele por meio de imagens de lesões.

Base de Dados
Será utilizada uma base de dados com imagens de lesões na pele, sejam elas
benignas ou malignas. Existem também arquivos .csv descrevendo as variáveis
respostas das imagens. O download das imagens usadas estão no https://www.kaggle.com/rychardguedes/isic-20172018; assim como os
arquivos descritivos, indicando quais imagens são treino, teste e validação.

Do ISIC 2017, devem ser utilizadas as imagens de Nevus e Melanoma. Para
complementar a base, rebalanceando as classes, devem ser utilizadas as imagens
de Melanoma do ISIC 2018. 

Projeto feito em squad, onde fizemos o carregamento e tratamento dos dados. Juntamos as bases de dados com os dados de imagens, para treino, teste e validação.
Foi criado o gerador, depois o Transfer Learning com o modelo VGG16 e acrescentado algumas camadas e rodamos o modelo. Depois fizemos um Fine Tuning para refinar o modelo.
Após isso fizemos o mesmo processamento para os dados de teste e rodamos os dados de teste no modelo e pegamos as predições.


# Tecnologias utilizadas
## Python - Colab
- Pandas
- Tensorflow - keras
- Numpy
- CV2
- Matplotlib


# Autor

Ricardo Pacheco Nagamatsu

https://www.linkedin.com/in/ricardo-pacheco-nagamatsu-580a85135/
