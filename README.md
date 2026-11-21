# AI Hub

[Guia de leitura, infográfico e cuidados](GUIA.md)

Protótipo de uma API de chat, parte do [MPPT24OS](https://github.com/mppt24/MPPT24OS). O serviço usa FastAPI e encaminha pedidos para Ollama. A integração com OpenAI é opcional e vem desativada na configuração de origem.

- **Experimentar em Docker.** Vê como confirmar que o serviço responde, ligar ao Ollama e parar os contentores. [Testar a API localmente](https://github.com/mppt24/ai-hub-publish#testar-a-api-localmente)
- **Ler o código.** Consulta a [implementação da API](agent-hub/main.py) e a [configuração Docker Compose](docker-compose.yml).

Por omissão, o Hub publica a porta no endereço local `127.0.0.1:8181`.
