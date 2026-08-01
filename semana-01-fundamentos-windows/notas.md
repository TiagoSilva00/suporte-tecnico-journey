# Semana 01 — Fundamentos de Windows

## Objetivo da semana
Aprender os conceitos fundamentais do sistema operacional Windows: interface, 
sistema de arquivos, contas de usuário, permissões e ferramentas básicas de 
diagnóstico — habilidades essenciais para atuação em Suporte Técnico.

## Atividades realizadas
- [x] Sala "Windows Fundamentals 1" (TryHackMe) — **concluída** ✅
  - 10 tarefas concluídas | 104 pontos ganhos

## O que aprendi

### Edições do Windows
- O Windows Pro permite ativar **BitLocker** (criptografia de disco completo), 
  recurso não disponível na versão Home.

### Área de trabalho e barra de tarefas
- É possível ocultar a caixa de pesquisa (`Hidden`) e o botão de Visualização 
  de Tarefas (`Show Task View button`) através do menu de contexto da barra 
  de tarefas.
- Além do Relógio e Rede, a Central de Ações (`Action Center`) também fica 
  visível na Área de Notificação.

### Sistema de arquivos
- O Windows moderno usa **NTFS** (`New Technology File System`), sucessor do 
  FAT16/FAT32 e HPFS. NTFS é um sistema de arquivos "journaling" (registra 
  alterações para recuperação em caso de falhas).

### Contas de usuário e grupos
- Explorei o **Gerenciamento do Computador** > Usuários e Grupos Locais para 
  visualizar contas do sistema.
- A conta **Guest** é a conta integrada para acesso de convidados, com 
  descrição `window$Fun1!`.
- Outro usuário de exemplo (`tryhackmebilly`) pertence aos grupos 
  `Remote Desktop Users` e `Users`.

### Ferramentas úteis
- Atalho de teclado para abrir o **Gerenciador de Tarefas**: `Ctrl+Shift+Esc` 
  (diferente do `Ctrl+Alt+Delete`, que abre um menu intermediário).

## Anotações
- Sala 100% feita através da VM do próprio TryHackMe (via navegador), já que 
  meu PC atual não suporta rodar uma VM Windows local sem travar.
- Tive dificuldade pontual em algumas respostas que exigiam o texto exato 
  esperado pela sala (ex: "Action Center" vs. tentativas anteriores como 
  "Volume"/"Battery") — reforça a importância de verificar informações 
  técnicas em vez de assumir por lógica.

## Reflexão da semana
Ótimo primeiro contato prático com fundamentos do Windows do ponto de vista 
de suporte técnico: navegação de interface, sistema de arquivos, contas de 
usuário e ferramentas de diagnóstico básicas. A sala trouxe uma boa mistura 
de teoria e prática hands-on na VM.

## Próximos passos
- [ ] Continuar para "Windows Fundamentals 2" (TryHackMe)
