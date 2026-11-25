# Hikki Notes 1.0 — R09

PWA pessoal local-first. Publique os arquivos na raiz do GitHub Pages (main, /). Abra em HTTPS e instale pelo Chrome Android.

Backups ZIP em Ajustes incluem anexos; JSON antigo também aceito. Restauração mescla por ID. PIN não criptografa. Nunca publique backups no GitHub.

R05: recorrência personalizada em dias (1–365), vínculos reversos, histórico e cronômetro visível, total dos últimos sete dias e notificações opcionais genéricas enquanto a página executa. Não há garantia de alarmes com aplicativo fechado ou suspenso.

Testes manuais: CRUD de cada módulo, recorrência, vínculos, cronômetro, notificações, anexos, backup/restauração, reinício e offline. Use dados fictícios.

R06: privacidade por lembrete, privada por padrão inclusive para registros antigos; modo público mostra título e conteúdo. Consulta de armazenamento nos ajustes. Notificações dependem das permissões e da execução da página.

## R07
Ícones SVG locais, foco visível, melhorias de tela estreita, lembretes atrasados por horário e reabertura, proteção contra registros órfãos visíveis, validação adicional de importação e limpeza de URLs de anexos. Exclusão de pasta oculta descendentes até restauração. Testes de navegador ainda necessários.

## R08
- Proteção contra conclusão duplicada de lembretes e geração repetida da próxima ocorrência.
- Recorrência mensal preserva o dia original quando possível.
- Criação de lembretes vinculados diretamente nos cards; vínculos ocultos não são oferecidos.
- Novos registros podem ser vinculados ou excluídos sem reabrir o editor.
- Flashcards não duplicam a resposta ao tocar novamente.
- Cache R08. Testes funcionais no Android ainda pendentes.

## R09
Pesquisa sem distinção de acentos, por múltiplas palavras, incluindo tarefas, humor e data. Busca global informa ausência de resultados. Editor impede fechamento durante processamento de anexos e evita alertas de validação durante digitação. Cache R09.

## R10
Aviso de atualização pendente da PWA, sem recarregar automaticamente durante edição. Interceptação de cache restrita ao escopo do aplicativo.

### R11
Cache de leitura restrito à versão ativa, verificação de alertas na inicialização e estado vazio da lixeira.

### R12
Correção da trava de conclusão, intervalo inteiro de recorrência e validação de anexos antes da importação.
