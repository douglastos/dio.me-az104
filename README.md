<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD045 -->
<!-- markdownlint-disable MD041 -->

<img src="https://certadda.com/wp-content/uploads/2020/11/azure-104.png" width="200"/><img src="https://hermes.digitalinnovation.one/assets/diome/logo.svg" width="500"/>

# 🚀 Bootcamp AZ-104 - DIO

Bem-vindo(a) ao meu repositório de estudos do Bootcamp AZ-104 oferecido pela Digital Innovation One (DIO)!\

Este bootcamp é focado na preparação para a certificação Microsoft Azure Administrator (AZ-104), abordando conceitos fundamentais e práticos sobre administração de ambientes no Azure, incluindo gestão de identidades, redes virtuais, recursos computacionais, armazenamento, monitoramento e segurança.\

Aqui você encontrará:\

    📚 Exercícios práticos realizados durante o bootcamp

    ✅ Resumos e anotações dos conteúdos estudados

    💡 Exemplos e scripts para auxiliar na prática diária

O objetivo deste repositório é consolidar meu aprendizado, compartilhar conhecimento e também servir como guia para quem está se preparando para a certificação AZ-104.

Confira abaixo os links para os exercícios e materiais do bootcamp!


## criando maquina virtual pelo browser

segue o exercicio de criar uma maquina virtual pelo browser:

![Criar Máquina Virtual pelo Browser](img/vm-browser-1.gif)

## criando maquina via CLI

exemplo do comando para criar uma maquina virtual via CLI:

```bash
az vm create \
  --resource-group AZ104-TESTE \
  --name az104-teste-vm \
  --image Debian:debian-12:12-gen2:latest \
  --admin-username douglastos \
  --authentication-type password \
  --admin-password "MinhaSenhaSuperForte@2025" \
  --size Standard_DS1_v2 \
  --public-ip-sku Basic \
  --tags teste-az104=douglas
```

segue o coamando para criar uma maquina virtual via CLI:

![Criar Máquina CLI](img/vm-cli.gif)

a maquina criada via CLI

![Maquina Criada CLI](img/vm-cli-1.png)
