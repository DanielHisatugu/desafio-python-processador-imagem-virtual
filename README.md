#### Processador de imagem virtual utilizando Python

Bootcamp Geração Tech Unimed-BH Ciência de Dados da [DiO](https://www.dio.me/) - criamos um pacote de processamento de imagens em python, utilizando o gerenciador de pacotes pip para instalação do pacote 'processamento_de_imagem'. Posteriormente, também disponibilizamos o projeto no repositório Pypi.

##### Funções do processador de imagem:

Processamento

- correspondência de histograma
- semelhança estrutural
- redimensionamento de imagem

Utilidade:

- ler imagem
- salvar imagem
- plotar imagem
- resultado da trama
- plotar histograma

##### Instalação do pacote do projeto

Utilize o gerenciador de pacote [pip](https://pip.pypa.io/en/stable/ ) para instalar o pacote do projeto

```
<<<<<<< HEAD
pip install processador-imagem-virtual-da
=======
pip install processador_imagem_virtual_da
>>>>>>> 096e893f567c320e1ff97a993e83e46e3e80d9ff
```

##### Uso

```
from package_name import file1_name
file1_name.my_function()

# Leitura da Imagem
imagem = io.ler_imagem("image.jpg")

# Carregando a Imagem
plot.plot_imagem(imagem)

# Combinações das Imagens
imagem_correspondente = combinacao.transferindo_histograma_dupla(imagem1, imagem2)
plot.plot_imagem(imagem_correspondente)
```

##### Autor

Daniel Hisatugu

##### Licença

[MIT](https://choosealicense.com/licenses/mit/)

