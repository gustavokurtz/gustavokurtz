<img src="./assets/terminal.svg" alt="$ whoami: Gustavo Nascimento, AI Engineer at NTConsult" width="480">

### Now

AI Engineer at [NTConsult](https://www.ntconsult.com.br/). I'm building an agent-based assistant that walks field teams through operational procedures: LangChain and MCP for tools, RAG over company knowledge, and LLM-as-a-judge checking every answer before it reaches the user. Evals and tracing on every turn, so model behavior is something we can test.

### Featured: [Dubla](https://github.com/gustavokurtz/dubla)

Dubs English jiu-jitsu instructionals into Brazilian Portuguese. Paste a YouTube link, get the same video back with a Portuguese voice on the original speaker's timing, over the original background sound, using mat vocabulary ("raspar", "passar a guarda") instead of a literal translation.

- **Per-line pipeline:** Demucs splits voice from background, AssemblyAI transcribes with speaker labels, Claude Sonnet fixes the English and translates, a Claude Haiku judge reviews every line and sends rejects back, AssemblyAI TTS voices each line and it gets fitted into its original time slot
- **Cost observability:** every paid call is priced and recorded in a per-job trace across the seven pipeline stages, so each dub shows exactly what it cost (an 11-minute video: ~US$0.57)
- **Jobs, not requests:** dubbing runs in a queue with live progress over SSE, and jobs, stages and paid calls are persisted to Postgres, so history survives restarts and interrupted jobs are flagged instead of lost

`Claude Sonnet` `Claude Haiku` `AssemblyAI` `Demucs` `NestJS` `Prisma` `PostgreSQL` `React`

### Selected work

| Project | What it does | Built with |
| --- | --- | --- |
| [**Visagismo**](https://github.com/gustavokurtz/kairobarberbackend/tree/main/src/modules/ai-visagism) | Shows a haircut on your own face before the scissors. A multimodal model describes the face, an image model renders only the new hair | Llama 4 Scout · image generation |
| [**my-skills**](https://github.com/gustavokurtz/my-skills) | Claude Code skills I use every day, including a Ctrl+G prompt refiner | Claude Code · Shell |
| [**buscacnpj**](https://github.com/gustavokurtz/buscacnpj) | Brazilian company lookup by CNPJ, with rate limiting and a web front end | NestJS · TypeScript |
| [**omarchy #1689**](https://github.com/basecamp/omarchy/pull/1689) | Merged fix for an ANSI escape bug in Basecamp's Omarchy, reviewed by DHH | Open source · Shell |

### Stack

`TypeScript` `Node.js` `LangChain` `AI SDK` `MCP` `RAG` `NestJS` `Fastify` `React` `Next.js` `PostgreSQL` `MongoDB` `Redis` `Python` `Docker`

### Elsewhere

[gustavodev.tech](https://www.gustavodev.tech/) · [LinkedIn](https://www.linkedin.com/in/gustavonascimentoo) · [YouTube](https://www.youtube.com/@gustavookurtz) · gustavoocontact@gmail.com
