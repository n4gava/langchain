# Estrutura do Projeto

Este repositório contém dois projetos separados:

- **frontend/**: Aplicação React criada com Vite e TailwindCSS.
- **backend/**: API criada com NestJS.

---

## Como rodar o frontend

```bash
cd frontend
npm install
npm run dev
```

O frontend estará disponível em `http://localhost:5173` por padrão.

### Estrutura de pastas do frontend

- `src/components/`: Componentes React reutilizáveis
- `src/pages/`: Páginas principais da aplicação
- `src/hooks/`: Custom hooks do React
- `src/assets/`: Imagens e arquivos estáticos

---

## Como rodar o backend

```bash
cd backend
npm install
npm run start:dev
```

O backend estará disponível em `http://localhost:3000` por padrão.

### Estrutura de pastas do backend

- `src/controllers/`: Controllers (rotas e requisições HTTP)
- `src/services/`: Services (lógica de negócio)
- `src/modules/`: Modules (organização de funcionalidades)

---

> Cada projeto possui seu próprio `package.json` e dependências.
> Não misture frontend e backend no mesmo projeto.

---

**Observação:**

- Não há autenticação ou lógica de API avançada neste template.
- Não há configuração Docker neste template.
- Siga os comentários nas pastas para entender a função de cada uma.
