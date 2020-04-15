# Atualizando OFW 4.2.2 para OFW 4.4.2 com tamanho de partição alterada
  
### Atenção:
```diff
- A execução deste procedimento pode resultar em danos permanentes. 
- Não responsabilizo-me por qualquer dano causado, prossiga por sua conta e risco.  
- Este update foi projetado para o modelo 7041D, entretanto é possível instalá-lo no 7040E. 
- É imprescindível a instalação da ROM OFW 4.2.2 antes de iniciar este procedimento.
- Os arquivos MBR, EBR1, EBR2 e MT6582_Android_scatter deverão ser o mesmos utilizados no item acima.
+ Senha para descomprimir os arquivos: mrcapybara
```
### Requisitos:

- <a href="">SP Flash Tool 5.1420.03</a>
- <a href="">Arquivos do UPDATE 4.4.2</a>
- <a href="INSTALL_MOD_OFW.md">ROM OFW 4.2.2 com partição modificada instalada</a>
- Arquivos de partição modificados (os mesmos utilizados na instalação do item acima):
  - ```MT6582_Android_scatter```
  - ```MBR```
  - ```EBR1```
  - ```EBR2```

### Instalação:

1. Extraia os arquivos do UPDATE 4.4.2
2. Substitua os arquivos ```MT6582_Android_scatter```, ```MBR```, ```EBR1``` e ```EBR2``` originais pelos arquivos modificados
3. Abra o arquivo ```flash_tool.exe```
4. Clique em ```OK``` no diálogo que será exibido

<p align="center"><img align="center" src="/Imagens/SPFT-01.PNG"/></p>

4. Clique em ```Scatter-loading``` e selecione o arquivo ```MT6582_Android_scatter``` que está na pasta extraída do UPDATE

<p align="center"><img align="center" src="/Imagens/SPFT-02.PNG"/></p>

5. Marques as caixas de seleção de acordo com a imagem e verifique se os caminhos delas estão de acordo com os arquivos extraídos. 
Caso contrário, clique na linha correspondente e selecione o arquivo equivalente presente na pasta extraída do UPDATE.

<p align="center"><img align="center" src="/Imagens/MODSPUP-01.PNG"/></p>

6. Desconecte o cabo USB e desligue o aparelho

7. Selecione ```Download Only``` na caixa de seleção e clique em ```Download```

<p align="center"><img align="center" src="/Imagens/SPUP-02.PNG"/></p>

9. Conecte o cabo USB e o processo de instalação iniciará automaticamente

<p align="center"><img align="center" width="700" src="/Imagens/MODSPUP-02.PNG"/></p>

10. Quando uma mensagem aparecer o processo haverá finalizado; basta desconectar o cabo USB e ligar o aparelho. 

<p align="center"><img align="center" src="/Imagens/SPFT-06.PNG"/></p>

- #### Informações da ROM Instalada:

<p align="center"><img align="center" width="200" src="/Imagens/SPUP-04.png"/></p>
