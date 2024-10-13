# Discord-Voice-Bot
# ДАННЫЙ БОТ БЫЛ НАПИСАН С ПОМОЩЬЮ CHAT GPT, ДАННЫЙ БОТ НЕ БУДЕТ ДОРАБАТЫВАТЬСЯ, ИЗМЕНЯТСЯ И Т.П. 

# Установка для Ubuntu (VDS/VPS Server)

### Шаг 1: Установка необходимых компонентов

sudo apt update && sudo apt upgrade -y

### Установите Node.js: Убедитесь, что у вас установлена последняя версия Node.js. Рекомендуется установить его через Node Version Manager (NVM):
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash

### После установки выполните следующую команду, чтобы загрузить nvm:
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

### Затем установите Node.js:
nvm install node

### Установите npm (он должен установиться вместе с Node.js):
npm install -g npm

# Шаг 2: Настройка проекта

### Создайте каталог для вашего бота:
mkdir DiscordBot
cd DiscordBot

### Войдите в данный каталог и загрузите файлы:
bot.js и config.json
Откройте файл config.json и настройте его.

### Инициализируйте новый проект Node.js:
npm init -y

### Установите необходимые пакеты: Установите discord.js и другие зависимости:
npm install discord.js @discordjs/rest discord-api-types

### Запустите бота:
node bot.js
Убедитесь, что бот успешно подключается и работает. Вы должны увидеть сообщение в терминале о том, что бот вошел в систему.
