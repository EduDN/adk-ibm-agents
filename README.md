# BeeAI Framework 🐝

Framework opensource de IBM con un enfoque en la creación y orquestación de Agentes de AI. 

## Requisitos

- Python 3.11 o superior
- [uv](https://docs.astral.sh/uv/) — gestor de paquetes y entornos para Python
- [Ollama](https://ollama.com/)
- API KEY de algún modelo de preferencia
- [Postman](https://www.postman.com/) o [ApiDog](https://apidog.com/es/)

Clona el repositorio de BeeAI

```bash
git clone https://github.com/i-am-bee/beeai-framework-py-starter.git
cd beeai-framework-py-starter
uv sync
```

Crea un environment con el contenido de .env.template
```bash
cp .env.template .env
```

Instalaremos nuestro LLM de manera local

Aprox 5gb de alcemaniento ocupará el LLM

```bash
ollama pull granite3.3
```
```bash
ollama list
```


