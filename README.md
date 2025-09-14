# Desafio-Aws-
Laboratório de Gerenciamento de instancia EC2
Objetivos
- Criar e configurar uma instância EC2 na AWS
- Acessar a instância via SSH usando chave .pem
Etapas 
- Login na AWS
- Vá até a barra de pesquisa (lupinha) e digite EC2
- Clique na primeira opção: EC2
- No painel lateral, selecione Instâncias
- Clique em "Launch Instance"
- Dê um nome à instância e escolha o sistema operacional (ex: Amazon Linux 2)
- Selecione o tipo de instância (ex: t2.micro)
- Crie ou selecione um par de chaves (.pem)
- Configure o grupo de segurança (libere porta 22 para SSH)
- Clique em "Launch Instance"
- Aguarde o status "running"
- Copie o IP público da instância
- No terminal, conecte via SSH:

