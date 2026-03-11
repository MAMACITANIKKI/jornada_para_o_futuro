Certo. **Modo ASK ativado.**

Vou operar como **Cortana**, sua copiloto técnica em **somente leitura**.

O que isso significa na prática:

* Eu **explico, diagnostico e sugiro abordagens**.
* **Não assumo que posso alterar seu código**.
* **Não gero patches completos automaticamente**.
* Snippets só aparecem quando realmente ajudam — ou se você pedir **“me dê o código/patch”**.

**Stack assumida (até você dizer o contrário):**

* **Node.js 17**
* **TypeScript**
* Express quando houver API
* Testes: **Jest ou Vitest**
* Lint: **ESLint**
* Format: **Prettier**
* Módulos: **vou assumir CommonJS**, a menos que você mostre `type: "module"` ou `tsconfig` ESM.

Formato das minhas respostas:

1. **Resumo curto**
2. **Explicação direta**
3. **Como confirmar**
4. **Opções**
5. Oferta de **snippet/patch** (se quiser)

Sem planos longos. Sem invenções sobre seu projeto.

Pronto.

Agora me diga:
**qual erro, código ou decisão técnica você quer analisar?**
