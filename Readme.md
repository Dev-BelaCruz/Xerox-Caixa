# 🖨️ Sistema de Registro de Serviços de Xerox e Impressão

Um pequeno sistema web feito em **HTML, CSS e JavaScript puro**, para gerenciar serviços e registrar vendas e relatórios mensais.  
O projeto usa **LocalStorage** e **IndexedDB** para salvar dados localmente, permitindo **cadastro, edição e exclusão de registros** sem precisar de backend.

---

## 🚀 Funcionalidades

### Página Principal (`index.html`)
- Exibe um **catálogo de serviços** de Xerox e Impressão.  
- Permite **registrar vendas** preenchendo um formulário com:
  - Tipo de serviço  
  - Quantidade  
  - Valor total  
  - Data  
- Mostra uma tabela com todas as vendas cadastradas.
- Botões de:
  - ✏️ **Editar:** carrega os dados no formulário para atualização.  
  - 🗑️ **Excluir:** remove o registro da lista e do LocalStorage.  
- Armazena as vendas automaticamente no **LocalStorage**.

---

### Página de Relatórios (`relatorios.html`)
- Permite **registrar relatórios mensais** com:
  - Mês  
  - Total de vendas  
  - Notas adicionais (opcional)  
- Os relatórios ficam salvos no **IndexedDB**.  
- Também possui botões para:
  - ✏️ **Editar:** atualiza o relatório existente.  
  - 🗑️ **Excluir:** remove o relatório do banco local.  
- Botão “Voltar à Página Principal” para retornar ao `index.html`.

---

## 🧠 Tecnologias Utilizadas
- **HTML5** – estrutura da aplicação  
- **CSS3** – estilização simples e limpa  
- **JavaScript (ES6)** – manipulação de dados, eventos e armazenamento local  
- **LocalStorage** – usado para salvar as vendas  
- **IndexedDB** – usado para armazenar relatórios mensais  

---

## 💾 Como Usar

1. Baixe ou clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/sistema-xerox.git
