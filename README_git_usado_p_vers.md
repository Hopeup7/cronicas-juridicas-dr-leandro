📘 Histórico e Guia de Comandos Git — Projeto Blog Le

Este documento registra os comandos Git utilizados no desenvolvimento do projeto Blog Dr. Leandro Alves de Souza, destacando convenções de commits, flags importantes e aprendizados práticos pela e para a euipe Powered By Hope Up 7.DEV.

🛠️ Inicialização do Repositório
bash
git status
git pull
git init
git status → Mostra o estado atual do repositório.

Antes do git init, retornou erro: "not a git repository".

git pull → Tentou buscar atualizações, mas sem repositório inicializado não funcionou.

git init → Criou o repositório local (.git/).

📌 Aprendizado: Sempre inicializar (git init) antes de usar comandos como status ou pull.

📂 Adicionando Arquivos
bash
git add .
git status
git add . → Adiciona todos os arquivos não rastreados.

git status → Mostrou os arquivos preparados para commit.

⚠️ Erro comum: digitar gis status em vez de git status.

📝 Primeiro Commit
bash
git commit -m "feat: adicionar estrutura inicial do Blog Dr. Leandro Alves de Souza em HTML e CSS
Inclui:
- Página principal em HTML5 com narrativa de 'Madame Anônima'
- Estrutura de estilos em CSS3 responsivo
- Seções institucionais (perfil, contato, ajuda, anúncios)
- Conteúdo jurídico com base no Código Penal e LEP
- Recursos visuais e representações artísticas
"
Mensagem de commit seguiu a convenção Conventional Commits:

feat: → Nova funcionalidade.

Descrição clara e detalhada.

Lista de mudanças no corpo da mensagem.

📌 Boa prática: usar prefixos como feat:, fix:, refactor:, docs:, style:, test:, chore:.

🌿 Gerenciamento de Branches
bash
git branch -M main
Renomeou a branch padrão de master para main.

Convenção moderna adotada pelo GitHub.

🔗 Conexão com Repositório Remoto
bash
git remote add origin https://github.com/Hopeup7/cronicas-juridicas-dr-leandro
git push -u origin main
git remote add origin <url> → Vincula repositório local ao remoto.

git push -u origin main → Envia commits para o GitHub e define main como branch padrão de rastreamento.

⚠️ Erro inicial: tentou git push -u origin master, mas a branch já havia sido renomeada para main.

🔄 Sincronização
bash
git pull
git remote -v
git branch -vv
git pull → Atualiza branch local com remoto.

git remote -v → Lista URLs de fetch/push.

git branch -vv → Mostra branch atual e tracking remoto.


✨ Refatoração de Arquivos
bash
git add index.html
git add -A
git commit -m "refactor: renomear blog_le_index.html para index.html para compatibilidade com GitHub Pages"
git push
git add index.html → Adicionou novo arquivo.

git add -A → Capturou também a exclusão/renomeação.

refactor: → Prefixo correto para mudanças estruturais sem alterar funcionalidade.

Push → Atualizou repositório remoto.

📑 Convenções de Commits Usadas
Prefixo	Significado
feat:	Nova funcionalidade
refactor:	Alteração de código que melhora estrutura/organização sem mudar comportamento
(futuro) fix:	Correção de bug
(futuro) docs:	Alterações em documentação
(futuro) style:	Ajustes de formatação, sem impacto no código

🚩 Flags e Opções Importantes
-m → Mensagem inline no commit.

-M → Força renomeação de branch.

-u → Define upstream (branch de rastreamento remoto).

-A → Adiciona todas as mudanças (novos, modificados e deletados).

📚 Descobertas e Aprendizados
Erro comum: tentar git pull antes de configurar branch remota.

Importância do git status: sempre verificar antes e depois de add ou commit.

Conventional Commits: ajudam a manter histórico limpo e semântico.

Renomear branch para main: alinhado ao padrão GitHub.

Compatibilidade com GitHub Pages: index.html precisa estar na raiz.

Fluxo correto: git init → git add → git commit → git branch -M main → git remote add origin → git push -u origin main.

✅ Estado Final
bash
git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
📌 Repositório sincronizado com GitHub, branch main configurada, commits semânticos aplicados.

👉 Esse documento pode ser expandido futuramente com alias úteis, boas práticas de branching (Git Flow) e estratégias de merge/rebase.