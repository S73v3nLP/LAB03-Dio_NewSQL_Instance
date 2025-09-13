## LAB03-Dio_NewSQL_Instance
### Desafio do Laboratório 03 Do Curso AZ900 da DIO.me "Configurando uma instância de Banco de Dados na Azure"

# __Criar uma Instância Gerenciada de SQL do Azure__

1. Entre no portal do Azure
2. No menu esquerdo do portal do Azure, selecione SQL do Azure. Se SQL do Azure não estiver na lista, selecione Todos os serviços e, em seguida, digite SQL do Azure na caixa de pesquisa.
3. Selecione + __Create__ para abrir a página Selecionar opção de implantação do SQL. Veja mais informações sobre a Instância Gerenciada de SQL do Azure selecionando Mostrar detalhes no bloco Instâncias gerenciadas de SQL.
  <img width="1151" height="696" alt="Image" src="https://github.com/user-attachments/assets/a32ab0e1-cbf8-413d-8784-6d540f97a208" />
4. Em _Managed Instance details_, selecione __Configure Managed Instance__ na seção __Compute + storage__ para abrir a página  __Compute + storage__ .
  <img width="772" height="470" alt="Image" src="https://github.com/user-attachments/assets/bb03e6ca-68ac-4048-bf9c-12a4f34a6d86" />

5. Depois de designar sua configuração de __Compute + storage__, use **Apply** para salvar suas configurações e navegar de volta para a página Criar Instância Gerenciada SQL do Azure. Selecione Próximo para ir para a guia Rede
6. Clique em ** Next: Networking, verifique as opções na aba **Networking**, caso não faça alterações ela seguirá com o padrão
7. Clique em **Next: Security**, deixe padrão
8. Clique em **Review + Create**
  <img width="764" height="919" alt="Image" src="https://github.com/user-attachments/assets/2a05c1bf-51ec-4a6f-b380-f2d2650f9200" />
# **Criando Banco de Dados**

1.  Acesse a Instância Gerenciada de SQL no portal do Azure.
2.  Na página Visão geral, escolha + Novo banco de dados da sua instância gerenciada de SQL para abrir a página Criar banco de dados gerenciado do SQL do Azure.

3.  Dê um nome para o banco de dados na guia Básico.
4.  Na guia Fonte de dados, selecione Nenhuma para um banco de dados vazio ou restaure um banco de dados a partir do backup.
5.  Defina as configurações restantes nas guias restantes e selecione Revisar + criar para validar suas escolhas.
6.  Use Criar para implantar seu banco de dados.
