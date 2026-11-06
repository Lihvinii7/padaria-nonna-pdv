# 🥖 Padaria da Nonna — PDV & Frente de Caixa

Sistema web de Ponto de Venda (PDV) e frente de caixa desenvolvido sob medida para a **Padaria da Nonna**. A aplicação conta com interface responsiva e rápida, suporte a leitores de código de barras, cálculo ágil de produtos de balança/peso variável, gestão de troco e persistência na nuvem via **Supabase**.

---

## 🚀 Funcionalidades

- **⚡ Frente de Caixa Rápida:** Lançamento de itens por leitor de código de barras ou busca instantânea por nome/iniciais.
- **⚖️ Balcão de Pesagem:** Integração prática para produtos vendidos por peso ou etiqueta de balança (Pão Francês, queijos fatiados, frios, doces).
- **💵 Múltiplas Formas de Pagamento:** Suporte para Dinheiro, PIX, Cartão de Débito e Cartão de Crédito com cálculo automático e botões de troco rápido.
- **☁️ Banco de Dados em Nuvem:** Conexão direta com **Supabase** para persistência e consulta em tempo real de produtos, preços e histórico de transações.
- **📱 Responsivo & Multiplataforma:** Acessível via desktop, notebooks, tablets e smartphones (com instalação PWA/atalho de tela inicial).
- **🖨️ Fechamento e Impressão:** Estrutura pronta para fechamento de venda e emissão de comprovantes térmicos (Elgin i9).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3**
- **Tailwind CSS** (Interface moderna e estilização utilitária)
- **JavaScript (ES6+)** (Lógica de carrinho, troco, atalhos e regras de negócio)
- **Supabase** (PostgreSQL em nuvem e autenticação via API REST)
- **Font Awesome** (Ícones da interface)

---

## 📦 Estrutura de Arquivos

```text
padaria-nonna-pdv/
├── index.html        # Estrutura visual e regras de negócio do PDV
├── banner.png        # Banner panorâmico superior do estabelecimento
├── logo.png          # Logotipo oficial Padaria da Nonna
└── README.md         # Documentação do projeto
