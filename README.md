🧪 Relatório de Testes – Análise de Qualidade Web
📌 Objetivo

Realizar a análise de qualidade das páginas:

https://qualidade.apprbs.com.br/certificacao

https://qualidade.apprbs.com.br/site

A avaliação foi conduzida com foco em:

Funcionalidade

Usabilidade

Desejabilidade (UX/UI)

Responsividade

Validação de Formulários

🔎 Metodologia

Foram realizados:

Testes manuais exploratórios

Testes de validação de formulário

Testes de navegação

Testes em resolução desktop e mobile

Análise de comportamento de botões e links

Ambiente de teste:

Navegador: Google Chrome (versão atual)

Dispositivo: Desktop e Mobile (modo responsivo)

Sistema Operacional: Windows / Android

🧩 Itens Identificados
📄 Página: /certificacao
Item 01 - Tela de login inacessível

Tipo: Correção
Classificação: Utilidade
Prioridade: Alta

Descrição:
Após acessar o link direto da página, não foi possível acessar a tela de login.

Resultado Esperado:
Usuário deve conseguir acessar normalmente a tela de login.

Resultado Obtido:
Tela não carrega ou não permite navegação.

Item 02 - Botão sem ação aparente

Tipo: Correção
Classificação: Utilidade
Prioridade: Alta

Descrição:
Ao clicar no botão principal da página, não ocorre nenhuma ação visível ou redirecionamento.

Resultado Esperado:
Botão deve executar ação correspondente (redirecionamento ou abertura de conteúdo).

Resultado Obtido:
Nenhuma ação é executada.

Item 03 - Ausência de validação clara em formulário

Tipo: Melhoria
Classificação: Usabilidade
Prioridade: Média

Descrição:
Ao submeter formulário com campos inválidos ou vazios, não são exibidas mensagens claras orientando o usuário.

Resultado Esperado:
Sistema deve informar quais campos precisam ser corrigidos.

Resultado Obtido:
Usuário não recebe feedback adequado.

Item 04 - Layout desalinhado em versão mobile

Tipo: Melhoria
Classificação: Desejabilidade
Prioridade: Média

Descrição:
Em resolução mobile (360x640), elementos apresentam desalinhamento e quebra de layout.

Resultado Esperado:
Layout deve se adaptar corretamente a diferentes resoluções.

Resultado Obtido:
Componentes sobrepostos ou desalinhados.

📄 Página: /site
Item 05 - Campos obrigatórios sem identificação visual

Tipo: Melhoria
Classificação: Usabilidade
Prioridade: Média

Descrição:
Campos obrigatórios não possuem indicação visual clara (ex: "*").

Resultado Esperado:
Usuário deve identificar facilmente quais campos são obrigatórios.

Resultado Obtido:
Obrigatoriedade só é percebida após tentativa de envio.

Item 06 - Ausência de mensagem de sucesso após envio

Tipo: Correção
Classificação: Utilidade
Prioridade: Alta

Descrição:
Após envio de formulário com dados válidos, não é exibida mensagem de confirmação.

Resultado Esperado:
Sistema deve exibir mensagem de sucesso ou redirecionamento.

Resultado Obtido:
Nenhuma confirmação visual é apresentada.

Item 07 - Performance de carregamento

Tipo: Melhoria
Classificação: Desejabilidade
Prioridade: Baixa

Descrição:
Tempo de carregamento inicial superior ao esperado.

Resultado Esperado:
Página deve carregar de forma otimizada.

Resultado Obtido:
Perceptível atraso no carregamento inicial.

📊 Resumo Geral
Tipo	Quantidade
Correção	3
Melhoria	4
Nova Funcionalidade	0
🚀 Considerações Finais

Foram identificados pontos críticos que impactam diretamente a utilidade da aplicação, principalmente relacionados a:

Acesso

Ações de botões

Feedback ao usuário

Recomenda-se priorização dos itens classificados como Alta prioridade, pois impactam diretamente a execução das tarefas pelo usuário.

👨‍💻 Autor

Rômulo Assunção Corrêa
Analista de Testes (QA)
Pós-graduado em Engenharia de Software com ênfase em Teste e Qualidade
