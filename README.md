Documentação MySQL — Guia Completo

Estudos e referência prática baseados no curso de MySQL do professor Gustavo Guanabara.


📋 Sobre o Projeto
Este projeto é uma documentação interativa em HTML sobre os fundamentos do MySQL, organizada de forma didática com exemplos de código com syntax highlighting, botões de cópia e navegação rápida entre seções.
O material foi construído como material de estudo pessoal, servindo também como referência rápida para consulta dos principais comandos SQL.

🖥️ Preview
Abra o arquivo index.html diretamente no navegador para visualizar a documentação completa com todos os recursos visuais e interativos.

📂 Estrutura do Projeto
.
└── index.html    # Documentação completa em página única (SPA estática)

📚 Conteúdo Abordado
1. DDL — Data Definition Language
Comandos para definir e modificar a estrutura do banco de dados.
ComandoDescriçãoCREATE TABLECria uma nova tabela com colunas, tipos e constraintsALTER TABLEAdiciona, remove ou modifica colunasMODIFY COLUMNAltera tipo, tamanho, NOT NULL e DEFAULT de uma colunaCHANGE COLUMNRenomeia uma coluna e suas característicasRENAME TABLERenomeia uma tabelaDROP TABLERemove completamente uma tabela

2. DML — Data Manipulation Language
Comandos para inserir, atualizar e remover dados.
ComandoDescriçãoINSERTInsere novos registrosSELECTConsulta registrosUPDATEAtualiza registros existentesDELETERemove registros específicosTRUNCATERemove todos os registros mantendo a estrutura

3. DQL — Data Query Language
Consultas avançadas e filtros de dados.
RecursoDescriçãoSELECT colunas específicasSeleção parcial de dadosWHEREFiltragem por condiçãoBETWEENFiltro por intervalo de valoresORDER BYOrdenação de resultadosLIMITLimitação de quantidade de registrosLIKEBusca por padrão em textoINFiltro por lista de valores

4. Funções de Agregação
FunçãoDescriçãoMAX()Valor máximoMIN()Valor mínimoAVG()Média dos valoresCOUNT()Contagem de registrosSubconsultasConsultas aninhadas para filtros dinâmicos

5. Agrupamento
RecursoDescriçãoGROUP BYAgrupa registros por uma ou mais colunasHAVINGFiltra grupos após o agrupamentoROUND()Arredondamento de valores numéricosWHERE vs HAVINGComparativo de quando usar cada um

⚡ Ordem de Execução SQL
FROM → WHERE → GROUP BY → HAVING → SELECT → ORDER BY → LIMIT

💡 Dica: WHERE filtra antes do agrupamento (registros individuais); HAVING filtra depois do agrupamento (grupos).


🎨 Recursos da Interface

✅ Syntax highlighting para SQL (keywords, strings, números, comentários)
✅ Botão de cópia em cada bloco de código
✅ Navegação rápida com menu lateral (âncoras)
✅ Scroll suave entre seções
✅ Botão "voltar ao topo"
✅ Design responsivo (mobile-friendly)
✅ Tema escuro com paleta inspirada no MySQL


🛠️ Tecnologias Utilizadas

HTML5 — estrutura e marcação semântica
CSS3 — layout, tema escuro, responsividade
JavaScript (Vanilla) — interatividade (cópia, scroll)
Google Fonts — Inter (interface) + Fira Code (código)

🚀 Como Usar
Nenhuma instalação necessária. Basta:
# Clone ou baixe o repositório
git clone https://github.com/totalo-dev/MySQL

# Abra o arquivo no navegador
open index.html
# ou simplesmente dê duplo clique no arquivo

📖 Referência

Curso de MySQL — Gustavo Guanabara / Curso em Vídeo
Documentação oficial: dev.mysql.com/doc

📝 Licença
Este projeto é de uso educacional e pessoal. O conteúdo foi desenvolvido como material de estudo com base no curso mencionado.
