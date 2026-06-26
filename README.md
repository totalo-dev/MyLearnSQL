# Documentação MySQL — Guia Completo

Estudos e referência prática baseados no curso de MySQL do professor Gustavo Guanabara.

---
## 👥 Colaboradores

Este projeto foi desenvolvido em parceria com:

- João (Totalo-dev) Leal — Front-end
- Felix (tenfelix) — Front-end

## 📋 Sobre o Projeto

Este projeto é uma documentação interativa em HTML sobre os fundamentos do MySQL, organizada de forma didática, com exemplos de código utilizando syntax highlighting, botões de cópia e navegação rápida entre seções.

O material foi construído como conteúdo de estudo pessoal, servindo também como referência rápida para consulta dos principais comandos SQL.

---

## 🖥️ Preview

Abra o arquivo `index.html` diretamente no navegador para visualizar a documentação completa com todos os recursos visuais e interativos.

---

## 🖥️ Site acess

Abra [MyLearnSQL](https://totalo-dev.github.io/MyLearnSQL/?utm_source=chatgpt.com) para visualização sem necessidade de instalação.


---

## 📂 Estrutura do Projeto

```txt
.
└── index.html    # Documentação completa em página única (SPA estática)
```

---

## 📚 Conteúdo Abordado

### 1. DDL — Data Definition Language

Comandos para definir e modificar a estrutura do banco de dados.

| Comando | Descrição |
|---|---|
| CREATE TABLE | Cria uma nova tabela com colunas, tipos e constraints |
| ALTER TABLE | Adiciona, remove ou modifica colunas |
| MODIFY COLUMN | Altera tipo, tamanho, NOT NULL e DEFAULT de uma coluna |
| CHANGE COLUMN | Renomeia uma coluna e suas características |
| RENAME TABLE | Renomeia uma tabela |
| DROP TABLE | Remove completamente uma tabela |

---

### 2. DML — Data Manipulation Language

Comandos para inserir, atualizar e remover dados.

| Comando | Descrição |
|---|---|
| INSERT | Insere novos registros |
| SELECT | Consulta registros |
| UPDATE | Atualiza registros existentes |
| DELETE | Remove registros específicos |
| TRUNCATE | Remove todos os registros mantendo a estrutura |

---

### 3. DQL — Data Query Language

Consultas avançadas e filtros de dados.

| Recurso | Descrição |
|---|---|
| SELECT colunas específicas | Seleção parcial de dados |
| WHERE | Filtragem por condição |
| BETWEEN | Filtro por intervalo de valores |
| ORDER BY | Ordenação de resultados |
| LIMIT | Limitação da quantidade de registros |
| LIKE | Busca por padrão em texto |
| IN | Filtro por lista de valores |

---

### 4. Funções de Agregação

| Função | Descrição |
|---|---|
| MAX() | Valor máximo |
| MIN() | Valor mínimo |
| AVG() | Média dos valores |
| COUNT() | Contagem de registros |
| Subconsultas | Consultas aninhadas para filtros dinâmicos |

---

### 5. Agrupamento

| Recurso | Descrição |
|---|---|
| GROUP BY | Agrupa registros por uma ou mais colunas |
| HAVING | Filtra grupos após o agrupamento |
| ROUND() | Arredondamento de valores numéricos |
| WHERE vs HAVING | Comparativo de quando usar cada um |

---

## ⚡ Ordem de Execução SQL

```txt
FROM → WHERE → GROUP BY → HAVING → SELECT → ORDER BY → LIMIT
```

💡 **Dica:** `WHERE` filtra antes do agrupamento (registros individuais); `HAVING` filtra depois do agrupamento (grupos).

---

## 🎨 Recursos da Interface

- ✅ Syntax highlighting para SQL (keywords, strings, números e comentários)
- ✅ Botão de cópia em cada bloco de código
- ✅ Navegação rápida com menu lateral (âncoras)
- ✅ Scroll suave entre seções
- ✅ Botão “voltar ao topo”
- ✅ Design responsivo (mobile-friendly)
- ✅ Tema escuro com paleta inspirada no MySQL

---

## 🛠️ Tecnologias Utilizadas

- HTML5 — estrutura e marcação semântica
- CSS3 — layout, tema escuro e responsividade
- JavaScript (Vanilla) — interatividade (cópia e scroll)
- Google Fonts — Inter (interface) + Fira Code (código)

---

## 🚀 Como Usar offline

Basta:

```bash
# Clone ou baixe o repositório
git clone https://github.com/totalo-dev/MySQL

# Abra o arquivo no navegador
open index.html

# Ou simplesmente dê duplo clique no arquivo
```

---

## 📖 Referência

- Curso de MySQL — Gustavo Guanabara / Curso em Vídeo
- Documentação oficial: `dev.mysql.com/doc`

---

## 📝 Licença

Este projeto é de uso educacional e pessoal. O conteúdo foi desenvolvido como material de estudo com base no curso mencionado.


## Last Updated

Automatically updated during repository processing.


## Status do Projeto
- Estado: em progresso
- Fases: não definidas
- Última verificação: 18/06/2026
