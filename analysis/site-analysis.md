# Análise do site: https://sistema-rh-sandy.vercel.app/#requests

## Informações gerais
- **Título da página:** "Sistema DP Corporativo | Gestão de RH".
- **Navegação principal (menu):** Dashboard, Funcionários, Empresas, Documentos IA, Férias, Escala, Benefícios, Solicitações.
- **Seções principais (headings):**
  - Sistema RH (aparece duplicado)
  - Tempo de Empresa (Anos/Meses)
  - Distribuição Etária
  - Motivos de Saída
  - Distribuição por Gênero
  - Gerenciar Empresas
  - Arraste documentos aqui
  - Controle de Férias
  - Escala de Domingos
  - Gestão de Benefícios (VA / VT)
  - Formulários e Solicitações
  - Configurações
  - Interface do Sistema
  - Personalizar Menu
  - Gerenciamento de Dados

## Ações e botões identificados
- **Acesso:** Acessar Sistema, Criar Conta.
- **Notificações:** Notificações (com ação "Marcar lidas" e indicação de "Nenhuma notificação nova").
- **Funcionários:** Novo Funcionário, Limpar, Ativos, Demitidos, Exportar.
- **Empresas:** Nova Empresa.
- **Documentos IA:** Selecionar Arquivos, PDF.
- **Férias:** Vencidas, A Vencer, Concedidas, Feriados, Sincronizar, PDF.
- **Benefícios/VA/VT:** Salvar.
- **Solicitações:**
  - Solicitação de Vale Transporte (descrição: roteiro + opção pelo benefício para novos colaboradores).
  - Termo de Renúncia / Recusa (descrição: declaração de não utilização do VT).
  - Cancelar, Confirmar.
- **Configurações:** Interface, Menu Lateral, Dados, Backup JSON, Exportar XML, Selecionar Arquivo Backup, Apagar Tudo, Salvar Alterações.

## Observações iniciais
- A página concentra um **dashboard de RH/DP** com módulos para funcionários, empresas, documentos, férias, escala, benefícios e solicitações.
- Há presença de **múltiplos fluxos administrativos** (ex.: documentos IA, backup, exportação, formulários).
- O texto de algumas áreas indica **funcionalidades de upload/download** (ex.: "Arraste documentos aqui", "Exportar XML", "Backup JSON").

## Pontos de atenção / melhorias potenciais
- **Consistência de headings:** "Sistema RH" aparece duas vezes, o que pode indicar repetição de bloco ou cabeçalho duplicado.
- **Acessibilidade:** verificar se botões com textos longos (ex.: ações de notificações, descrições de solicitações) têm labels/aria adequados para leitores de tela.
- **Microcópia:** padronizar o uso de termos (ex.: "PDF" como botão em múltiplos módulos pode exigir contexto ou ícone/tooltip adicional).

