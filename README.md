# Tropical Lanches 🍔

**Tropical Lanches** é um sistema de gerenciamento de pedidos e cardápio para lanchonetes, desenvolvido com Next.js, Prisma, Tailwind CSS e outras tecnologias modernas. O projeto visa simplificar o atendimento e melhorar a experiência do cliente.

---

## 🚀 Começando

Siga os passos abaixo para configurar e rodar o projeto localmente.

### Pré-requisitos

- Node.js instalado (recomendado usar `nvm` para gerenciar versões).
- Banco de dados configurado (ex: Neon, Supabase, etc.).
- Git instalado.

---

## 🛠 Configuração do Ambiente

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/tropical-lanches.git
   cd tropical-lanches
   ```

2. **Instale as dependências**:
   ```bash
   npm install
   ```

3. **Configure o banco de dados**:
   - Crie um banco de dados no [Neon](https://console.neon.tech/) ou outra plataforma.
   - Copie a URL de conexão e cole no arquivo `.env`:
     ```env
     DATABASE_URL="sua_url_de_conexao"
     ```

4. **Execute as migrações do Prisma**:
   ```bash
   npx prisma migrate dev --name init
   ```

5. **Popule o banco de dados com dados iniciais**:
   ```bash
   npx prisma db seed
   ```

---

## 🖥 Executando o Projeto

1. **Inicie o servidor de desenvolvimento**:
   ```bash
   npm run dev
   ```

2. **Acesse o projeto**:
   Abra o navegador e acesse:
   ```
   http://localhost:3000
   ```

---

## 🛠 Ferramentas e Tecnologias

- **Frontend**: Next.js, Tailwind CSS, shadcn/ui.
- **Backend**: Node.js, Prisma.
- **Banco de Dados**: PostgreSQL (via Neon, Supabase, etc.).
- **Ferramentas**: ESLint, Prettier, Git.

---

## 📂 Estrutura do Projeto

- **`/prisma`**: Contém o schema do banco de dados e scripts de seed.
- **`/src`**: Código-fonte do projeto.
  - **`/app`**: Páginas e rotas do Next.js.
  - **`/components`**: Componentes reutilizáveis.
  - **`/lib`**: Utilitários e funções auxiliares.

---

## 🧩 Como Contribuir

1. Faça um fork do repositório.
2. Crie uma branch para sua feature:
   ```bash
   git checkout -b feature/nova-feature
   ```
3. Commit suas mudanças:
   ```bash
   git commit -m "Adiciona nova feature"
   ```
4. Push para a branch:
   ```bash
   git push origin feature/nova-feature
   ```
5. Abra um Pull Request.

---

## 📝 Licença

Este projeto está licenciado sob a **MIT License**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🙏 Agradecimentos

- [Next.js](https://nextjs.org/)
- [Prisma](https://prisma.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/)

---

Feito com ❤️ por Pedro Sipriano.  
📧 **Contato**: SIPRIANOWEB@GMAIL.COM 
