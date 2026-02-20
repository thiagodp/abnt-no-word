# abnt-no-word

> Adicione estilos da ABNT ao Microsoft Word ™

👉 Como utilizar estilos da Associação Brasileira de Normas Técnicas (ABNT) no Microsoft Word.


## Como adicionar estilos:

Este projeto mantém arquivos XSL que podem ser adicionados ao pacote Microsoft Office para que seja possível usar estilos da ABNT.
Basta baixá-los, colocá-los no diretório correto e reabrir o Word para que seja possível visualizá-los. Eles irão aparecer na opção "Estilo" da aba "Referências".

### Pelo Windows

1. Abra o Windows Explorer (atalho: tecla `Windows` + `E`).
2. Na barra de endereços, substitua o endereço atual por `%AppData%\Microsoft\Bibliography\Style` e tecle Enter. Isso fará abrir a pasta onde ficam os estilos do Microsoft Word. Veja a seção "Notas de compatibilidade" abaixo, caso contrário.
3. Baixe os arquivos `.XSL` disponíveis nesse projeto salvando na pasta acima. Links:
   * [`ABNT_Author.XSL`](https://github.com/thiagodp/abnt-no-word/raw/main/ABNT_Author.XSL)
   * [`ABNT_Num.XSL`](https://github.com/thiagodp/abnt-no-word/raw/main/ABNT_Num.XSL)
   * [`ABNT_Num_Alt.XSL`](https://github.com/thiagodp/abnt-no-word/raw/main/ABNT_Num_Alt.XSL)
4. Reinicie o Microsoft Word. Na aba "Referências", ao acessar a opção "Estilo" devem estar disponíveis os estilos instalados.

### Pelo Mac OS

1. Clique com o botão direito no ícone do Microsoft Word e escolha "Mostrar conteúdo do pacote". Isso fará abrir a pasta onde fica o Microsoft Word.
2. Entre na subpasta `Contents/Resources/Style/`.
3. Baixe os arquivos `.XSL` disponíveis nesse projeto salvando na pasta acima. Links:
   * [`ABNT_Author.XSL`](https://github.com/thiagodp/abnt-no-word/raw/main/ABNT_Author.XSL)
   * [`ABNT_Num.XSL`](https://github.com/thiagodp/abnt-no-word/raw/main/ABNT_Num.XSL)
   * [`ABNT_Num_Alt.XSL`](https://github.com/thiagodp/abnt-no-word/raw/main/ABNT_Num_Alt.XSL)
4. Reinicie o Microsoft Word. Na aba "Referências", ao acessar a opção "Estilo" devem estar disponíveis os estilos instalados.

## Notas de compatibilidade

* Os *arquivos* .XSL disponibilizados são compatíveis com o Microsoft Word 2007 em diante.
* O endereço descrito acima para Windows foi testado com o Microsoft Word para Office 365 e sabe-se que também funciona com o Microsoft Word 2019 ou posterior.
* Diretórios de outras versões do Microsoft Word para Windows, [segundo o forum Microsoft Community](https://answers.microsoft.com/pt-br/msoffice/forum/all/como-adicionar-o-estilo-bibliogr%C3%A1fico-abnt/b7903674-d1b8-4ba1-8714-76c912949fac):
  * Word 2007: `%programfiles%\Microsoft Office\Office12\Bibliography\Style`
  * Word 2010: `%programfiles%\Microsoft Office\Office14\Bibliography\Style`
  * Word 2013: `%userprofile%\AppData\Roaming\Microsoft\Bibliography\Style`
  * Word 2016: `%AppData%\Microsoft\Templates\LiveContent\16\Managed\Word Document Bibliography Styles`
  * Word 2019: `%AppData%\Microsoft\Bibliography\Style`
  * Word para Microsoft 365: `%AppData%\Microsoft\Bibliography\Style`

## Versões

> 👉 [Saiba sobre as últimas atualizações realizadas](https://github.com/thiagodp/abnt-no-word/commits/main/)

- **Atual** - atualizada com NBR 14724:2025 (2025.04.01), NBR 6023:2018 (2018.11.14) e NBR 10520:2023 (2023.07.19).
- [v2023](https://github.com/thiagodp/abnt-no-word/releases/tag/v2023) - Incorpora a NBR 10520:2023 (2023.07.19).
- [v2022](https://github.com/thiagodp/abnt-no-word/releases/tag/v2022) - Versão antes da [NBR 10520/2023](https://github.com/thiagodp/abnt-no-word/pull/1).


## Veja também

- Baixe outros estilos em [codingo/BibWord](https://github.com/codingo/BibWord) (GitHub). Infelizmente o projeto BibWord original, [no CodePlex](https://archive.codeplex.com/?p=bibword), parece ter sido descontinuado.

## Observações e licença

- _Esse projeto não se responsabiliza pela realização dos procedimentos descritos ou pelo uso dos arquivos providos. Faça ou use por sua conta e risco._
- Windows, Word e Office 365 são marcas registradas da Microsoft Corporation. Mac OS é marca registrada da Apple Inc.
- Este projeto é regido pela [licença MIT](LICENSE).

