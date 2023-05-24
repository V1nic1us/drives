# **Drivers-Printers**

Criado para baixar disponibilizar os Drives das Impressoras mais atuais

## 1. Para enviar executaveis acima de 50MB

Utilize o Git Large File Storege

https://git-lfs.com/

## 1.2 Instalação

1.Instalação: Primeiro, você precisa instalar o Git LFS em sua máquina local. Você pode baixar a versão adequada para o seu sistema operacional a partir do site oficial do Git LFS (https://git-lfs.github.com/).

2.Inicializar o Git LFS: Após a instalação, vá para o diretório do seu repositório Git através do terminal ou prompt de comando e execute o seguinte comando para inicializar o Git LFS no seu repositório:

```git lfs install```

3.Especificar arquivos para o Git LFS: Agora, você precisa especificar quais arquivos devem ser gerenciados pelo Git LFS. Normalmente, arquivos grandes, como arquivos binários, imagens ou vídeos, são candidatos adequados para serem gerenciados pelo Git LFS. Para fazer isso, você pode usar o seguinte comando:

```git lfs track "<padrão de arquivo>"```

Substitua <padrão de arquivo> pelo padrão que corresponda aos arquivos que você deseja rastrear com o Git LFS. Por exemplo, para rastrear todos os arquivos .mp4, você pode usar:

```git lfs track "*.mp4"```

O arquivo .gitattributes será atualizado automaticamente com as configurações necessárias.
## 2. Baixe os drives mais atualizados

https://github.com/V1nic1us/drivers-printers/releases
