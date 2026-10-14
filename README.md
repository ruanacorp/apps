# Site da Ruana Corp 

Conteúdo de https://ruanacorp.github.io/apps/ (GitHub Pages do repositório
ruanacorp/apps). HTML estático, sem scripts, cookies nem rastreamento.
Contato: ruana.corp@gmail.com.

## Estrutura

- `index.html`: página inicial e lista de apps.
- `<app>/index.html`, `<app>/privacidade/`, `<app>/suporte/`: páginas de cada app.
- `style.css`: estilo comum (as páginas usam caminhos relativos).
- `.github/ISSUE_TEMPLATE/`: formulário de suporte das issues.

## Adicionar um app novo

1. Copie a pasta `passa-regua/` para `<novo-app>/`.
2. Ajuste nome, descrição e link da loja em `index.html`.
3. Troque `privacidade/index.html` pela política do app novo (o texto vem do
   repositório do app; as duas versões mudam juntas) e revise `suporte/`.
4. Inclua o app na lista de `index.html` e nas opções do campo "App" em
   `.github/ISSUE_TEMPLATE/suporte.yml`.

## Triagem das issues de suporte

O formulário aplica só o rótulo `suporte` (formulários não aplicam rótulo por
campo, e não usamos Actions com permissão de escrita). Na triagem, leia o campo
"App" e aplique manualmente o rótulo `app:<nome>` (ex.: `app:passa-regua`),
criado antes em Issues > Labels. Apague qualquer foto ou dado pessoal que
alguém poste, mesmo com o aviso.
