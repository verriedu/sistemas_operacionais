# **Setup inicial**
**Observação 1**: Quando tiver `C:>\` o comando deve ser executado no terminal Windows.
Quando tiver `$` o comando deve ser executado no terminal Linux.

**Observação 2**: Abra este arquivo no VSCode e pressione `CTRL + Shift + V` para abrir o visualizador de arquivo Markdown e vê-lo formatado.

## INSTALANDO AWS CLI **WINDOWS** 

### Abra um PowerShell ou um CMD no modo de administrador e execute os seguintes comandos para instalar e testar se a instalação ocorreu com sucesso:
```
C:\> msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi`

C:\> aws --version
```

## INSTALANDO AWS CLI _Linux_
### Abra um terminal bash e execute os seguintes comandos para instalar e testar se a instalação ocorreu com sucesso:
```
$ curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"

$ unzip awscliv2.zip

$ sudo ./aws/install

$ aws --version
```
