# Checklist generator
This tool is designed to generate checklists for any programming task. It helps ensure that all necessary steps have been completed as intended.

For example, it can check if tests have been written and if the README file has been updated. It serves as a helpful tool to ensure nothing is overlooked.

## Instalation
Just run docker compose up - it will create containers and expose localhost at 80 to check the app

## Internal stuff
LLaMA is LLM provider in which AI image can be loaded. In this example LLama2 is used. To work proprietary it needs at least 8GB of RAM.
LLaMA act as http server, it listen on port 11434 and responds to POST request.

[LLaMA 2 image](https://huggingface.co/meta-llama)

## Tech stack
* Vue.js [vuejs.org](https://vuejs.org)
* ollama [ollama.com](https://ollama.com)

## Initial work
Greg, Lord of Mailgun Messages, Master of Redis Realms, Messenger of Symfony Secrets, Champion of Domain-Driven Development, Guardian of PHPUnit Proclamations, and Sage of PHP Sorcery
