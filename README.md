# Chamados-ADS

## Programação para Web

### Aluno:
Antonio Matheus Rodrigues e Silva

### Objetivo do projeto.
O projeto consiste no desenvolvimento de uma API web em Python utilizando Flask para um sistema de chamados, onde os usuários irão abrir chamados de suporte técnico.

### Como instalar as dependências com uv sync --locked.
Para instalar o UV
```bash
            pip install uv
```

Após a instalaçao do UV ser concluída, você pode realizar as instação através do comando:
```bash
            uv add [biblioteca-desejada]
```


### Como executar a aplicação.

Para executar a aplicação, é muito simples:
```bash
            flask run
```

ou através do UV, que fica:
```bash
        uv run flasck run
```

e para exectar no codespace, utilize o comando:
```bash
    uv run flask --app app run --host=0.0.0.0 --port=5000
```
### Como acessar a rota inicial e qual resposta esperar.

A rota inicial é acessada através da página raís, ou seja 

```html
    /
```