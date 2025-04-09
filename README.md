# MarketPilot
Aplicativo para listas inteligentes de mercado.
# 🛒 Protótipo de Aplicativo de Compras Compartilhadas

Este repositório contém um protótipo desenvolvido em **HTML, CSS e JavaScript** para estruturar a base de um aplicativo web focado em **listas de compras colaborativas**.

> ⚠️ Este projeto ainda está em fase inicial de prototipação e não utiliza banco de dados nem backend integrado. A estrutura atual visa simular a navegação e lógica principal da aplicação.

---

## 📌 Objetivo do Aplicativo

Criar uma plataforma web onde diferentes usuários da casa possam:

1. Criar e editar listas de compras.
2. Compartilhar e colaborar em tempo real.
3. Registrar preços durante as compras.
4. Obter relatórios simples ao final da compra.

---

## 👥 Fluxo de Uso

### 1. Identificação do Usuário
Ao acessar o app, o usuário escolhe seu nome: **Leo**, **Kdu/Caio** ou **Yumi**.

### 2. Escolha da Ação
- 🔹 **Ver Listas Salvas**
- 🔹 **Criar Nova Lista**

### 3. Criação de Lista
O usuário pode adicionar itens categorizados por:

- Carnes, Aves e Peixes  
- Hortifrúti  
- Laticínios e Ovos  
- Mercearia, Enlatados e Grãos  
- Produtos de Limpeza e Higiene

Cada item inserido é associado ao nome do usuário. Outros membros podem visualizar e interagir com esses itens, aceitando-os caso também queiram comprá-los.

### 4. Salvamento da Lista
Após finalização, a lista é salva no servidor da casa e fica disponível para acesso por outros dispositivos.

---

## 🛍️ MOMENTO MERCADO

- O usuário acessa a **lista salva** e, ao encontrar os produtos no mercado, insere os **valores reais** pagos por item.
- Ao finalizar a compra, o app gera um **relatório final** com:

  - 💰 Valor total da compra  
  - ⏱️ Tempo total da compra  
  - 📈 Produto mais caro  
  - 📉 Produto mais barato  

O relatório é então salvo no servidor local.

---

## 🗂️ Estrutura de Arquivos

| Arquivo | Função |
|--------|--------|
| `escolha_corre.html` | Tela de escolha do usuário |
| `Inicio_app.html` | Página inicial com as opções de criar/ver lista |
| `Listas_Salvas.html` | Visualização de listas anteriores |
| `Listinhas.html` | Navegação entre listas por categoria |
| `Momento_Mercado.html` | Inserção de preços no momento da compra |
| `nova_lista.html` | Criação de nova lista por categorias |

> No futuro, os arquivos serão organizados em pastas separadas por **HTML**, **CSS** e **scripts JS**, com nomes semânticos.

---

## 🚧 Próximos Passos

- Integração com backend para salvar dados permanentemente  
- Criação de sistema de autenticação simples  
- Visualização de histórico de compras por data  
- Comparação entre listas anteriores  

---
