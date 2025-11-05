# 🕯️ Loja de Velas — E-commerce Artesanal

Um e-commerce simples e elegante desenvolvido em **Node.js + Express + EJS**, pensado para pequenas lojas artesanais venderem seus produtos de forma direta e prática.

O sistema permite que o **dono da loja** gerencie produtos (crie, edite, exclua) e que o **cliente** adicione produtos ao carrinho e finalize a compra via **WhatsApp**, enviando automaticamente a mensagem com o resumo do pedido.

---

## ✨ Funcionalidades Principais

### 🧑‍💼 Painel do Dono
- Adicionar, editar e excluir produtos  
- Definir preço, descrição e estoque  
- Atualização instantânea no site  

### 🛍️ Área do Cliente
- Visualizar todos os produtos disponíveis  
- Adicionar itens ao carrinho  
- Gerar pedido e enviar via WhatsApp  

### 💬 Checkout via WhatsApp
Ao finalizar a compra, o site monta automaticamente uma mensagem com os itens do carrinho e redireciona o cliente para o WhatsApp do dono da loja.

---

## 🧩 Stack Técnica

| Área | Tecnologia |
|------|-------------|
| Backend | Node.js + Express |
| Frontend | EJS + HTML + CSS |
| Banco de Dados | Arquivo JSON (futuro: SQLite ou MongoDB) |
| Hospedagem | Servidor Linux (Debian/Ubuntu) |
| Ferramentas | VSCode, Git, PM2, Nginx |

---

## 🗺️ Roadmap de Desenvolvimento

### 🏁 Fase 1 — Configuração do Ambiente
- [x] Criar estrutura do projeto  
- [x] Instalar dependências (express, ejs, body-parser, fs-extra)  
- [x] Configurar servidor e rota inicial  

### 💻 Fase 2 — Estrutura Base e Views
- [x] Criar páginas com EJS (`index.ejs`, `admin.ejs`)  
- [x] Adicionar layout base e partials  
- [x] Estilizar com CSS simples  

### 📦 Fase 3 — Banco de Dados JSON
- [x] Implementar leitura e gravação com `fs-extra`  
- [x] Criar CRUD de produtos no painel admin  

### 🛒 Fase 4 — Carrinho e Checkout
- [x] Implementar carrinho com JavaScript no cliente  
- [x] Montar mensagem e redirecionar para WhatsApp  

### 🎨 Fase 5 — Interface e UX
- [ ] Estilização final e design responsivo  
- [ ] Adicionar logo e favicon da loja  

### 🧑‍💼 Fase 6 — Login do Dono (Autenticação)
- [ ] Criar login simples protegido por senha  
- [ ] Armazenar hash em `.env`  

### ☁️ Fase 7 — Deploy no Servidor Linux
- [ ] Instalar Node.js e PM2 no servidor  
- [ ] Fazer deploy e configurar proxy reverso com Nginx  

### 🚀 Fase 8 — Melhorias Futuras
- [ ] Upload de imagens  
- [ ] Edição de produtos (não só exclusão)  
- [ ] Banco real (SQLite ou MongoDB)  
- [ ] Pagamentos com Mercado Pago ou Stripe  
- [ ] Tema escuro / claro  

---

## 💻 Como Rodar Localmente

```bash
# Clone o repositório
git clone https://github.com/seuusuario/loja-velas.git
cd loja-velas

# Instale as dependências
npm install

# Execute o servidor
node server.js
```

Depois acesse:
👉 http://localhost:3000

---

## ☁️ Deploy no Servidor Linux

```bash
# No servidor
sudo apt update
sudo apt install nodejs npm -y

# Clone o projeto
git clone https://github.com/seuusuario/loja-velas.git
cd loja-velas
npm install

# Execute com PM2
npm install -g pm2
pm2 start server.js
pm2 startup
```

(Opcional: configurar Nginx para redirecionar porta 80 → 3000)

---

## 📸 Screenshots (adicione aqui)
| Página | Imagem |
|--------|--------|
| Loja principal | _adicione imagem_ |
| Carrinho | _adicione imagem_ |
| Painel Admin | _adicione imagem_ |

---

## 🧠 Aprendizados e Objetivos
- Praticar desenvolvimento fullstack com Node.js  
- Aprender a estruturar CRUD sem frameworks pesados  
- Gerenciar fluxo completo de um e-commerce simples  
- Preparar terreno para integração com banco e pagamentos  

---

## 🧑‍💻 Autor
**Gustavo Miranda**  
📦 Projeto pessoal para estudo e futura aplicação real.  
💬 Contato: [gustavomiranda@exemplo.com](mailto:gustavomiranda@exemplo.com)

---

## 📜 Licença
Este projeto é distribuído sob a licença **MIT** — sinta-se à vontade para usar e modificar.

---

> _“Comece simples, mas pense grande.”_  
> — Roadmap da Loja de Velas 🌿
