# Guia de AI Hub

**Estado:** Em avaliação.

Cópia pública com o mesmo percurso de arranque e teste.

[![AI Hub. Guia do AI Hub Publish. Verificação em Docker. Dados e chaves no teu ambiente.](docs/guia-visual.png)](docs/guia-visual.png)

## Onde começar

Consulta o [guia de teste local](https://github.com/mppt24/ai-hub-publish#testar-a-api-localmente).

## Como confirmar

Para verificar esta cópia, executa o seu teste de saúde e abre a execução de Docker em **Actions**.

## Como ler os registos

Os registos do contentor ajudam a separar um erro de arranque de um erro ao ligar ao modelo. A CI desta cópia confirma o primeiro percurso.

### Exemplo fictício

```text
OK · Docker · API local disponível
```

Se a verificação em Docker passar, confirma o arranque e a resposta do serviço. Para investigar uma falha, abre a etapa marcada a vermelho. Para confirmar o chat com um modelo, segue a ligação ao Ollama no guia de teste local. [Ver a execução em Docker deste repositório](https://github.com/mppt24/ai-hub/actions/runs/44919943838)

## Cuidados

Usa a configuração local do guia. Não incluas chaves, ficheiros de configuração privados ou mensagens reais nos exemplos.
