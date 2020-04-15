# Alterando o tamanho da partição do sistema

### Atenção:
```diff
- O programa MTK Partition Editor 0.5 poderá ser identificado como vírus.
- Caso não queira utilizá-lo baixe a partição já criada de 1GB.
```

### Alternativo:
- <a href="">Arquivos modificados para partição de 1GB</a>

### Requisitos:

- <a href="">MTK Partition Editor 0.5</a>
- Seguintes arquivos da ROM OFW 4.2.2:
  - ```MT6582_Android_scatter```
  - ```MBR```
  - ```EBR1```
  - ```EBR2```

### Instalação:

1. Inicie o programa e carregue os arquivos em seus respectivos campos
2. Altere a caixa de seleção para ```New Version```
3. Marque as caixas correspondentes a todos os arquivos selecionados

<p align="center" width="500"><img align="center" src="/Imagens/MTSYS-01.PNG"/></p>

4. Na aba ```Scatter``` será exibido todas as partições da ROM

5. Como exemplo, vamos aumentar a partição do sistema de 613 MB para 1GB e iremos reduzir o espaço para dados do usuário.

```diff
! Por padrão o sistema possui 613MB de tamanho.
! Ao aumentar o tamanho do sistema alguma outra partição deverá ser diminuída.
```

6. Note que entre a partição do sistema (```ANDROID```) e partição de dados (```USRDATA```) há a partição ```CACHE```. 
Portanto não podemos simplismente aumentar a partição do sistema, pois, ao fazer isto, ela irá sobreescrever toda a 
partição ```CACHE```.

<p align="center" width="500"><img align="center" src="/Imagens/MTSYS-02.PNG"/></p>

7. Neste caso vamos aumentar a partição ```CACHE``` primeiro. Como queremos 1GB para o sistema, teremos que aumentá-la em 411MB, 
pois: 1024MB - 613MB = 411MB.

8. Para altera o valor da partição basta clicar com o botão direito sobre a linha e clicar em ```Change Size```

9. Na nova janela que abrirá, altere o tamanho para 724MB, pois seu tamanho é de 313MB. Logo, 313MB + 411MB = 724MB.
Posteriormente clique em ```OK```

<p align="center" width="500"><img align="center" src="/Imagens/MTSYS-03.PNG"/></p>

10. Note que a partição ```CACHE``` aumentou e a partição ```USRDATA``` reduziu

11. Agora vamos aumentar o sistema para o tamanho desejado, neste caso, 1GB. O processo é similar ao item 8, porém agora 
clicando na partição ```ANDROID```

<p align="center" width="500"><img align="center" src="/Imagens/MTSYS-04.PNG"/></p>

12. Note que o tamanho do sistema agora é de 1GB e o tamanho do ```CACHE``` voltou ao que estava por padrão

13. Salve os arquivos clicando em ```File``` depois em ```Save```. Clique em ```SIM``` na mensagem que aparecer. 

14. Pronto, os arquivos estão prontos para serem gravados no aparelho











