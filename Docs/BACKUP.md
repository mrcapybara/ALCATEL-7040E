# Fazendo backup da ROM, IMEI e NVRAM

### Atenção:
```diff
- A execução deste procedimento pode resultar em danos permanentes. 
- Não responsabilizo-me por qualquer dano causado, prossiga por sua conta e risco.
```
### Requisitos:

- Atualização 4.4.2 instalada com <a href="/Docs/UPDATE_OFW.md">partição padrão</a> ou com <a href="/Docs/UPDATE_MOD_OFW.md">partição modificada</a>
- <a href="/Docs/INSTALL_ROOT.md">Aparelho com ROOT</a>
- <a href="/Ferramentas/MTK-Droid-Tools-2.5.3.7z">MTK Droid Tools</a>

### Instalação:

1. Habilite o modo desenvolvedor e a depuração USB
2. Abra o arquivo ```MTKdroidTools.exe```
3. Após o programa iniciar, conecte o cabo USB e permita a depuração USB no aparelho
4. Clique em ```ROOT```

<p align="center" width="600"><img align="center" src="/Imagens/MTBK-01.PNG"/></p>

5. Clique em ```SIM``` no diálogo que aparecer

<p align="center" width="600"><img align="center" src="/Imagens/MTBK-02.PNG"/></p>

6. Permita que a aplicação tenha acesso ROOT no aparelho e aguarde
7. Após o carregamento o status da conexão deverá está conforme a imagem

<p align="center" width="600"><img align="center" src="/Imagens/MTBK-03.PNG"/></p>

8. Para o backup do IMEI e da NVRAM clique em ```IMEI/NVRAM``` e em ```Backup``` na janela que abrirá

<p align="center" width="600"><img align="center" src="/Imagens/MTBK-04.PNG"/></p>

9. Para o backup dos demais dados: clique na aba ```root, backup, recovery``` e depois em ```Backup``` (este processo poderá demorar bastante)

<p align="center" width="600"><img align="center" src="/Imagens/MTBK-05.PNG"/></p>

10. Pronto, todos os arquivos estarão salvos nas pastas de backups do programa

