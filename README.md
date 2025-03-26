# Infraestrutura como Código: Script de Criação de Estrutura de Usuários, Diretórios e Permissões

Neste projeto foi criado um script onde toda a infraestrutura de usuários, grupos de usuários, diretórios e permissões são criadas automaticamente. Foi realizado o upload do arquivo de script no GitHub para futuras reutilizações do script. Sendo assim, toda nova máquina virtual que for iniciada já estará pronta para uso quando o script for executado.


## O que é IaC

**Infraestrutura como código (IaC)** é o gerenciamento e provisionamento da infraestrutura por meio de códigos, em vez de processos manuais.

Com a IaC, são criados arquivos de configuração que incluem as especificações da sua infraestrutura, facilitando a edição e a distribuição de configurações. Ela também assegura o provisionamento do mesmo ambiente todas as vezes. 


## Principais Benefícios

Ao automatizar o provisionamento da infraestrutura com a IaC, os desenvolvedores não precisam provisionar e gerenciar manualmente servidores, sistemas operacionais, armazenamento e outros componentes de infraestrutura sempre que criam ou implantam uma aplicação.


![IaC Imagem](https://github.com/Danaraujoc/projeto-linux-iac/blob/main/Infraestrutura%20Iac.png)


## Scopo

- **`Todo provisionamento deve ser feito em um arquivo do tipo Bash Script;`**
- **`O dono de todos os diretórios criados será o usuário root;`**
- **`Todos os usuários terão permissão total dentro do diretório publico;`**
- **`Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;`**
- **`Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem.`**
## Stack utilizada

- **Linux Ubuntu Server** 

- **Virtual Box** 


## Referência

 - [Principais comandos do Linux](https://www.linux.ime.usp.br/~albasalo/Apostila/apostila.pdf)
 - [Mais informações sobre usuários no Linux](https://www.infowester.com/usuarioslinux.php)
 
