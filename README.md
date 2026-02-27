# Relatório de Testes – Análise de Qualidade Web <p>

📌 Objetivo

Realizar a análise de qualidade das páginas:
 * https://qualidade.apprbs.com.br/certificacao
 * https://qualidade.apprbs.com.br/site

A avaliação foi conduzida com foco em:
  * Funcionalidade
  * Usabilidade
  * Desejabilidade (UX/UI)
  * Responsividade
  * Validação de Formulários

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
  📄 Página: /certificacao - https://qualidade.apprbs.com.br/certificacao
  
  Item 01 - Botão "Saiba mais" sem ação.
  Tipo: Correção
  Classificação: Utilidade
  Prioridade: Baixa
  Descrição: Após clicar no botão "Saiba mais" não está realizando o redirecionamento para próxima página.
  Resultado Esperado: Botão deve executar ação correspondente (redirecionamento ou abertura de conteúdo).
  Resultado Obtido: Botão "Saiba mais" sem execução.
       
  Item 02 - Tela de Inscrição inacessível
  Tipo: Correção
  Classificação: Utilidade
  Prioridade: Alta
  Descrição: Ao realizar a inscrição preenchendo o campo de e-mail com um formato (ex: “usuario@” ou “usuario.com”), o sistema não permite o envio do formulário exibir mensagem de erro "É necessário informar base legal".
  Resultado Esperado: Usuário deve conseguir e seguir para segunda etapa.
  Resultado Obtido: Tela não carrega ou não permite seguir para segunda etapa.

  Item 03 - Cards de "Opções de Cursos" fora do padão visual dos demais
  Tipo: Melhoria
  Classificação: Usabilidade
  Prioridade: Média
  Descrição: O card dendro do carrossel “Opção de Cursos” apresenta inconsistência visual em relação aos demais cards da página, com diferença da opção "Saiba". Essa divergência compromete a padronização da interface.
  Resultado Esperado: Seguir o padão dos demais cards com a opção correta "Saiba mais".
  Resultado Obtido: Exibe somente o nome "Saiba".

  Item 04 - Cards de "Opções de Cursos" sem ação 
  Tipo: Melhoria
  Classificação: Usabilidade
  Prioridade: Média
  Descrição: Ao clicar em "Saiba mais" de qualquer card do carrossel dentro de "Opções de Cursos" não está sendo redirecionado para página seguinte.
  Resultado Esperado: Após clicar em "Saiba mais" de qualquer card do carrossel dentro de "Opções de Cursos", deve ser redirecionado para a página do card solicitado.
  Resultado Obtido: Sem ação a opção "Saiba mais".

  Item 05 - Layout desalinhado em versão mobile (reponsivo)
  Tipo: Melhoria
  Classificação: Desejabilidade
  Prioridade: Média
  Descrição: Em resolução mobile (360x640), elementos apresentam desalinhamento e quebra de layout.
  Resultado Esperado: Layout deve se adaptar corretamente a diferentes resoluções.
  Resultado Obtido: Componentes sobrepostos ou desalinhados.

  Item 06 - Página sem rodapé (Footer)
  Tipo: Correção
  Classificação: Usabilidade
  Prioridade: Média
  Descrição: A página de certificação não apresenta rodapé (footer) ao final da navegação. A ausência desse elemento impede o acesso rápido a informações institucionais, links úteis, política de privacidade, termos de uso ou canais de contato.
  Resultado Esperado: A página deve conter um rodapé padronizado, alinhado à identidade do sistema, com informações institucionais, links complementares e dados de contato.
  Resultado Obtido: A página finaliza o conteúdo sem exibir rodapé, limitando o acesso a informações adicionais e prejudicando a experiência do usuário.
  
📄 Página: /site https://qualidade.apprbs.com.br/site
  
  Item 07 - Campos obrigatórios sem identificação visual
  Tipo: Melhoria
  Classificação: Usabilidade
  Prioridade: Média
  Descrição: Campos obrigatórios não possuem indicação visual clara (ex: "*").
  Resultado Esperado: Usuário deve identificar facilmente quais campos são obrigatórios.
  Resultado Obtido: Obrigatoriedade só é percebida após tentativa de envio.

  Item 08 - Ausência de mensagem de sucesso após envio
  Tipo: Correção
  Classificação: Utilidade
  Prioridade: Alta
  Descrição: Após envio de formulário com dados válidos, não é exibida mensagem de confirmação.
  Resultado Esperado: Sistema deve exibir mensagem de sucesso ou redirecionamento.
  Resultado Obtido: Nenhuma confirmação visual é apresentada.

  Item 09 - Performance de carregamento
  Tipo: Melhoria
  Classificação: Desejabilidade
  Prioridade: Baixa
  Descrição: Tempo de carregamento inicial superior ao esperado.
  Resultado Esperado: Página deve carregar de forma otimizada.
  Resultado Obtido: Perceptível atraso no carregamento inicial.

📊 Resumo Geral
Tipo	Quantidade
Correção	4
Melhoria	5
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
