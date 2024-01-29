# **Atividade-Linux-AWS**
Primeira atividade desenvolvida no programa de bolsas da Compass UOL (DevOps), atividade é proposta em aplicar nosso conhecimento de **Linux** e **AWS**

___
# **Objetivo Geral**
Vamos subir uma máquina **Linux** com o **Apache** rodando, por último criar um **Script** que vai verificar seu meu **Apache** vai estar **online** e **rodando**. utilizaremos o seguinte serviço da AWS:   **Instâncias EC2**


___
# Prática
## **Prática AWS**
- Gerar um **"Par de chaves"** para acessar a instância **EC2**
  - Dentro do painel do serviço **EC2**, clique na opção **Pares de Chaves**
    ![Par de Chaves](https://github.com/kaueribeirocosta/Atividade-Linux-AWS/assets/157628195/777a35e2-177e-4c25-af3c-b5fb46a913cc)

  - Clique em **Criar par de chaves**
   
  - Insira o **Nome**, e mude o **Formato de arquivo para ".pem"**. Depois é só clicar em criar
 
  - 


- Gerar um **"Grupo de segurança"** para liberar as **portas de comunicação**
- Criar uma **"Instância EC2"** para podermos subir nosso **Apache**
- Gerar um **"Elastic IP"** e anexar a nossa **instância EC2** já criada!

## **Prática Linux**
- Configurar o **"NFS"** do seu **Linux**
- Criar um diretório dentro do **"filesystem"** do **NFS** com seu nome
- Subir um **"Apache"** no seu servidor - deve estar **online** e **rodando**
- Criar um **"Script"** que valide se o **Apache** está **online**
  - Ele deve retornar o resultado para seu diretório no **NFS**
  - O **Script** deve contem o formato em ( **Data** **Hora** + **nome do serviço** + **Status** + mensagem de **OFFLINE** ou **ONLINE**)
  - O **Script** deve gerar **dois arquivos** de **saída**: Um para o **serviço** **ONLINE**, o outro para ele **OFFLINE**
  - **Automatizar** a execução dele para de 5 em 5 minutos
