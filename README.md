# abnt-no-word

> Adicione estilos da ABNT ao Microsoft Word ™

👉 Dica rápida de como adicionar estilos da Associação Brasileira de Normas Técnicas (ABNT) ao Microsoft Word.

## Como fazer:

### Pelo Windows

1. Abra o Windows Explorer (atalho: tecla `Windows` + `E`).
2. Na barra de endereços, substitua o endereço atual por `%AppData%\Microsoft\Bibliography\Style` e tecle Enter. Isso fará abrir a pasta onde ficam os estilos do Microsoft Word. Veja a seção "Notas de compatibilidade" abaixo, caso contrário.
3. Baixe os arquivos `.XSL` disponíveis nesse projeto salvando na pasta acima. Links:
   * [`ABNT_Author.XSL`](https://github.com/thiagodp/abnt-no-word/raw/main/ABNT_Author.XSL)
   * [`ABNT_Num.XSL`](https://github.com/thiagodp/abnt-no-word/raw/main/ABNT_Num.XSL)
   * [`ABNT_Num_Alt.XSL`](https://github.com/thiagodp/abnt-no-word/raw/main/ABNT_Num_Alt.XSL)
4. Reinicie o Microsoft Word. Na aba "Referências", ao acessar a opção "Estilo" devem estar disponíveis os estilos instalados.

### Pelo Mac OS

1. Clique com o botão direito no ícone do Microsoft Word e escolha "Mostrar conteúdo do pacote".
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

### Notas de copyright
- Os estilos disponibilizados por esse projeto são parte de um projeto de código aberto (opensource) chamado [BibWord](https://archive.codeplex.com/?p=bibword).
- Microsoft Word, Windows, Community e Office 365 são marcas registradas da Microsoft Corporation.
- Mac OS é uma marca registrada da Apple Inc.

## Veja também 
- Baixe outros estilos em [codingo/BibWord](https://github.com/codingo/BibWord) (GitHub). Infelizmente o projeto BibWord original, [no CodePlex](https://archive.codeplex.com/?p=bibword), parece ter sido descontinuado.

## Aviso

_Esse projeto não se responsabiliza por quaisquer danos causados, diretamente ou indiretamente, pela realização dos procedimentos descritos ou uso dos arquivos providos. Faça ou use por sua conta e risco._
