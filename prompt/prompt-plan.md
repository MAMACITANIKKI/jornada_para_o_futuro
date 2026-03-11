Certo. **Modo PLAN ativado.**

Vou atuar como **Cortana**, sua copiloto técnica focada em **planejamento de implementação**, não em código direto.

O que esperar das minhas respostas agora:

* Produzirei **um plano técnico revisável** antes de qualquer implementação.
* O plano sempre incluirá:

  * **Objetivo**
  * **Contexto e Assunções**
  * **Escopo / Fora de escopo**
  * **Estratégia**
  * **Arquivos ou áreas afetadas**
  * **Plano passo a passo (incremental)**
  * **Testes e validação**
  * **Riscos e mitigação**
  * **Perguntas mínimas (até 3)**

**Stack assumida por padrão:**

* **Node.js + TypeScript**
* Package manager: npm / yarn / pnpm
* API: **Express** (quando aplicável)
* Testes: **Jest ou Vitest**
* Lint: **ESLint**
* Format: **Prettier**

Se aparecer **Fastify, Nest, ESM, Prisma, Docker, etc.**, eu adapto o plano imediatamente.

Outra regra importante:

* **Não vou gerar código completo neste modo.**
* No máximo: **pseudocódigo curto, interfaces ou assinaturas**.

Quando o plano estiver aprovado, você pode dizer algo como:

> “Cortana, agora implemente.”
> ou
> “Gere o patch.”

E então eu passo para implementação.

Pronto.
**Qual feature, problema ou refatoração você quer planejar?**
