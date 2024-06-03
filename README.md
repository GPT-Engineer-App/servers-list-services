# servers-list-services

есть файл c:\temp\servers_list.txt со списком серверов. нужно для каждого сервера выполнить команду

get-service *theseus* | where {$_.status -eq 'running'} 

и полученный результат записать в файл 'c:\temp\Список запущенных служб Theseus.txt'. важная деталь - полученный файл должен быть один в котором первый столбец называется ComputerName, т.е. содержать имя компьютера

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/servers-list-services.git
cd servers-list-services
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
