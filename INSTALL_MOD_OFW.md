
# Instalando OFW 4.2.2 com tamanho de partição alterada

### Atenção:
```diff
- A execução deste procedimento pode resultar em danos permanentes. 
- Não responsabilizo-me por qualquer dano causado, prossiga por sua conta e risco.
- Ao executar este procedimento todos os dados do dispositivo serão perdidos.
+ Senha para descomprimir os arquivos: mrcapybara
```
### Requisitos:

- <a href="">SP Flash Tool 5.1420.03</a>
- <a href="">OFW 4.2.2</a>
- Arquivos de partição modificados:
  - ```MT6582_Android_scatter```
  - ```MBR```
  - ```EBR1```
  - ```EBR2```

### Instalação:

1. Extraia os arquivos da OFW 4.2.2
2. Substitua os arquivos ```MT6582_Android_scatter```, ```MBR```, ```EBR1``` e ```EBR2``` originais pelos arquivos modificados
3. Abra o arquivo ```flash_tool.exe```
4. Clique em ```OK``` no diálogo que será exibido

<p align="center"><img align="center" src="/Imagens/SPFT-01.PNG"/></p>

5. Clique em ```Scatter-loading``` e selecione o arquivo ```MT6582_Android_scatter``` que está na pasta extraída da ROM

<p align="center"><img align="center" src="/Imagens/SPFT-02.PNG"/></p>

6. Verifique se todos os item carregados possuem o caminho correto, caso contrário, clique na linha correspondente e selecione o arquivo equivalente presente na pasta extraída da ROM.

7. Marque todas as caixas de seleção

<p align="center"><img align="center" src="/Imagens/MODSPFT-01.PNG"/></p>

8. Desconecte o cabo USB e desligue o aparelho

9. Selecione ```Format All + Download``` na caixa de seleção e clique em ```Download```

<p align="center"><img align="center" src="/Imagens/SPFT-04.PNG"/></p>

10. Conecte o cabo USB e o processo de instalação iniciará automaticamente

<p align="center"><img align="center" width="700" src="/Imagens/MODSPFT-02.PNG"/></p>

11. Quando uma mensagem aparecer o processo haverá finalizado; basta desconectar o cabo USB e ligar o aparelho. 

<p align="center"><img align="center" src="/Imagens/SPFT-06.PNG"/></p>
