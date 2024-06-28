# Terraform AWS EKS Cluster

Este repositório contém código Terraform para provisionar um cluster EKS (Elastic Kubernetes Service) na AWS. A configuração inclui a criação de uma VPC, subnets públicas e privadas, um gateway de internet, um NAT Gateway e o cluster EKS com grupos de nós gerenciados.

## Estrutura do Projeto

- `main.tf`: Arquivo principal que define os recursos da AWS e o módulo EKS.
- `variables.tf`: Define as variáveis utilizadas no projeto.
- `outputs.tf`: Define as saídas do Terraform para obter informações sobre os recursos provisionados.
- `providers.tf`: Define os provedores necessários para o Terraform.
- `data.tf`: Contém os dados necessários, como as zonas de disponibilidade.

## Pré-requisitos

- Terraform instalado: [Instruções de instalação](https://learn.hashicorp.com/tutorials/terraform/install-cli)
- AWS CLI instalado e configurado com o perfil `decro`: [Instruções de instalação](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)
- Credenciais AWS configuradas no perfil `decro`

## Como Usar

### 1. Clone o Repositório

```sh
git clone <URL_DO_SEU_REPOSITORIO_GITHUB>
cd <NOME_DO_REPOSITORIO>

