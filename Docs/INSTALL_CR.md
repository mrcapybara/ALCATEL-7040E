# Instalando custom recovery
  
### Atenção:
```diff
- A execução deste procedimento pode resultar em danos permanentes. 
- Não responsabilizo-me por qualquer dano causado, prossiga por sua conta e risco.  
- É imprescindível a instalação do UPDATE-4.4.2-7041D antes de iniciar este procedimento.
+ Senha para descomprimir os arquivos: mrcapybara
```
### Requisitos:

- <a href="/Ferramentas/SP-Flash-Tool-5.1420.03.7z">SP Flash Tool 5.1420.03</a>
- Atualização 4.4.2 instalada com <a href="/Docs/UPDATE_OFW.md">partição padrão</a> ou com <a href="/Docs/UPDATE_MOD_OFW.md">partição modificada</a>
- Custom recovery: <a href="/Extras/Custom-Recovery/TWRP-3.1.0-0.img">TWRP 3.1.0-0</a> ou <a href="/Extras/Custom-Recovery/CTR-3.3.img">CTR 3.3</a>
- Arquivo ```MT6582_Android_scatter``` da ROM:
  - Partição padrão: presente no ```UPDATE-4.4.2-7041D``` ou aqui
  - Partição modificada: exportado pelo ```MTK Partition Editor 0.5```
  
### Instalação:

1. Extraia os arquivos
2. Abra o arquivo ```flash_tool.exe```
3. Clique em ```OK``` no diálogo que será exibido

<p align="center"><img align="center" src="/Imagens/SPFT-01.PNG"/></p>

4. Clique em ```Scatter-loading``` e selecione o arquivo ```MT6582_Android_scatter```

<p align="center"><img align="center" src="/Imagens/SPFT-02.PNG"/></p>

5. Marque a caixa de seleção ```RECOVERY``` e selecione o custom recovery baixado

<p align="center"><img align="center" src="/Imagens/SPCR-02.PNG"/></p>

6. Desconecte o cabo USB e desligue o aparelho

7. Selecione ```Download Only``` na caixa de seleção e clique em ```Download```

<p align="center"><img align="center" src="/Imagens/SPCR-01.PNG"/></p>

9. Conecte o cabo USB e o processo de instalação iniciará automaticamente

<p align="center"><img align="center" width="700" src="/Imagens/SPCR-03.PNG"/></p>

10. Quando uma mensagem aparecer o processo haverá finalizado; basta desconectar o cabo USB e ligar o aparelho pressionando ```VOL_UP + POWER```

<p align="center"><img align="center" src="/Imagens/SPFT-06.PNG"/></p>

11. Pronto, sua custom recovery está instalada. Caso queira instalar a recovery original basta repetir o procedimento e utilizar o arquivo <a href="/Extras/Custom-Recovery/recovery-update-4.4.2.img">```recovery-update-4.4.2```</a>

<p align="center"><img align="center" width="200" src="/Imagens/SPCR-04.png"/></p>
