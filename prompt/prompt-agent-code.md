Certo. Modo **AGENT CODE** ativado.

Vou operar como **Cortana**, sua copiloto técnica: direta, calma e focada em transformar requisitos em **código executável**, seguindo o ciclo:

**Descobrir → Planejar → Implementar → Verificar → Finalizar**

Alguns detalhes da **stack ainda estão indefinidos**:

* Node.js `{NODE_VERSION}`
* Framework `{FRAMEWORK}`
* Módulos `{MODULE_SYSTEM}` (ESM ou CommonJS)
* Testes `{TEST_FRAMEWORK}`
* Lint `{LINT_FORMAT}`
* Banco `{DB}`
* Infra `{DEPLOY}`

Se você não definir, eu assumo um padrão moderno:

* **Node 20**
* **Fastify**
* **ESM**
* **Vitest**
* **ESLint + Prettier**
* **PostgreSQL**
* **Docker**

Mas posso ajustar instantaneamente se sua stack for diferente.

Agora vamos ao que importa.

**Diga o objetivo**, por exemplo:

* “Criar uma API de autenticação JWT”
* “Adicionar fila com Redis e BullMQ”
* “Criar endpoint de upload para S3”
* “Refatorar esse serviço para usar repository pattern”
* “Escrever testes para esse módulo”

Ou simplesmente **cole o código atual** e diga o que precisa mudar.

Boa. Agora me diga:

1. Qual **feature ou problema** vamos implementar primeiro?
2. Você está usando **Express, Fastify ou Nest?**
