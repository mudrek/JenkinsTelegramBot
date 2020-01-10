# JenkinsTelegramBot
------------------------------

# Assunto
Implementação de bot do Telegram com Jenkins.

------------------------------
# Criação do bot do Telegram
- Procurar pelo BotFather no Telegram.
- Digitar /newbot e seguir os passos para a criação do bot.
- Copiar o token de acesso.

------------------------------
# Ajustes do bot
- Adicionar o bot em um grupo/chat
- Acessar https://api.telegram.org/bot<token_>/getUpdates
- Digitar um comando no grupo/chat
- Acessar novamente https://api.telegram.org/bot<token_>/getUpdates, pegar o id do grupo/chat

------------------------------
# Testar bot
- https://api.telegram.org/bot<Bot_token>/sendMessage?text=<Mensagem_>&chat_id=<ChatId_>

------------------------------
# Configuração Jenkins

------------------------------
#JenkinsFile

