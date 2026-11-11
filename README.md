# Verifique seu download do ProjetoQuant

Este é o canal de verificação de arquivos do ProjetoQuant mantido por
**Jdalpiva**. Consulte este endereço para obter a chave pública oficial e
confirmar a revisão da entrega assinada.

## Chave pública oficial

Publicada em **11/11/2026**. Baixe [ProjetoQuant.pub](ProjetoQuant.pub) neste
repositório. Este é o arquivo público usado para conferir as assinaturas.

SHA-256 do arquivo `ProjetoQuant.pub`:

```text
5b383cb33f19ba67f99021795e4e5249725f47bd22351b581883af40c5434230
```

A chave já foi usada para assinar uma prévia interna. A entrega comercial
está em preparação; a revisão vigente e sua lista assinada serão anunciadas
aqui quando a entrega estiver concluída e aprovada.

## Antes de abrir o instalador

1. Abra este canal pelo perfil [jdalpiva](https://github.com/jdalpiva) e confira
   a revisão informada para a entrega.
2. Reúna o instalador do seu sistema, `SHA256SUMS.txt` e
   `SHA256SUMS.txt.minisig` em uma pasta. Obtenha a chave pública neste canal.
3. Use o Minisign para verificar a assinatura da lista com a chave oficial.
   O comentário assinado deve identificar a mesma revisão anunciada neste
   canal. O comando de verificação usa somente a chave pública:

   ```bash
   minisign -V -H -m SHA256SUMS.txt -p ProjetoQuant.pub
   ```

   No Windows, execute `minisign.exe` na pasta correspondente. Se a assinatura
   for inválida, interrompa a instalação.
4. Calcule o SHA-256 do instalador e compare o valor com a linha que contém
   seu nome na lista assinada. No Windows, use `Get-FileHash -Algorithm SHA256`
   no PowerShell. No Linux, use `sha256sum`. Extraia o instalador após
   confirmar a assinatura e a correspondência do arquivo.
   [Documentação e downloads do Minisign](https://jedisct1.github.io/minisign/).

Se a verificação falhar, interrompa a instalação e confira a revisão e o
arquivo obtido.

## Histórico da chave

- **11/11/2026:** primeira publicação da chave oficial.

Uma substituição será registrada neste canal com a identificação da chave
anterior e das entregas às quais se aplica. A chave privada e a senha ficam
sob guarda do responsável; o cliente usa a chave pública para conferir os
downloads.
