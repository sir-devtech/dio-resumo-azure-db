# dio-resumo-azure-db

# Resumo: Configurando Banco de Dados na Azure

Este repositório contém o resumo do laboratório prático do curso de Tipos de Serviço de Nuvem da DIO.

## 🎯 Objetivo
Documentar o processo de provisionamento de uma instância de Banco de Dados SQL gerenciada na plataforma Microsoft Azure (modelo PaaS).

## 🚀 Passo a Passo da Configuração

Durante a prática, os seguintes passos foram observados e executados no portal da Azure:

1. **Criação do Grupo de Recursos:**
   - Foi necessário definir um *Resource Group* para organizar e agrupar os serviços utilizados no laboratório.

2. **Configuração do Banco de Dados:**
   - Criação de um recurso do tipo "Banco de dados SQL".
   - Definição do nome do banco e configuração de um novo **Servidor Lógico** (inserindo login e senha de administrador).

3. **Ajuste de Custos e Carga de Trabalho:**
   - Seleção do ambiente de **Desenvolvimento** (ao invés de Produção) e ajuste das configurações de computação/armazenamento para a camada Básica, visando otimização de custos e uso dos créditos gratuitos.

4. **Regras de Rede (Firewall):**
   - Na aba de rede, foi configurada a liberação do IP público para permitir que ferramentas externas consigam se conectar ao banco de dados recém-criado.

## 💡 Conclusão
O modelo de Plataforma como Serviço (PaaS) da Azure facilita imensamente a subida de um banco de dados relacional, abstraindo a necessidade de configurar máquinas virtuais e sistemas operacionais, permitindo focar diretamente na gestão dos dados.
