# AeroLex ✈️

Consultor de legislação aeronáutica com IA — FAA, EASA e ANAC.

## Estrutura

```
aerolex-vercel/
├── index.html          # App principal (frontend)
├── api/
│   └── ask.js          # Proxy para a API da Anthropic (Vercel Function)
├── vercel.json         # Configuração do Vercel
└── README.md
```

## Deploy

1. Suba esta pasta para um repositório no GitHub
2. Conecte o repositório no vercel.com
3. Adicione a variável de ambiente:
   - `ANTHROPIC_API_KEY` = sua chave em console.anthropic.com
4. Clique em Deploy

## Desenvolvimento local

```bash
npm i -g vercel
vercel dev
```
