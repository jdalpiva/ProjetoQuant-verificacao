# Verifique seu download do ProjetoQuant

Este é o canal de verificação de arquivos do ProjetoQuant mantido por
**Jdalpiva**. Consulte este endereço para obter a chave pública oficial e
confirmar a revisão da entrega assinada.

A primeira chave pública e a revisão da entrega serão divulgadas aqui
quando a assinatura oficial estiver disponível.

## Antes de abrir o instalador

1. Abra este canal pelo perfil [jdalpiva](https://github.com/jdalpiva) e confira
   a revisão informada para a entrega.
2. Reúna o instalador do seu sistema, `SHA256SUMS.txt` e
   `SHA256SUMS.txt.minisig` em uma pasta. Obtenha a chave pública neste canal.
3. Use o Minisign para verificar a assinatura da lista com a chave oficial.
   O comentário assinado deve identificar a mesma revisão.
4. Calcule o SHA-256 do instalador e compare o valor com a linha que contém
   seu nome na lista assinada. No Windows, use `Get-FileHash -Algorithm SHA256`
   no PowerShell. No Linux, use `sha256sum`. Extraia o instalador após
   confirmar a assinatura e a correspondência do arquivo.
   [Documentação e downloads do Minisign](https://jedisct1.github.io/minisign/).

Se a verificação falhar, interrompa a instalação e confira a revisão e o
arquivo obtido.
