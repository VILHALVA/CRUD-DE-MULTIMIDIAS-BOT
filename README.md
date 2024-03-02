# CRUD DE MULTIMIDIAS BOT
🤤ESSE É UM BOT DO TELEGRAM DE CRUD DE MULTIMIDIAS EM MYSQL!

<img src="./IMAGENS/FOTO_1.png" align="center" width="400"> <br>
<img src="./IMAGENS/FOTO_2.png" align="center" width="400"> <br>
<img src="./IMAGENS/FOTO_3.png" align="center" width="400"> <br>
<img src="./IMAGENS/FOTO_4.png" align="center" width="400"> <br>

## DESCRIÇÃO:
Este bot é um aplicativo de mensagens instantâneas que opera na plataforma Telegram e foi desenvolvido para gerenciar um banco de dados de multimídias. Ele oferece funcionalidades básicas de um CRUD (Create, Read, Update, Delete) para manipular arquivos de mídia, como imagens, vídeos ou áudios.

1. **Enviar Mídia:** Os usuários podem enviar arquivos de mídia para serem armazenados no banco de dados do bot. Isso é feito iniciando uma conversa com o bot e selecionando a opção "ENVIAR" no menu principal.

2. **Exibir Mídias:** Os usuários podem visualizar todas as mídias armazenadas no banco de dados do bot. Ao selecionar a opção "EXIBIR" no menu principal, o bot exibirá uma lista de todas as mídias disponíveis.

3. **Editar Mídia:** Os usuários podem renomear os arquivos de mídia armazenados no banco de dados. Ao selecionar a opção "EDITAR" no menu principal, o bot permite que os usuários escolham a mídia que desejam editar e forneçam um novo nome para ela.

4. **Apagar Mídia:** Os usuários podem excluir arquivos de mídia do banco de dados. Ao selecionar a opção "APAGAR" no menu principal, o bot exibe uma lista de todas as mídias disponíveis e permite que os usuários escolham qual deseja excluir.

O bot é capaz de interagir com os usuários por meio de mensagens de texto e botões interativos, facilitando a comunicação e a execução das operações CRUD de maneira intuitiva e eficiente. Ele ajuda os usuários a gerenciar suas coleções de mídia de forma conveniente e organizada diretamente do aplicativo Telegram.

## COMO USAR?
### BAIXANDO O PROJETO:
**Passo 1:** Clone o repositório para o seu sistema local.

```bash
git clone https://github.com/VILHALVA/CRUD-DE-MULTIMIDIAS-BOT.git
```

**Passo 2:** Navegue até o diretório do projeto.

```bash
cd CRUD-DE-MULTIMIDIAS-BOT
```

**Passo 3:** Descompacte o arquivo ZIP (se você baixou manualmente):

```bash
unzip CRUD-DE-MULTIMIDIAS-BOT.zip
```

### EXECUTANDO O PROJETO:
1. **Configuração do Banco de Dados:**

   - Você deve importar o arquivo `DATABASE.sql` para o seu BANCO DE DADOS.

   - Se você não estiver familiarizado com esses passos, confira nosso [curso completo de MYSQL](https://github.com/VILHALVA/CURSO-DE-MYSQL) para obter orientações detalhadas.

2. **Editar o código:**
   - Certifique-se de substituir "localhost", "seu_usuario" e "sua_senha" no arquivo `DB_CONNECTION.py` pelas informações corretas do seu banco de dados MySQL.

3. **Coloque o Token:**
   - Antes de executar o programa, é necessário substituir o token do seu bot no arquivo `TOKEN.py`, o qual pode ser obtido por meio do [@BotFather](https://t.me/BotFather). Certifique-se também de que todas as dependências estejam instaladas em sua máquina. Se você não estiver familiarizado com esses passos, confira nosso [curso completo sobre a criação de bots no Telegram](https://github.com/VILHALVA/CURSO-DE-TELEGRAM-BOT) para obter orientações detalhadas.

4. **Inicie o Bot:**
   - Execute o bot do Telegram em Python iniciando-o com o seguinte comando:
```bash
   python MAIN.py
```
   - Inicie o bot enviando o comando `/start`. Receba uma mensagem de boas-vindas e clique nos botões inlines.

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)

