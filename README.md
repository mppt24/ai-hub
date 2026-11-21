# AI Hub

Protótipo de uma API de chat, parte do [MPPT24OS](https://github.com/mppt24/MPPT24OS). O serviço usa FastAPI e encaminha pedidos para Ollama. A integração com OpenAI é opcional e vem desativada na configuração de origem.

- [Código da API](agent-hub/main.py)
- [Configuração Docker Compose](docker-compose.yml)
- [Guia de teste local](https://github.com/mppt24/ai-hub-publish#testar-a-api-localmente)

Por omissão, o Hub publica a porta no endereço local `127.0.0.1:8181`. O guia mostra como arrancar, verificar a resposta, ligar ao Ollama e parar os contentores.
