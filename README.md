> # Atualizar_Linux.debian
> #!/bin/bash

> #Script para atualizar o Kali Linux

> echo "Iniciando o processo de atualização do Kali Linux..."

> #Atualizar a lista de pacotes
> echo "Atualizando a lista de pacotes..."
> sudo apt-get update -y

> #Atualizar todos os pacotes instalados
> echo "Atualizando pacotes instalados..."
> sudo apt-get upgrade -y

> #Realizar atualização de distribuição (Caso Necessário)
> echo "Atualizando pacotes instalados..."
> sudo apt-get dist-upgrade -y

> #Limpar pacotes denecessários
> echo "Removendo pacotes desnecessários..."
> sudo apt-get autoremove -y

> #limpar arquivos de cache (Opcional)
> echo "Removendo arquivos de cache..."
> sudo apt-get clean

> echo "Atualização concluída com sucesso!"
