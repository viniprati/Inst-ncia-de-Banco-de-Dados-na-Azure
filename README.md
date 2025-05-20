# Desafio: Configuração de Instância de Banco de Dados no Microsoft Azure

## Sobre o Projeto
Este repositório documenta o processo de criação e configuração de uma instância gerenciada do SQL Server no Microsoft Azure. O objetivo é reunir informações importantes, dicas e passos claros para facilitar o entendimento e o uso da plataforma em projetos futuros.

## Passo a Passo Detalhado

### 1. Acesso ao Portal do Azure
- Acesse o [Portal do Azure](https://portal.azure.com).
- Faça login com sua conta Microsoft vinculada ao Azure.

### 2. Criar uma Instância Gerenciada SQL
- Clique em “Criar um recurso”.
- Pesquise por “Instância Gerenciada SQL” e selecione.
- Clique em “Criar”.
- Preencha os dados básicos:
  - **Nome da instância**: escolha um nome único.
  - **Assinatura**: selecione sua assinatura do Azure.
  - **Grupo de recursos**: crie um novo ou selecione um existente.
  - **Região**: escolha a região mais próxima para melhor desempenho.
- Configure as opções de administração, como login do administrador e senha.
- Ajuste a configuração de computação e armazenamento conforme necessidade e orçamento.

### 3. Configuração de Rede e Segurança
- Configure a rede virtual (VNet) e sub-rede onde a instância ficará.
- Defina as regras de firewall para liberar os IPs que poderão acessar a instância.
- É possível usar também regras de acesso para serviços específicos do Azure.

### 4. Finalizar Criação e Testar
- Revise todas as configurações e clique em “Criar”.
- Aguarde a implantação da instância, que pode levar alguns minutos.
- Após criada, conecte-se à instância usando ferramentas como Azure Data Studio ou SQL Server Management Studio (SSMS).
- Crie bancos de dados, tabelas e execute comandos para validar o funcionamento.

## Dicas Importantes
- Sempre monitore o uso e custo da instância pelo portal do Azure.
- Escolher a região correta ajuda a reduzir latência e melhorar a performance.
- Configure backup automático para garantir segurança dos dados.
- Documente as credenciais e configurações para facilitar manutenção futura.

## Recursos Utilizados
- [Documentação oficial Microsoft Azure SQL Managed Instance](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/)
- Vídeo-aulas da DIO sobre Azure e bancos de dados
- GitHub para versionamento e compartilhamento da documentação

## Estrutura do Repositório
- `README.md` — documentação principal
- `/images/` — pasta para capturas de tela (opcional)
