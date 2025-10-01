# 🛒 Marketplace Corpo & Tech Backend

## 🚀 Status do Projeto
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Laravel Version](https://img.shields.io/badge/Laravel-10%2B-FF2D20?logo=laravel)](https://laravel.com/)
[![PHP Version](https://img.shields.io/badge/PHP-8.1%2B-777BB4?logo=php)](https://www.php.net/)
[![API RESTful](https://img.shields.io/badge/API-RESTful-007ACC?logo=json)](https://pt.wikipedia.org/wiki/REST)

---

## 📝 Descrição do Projeto

Este é o **backend** da plataforma **Marketplace Corpo & Tech**, um e-commerce especializado na venda de produtos para **bem-estar, suplementação e tecnologia vestível**.

Desenvolvido com o *framework* **Laravel**, o projeto foi estruturado como uma **API RESTful** robusta, focando na **performance** e **segurança** para gerenciar todas as operações de negócio.

### Objetivos da API:
* **Catálogo de Produtos:** Gerenciamento completo de produtos, categorias e imagens (CRUD).
* **Fluxo de Vendas:** Autenticação, gestão de carrinhos de compra e processamento de pedidos.
* **Administração:** Controle de usuários (Clientes e Administradores) e visualização de dados.

---

### 2. Melhoria na Seção de Funcionalidades

Use ícones Markdown (como `:check:` ou emojis) para tornar a lista mais dinâmica e detalhe a arquitetura.

## ✨ Funcionalidades e Arquitetura

| Funcionalidade | Descrição |
| :--- | :--- |
| **🔒 Autenticação JWT** | Login/Registro seguro para clientes e endpoints protegidos para o Painel Administrativo, utilizando [Sua Biblioteca JWT aqui]. |
| **🛍️ Gestão de Produtos** | CRUD completo de produtos, incluindo **upload de imagens** via *Storage Disk* e organização por **categorias aninhadas** (hierárquicas). |
| **🛒 Sistema de Carrinho** | Adicionar/Remover itens de forma persistente, cálculo dinâmico de subtotais e validação de estoque. |
| **📦 Gerenciamento de Pedidos** | API para criação de pedidos e endpoints protegidos para Administradores alterarem o status (ex: `pendente` $\rightarrow$ `enviado` $\rightarrow$ `entregue`). |
| **💵 Integração Mock (Pagamento)** | Serviço simulado para processamento de transações, pronto para integrar com gateways reais (Stripe/PagSeguro/Mercado Pago). |
| **🛡️ Dashboard Administrativo** | Rotas e *middlewares* protegidos para gerenciar o catálogo, usuários e pedidos. |

---

### 3. Melhoria na Seção Técnica e Diagrama (Opcional)

Se você puder criar um **diagrama de arquitetura** simples (pode ser feito com ferramentas como Excalidraw ou Mermaid), adicione a imagem e a seção a seguir.

## 🛠️ Stack Tecnológico

| Categoria | Tecnologia | Versão | Notas |
| :--- | :--- | :--- | :--- |
| **Back-end** | **PHP** | 8.1+ | Linguagem principal. |
| **Framework** | **Laravel** | 10.x / 11.x | Estrutura MVC robusta. |
| **Banco de Dados** | **PostgreSQL** | N/A | Escolhido pela performance e recursos avançados. |
| **Autenticação** | **JWT** | (Biblioteca) | Utilizado para *stateless* authentication. |
| **Gerenciador** | **Composer** | 2.8.8 | Gerenciamento de dependências. |

### 📊 Diagrama de Arquitetura (Opcional)

Se houver um frontend (como Vue/React), esta imagem ilustra a comunicação entre as partes.

```markdown
