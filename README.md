
## Como rodar

Clone o repositório e instale as dependências:

```bash
cd todo-app
npm install
cp .env.example .env # ajuste os valores
npm run dev
```

## Docker

Ajuste os valores de `.env.production` e então execute os comandos de `build` e `run`:

```bash
docker build -t todo-app .
docker run -it --rm -p 3000:3000 todo-app
```