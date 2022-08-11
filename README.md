# Git e Github com Nélio Alves

- git config --list = verifica configurações padrões como branch principal, git config --global user.name/user.email "".
- git reflog = Mostra o histório de commits.
- git log = Mostra o histório de commits com author, data e nome do commit salvas no github(origin/main) e local (HEAD->main).
- git log --oneline = Mostra o histório de commits de forma resumida salvas no github(origin/main) e local (HEAD->main).

---

- git reset --hard {codigo do commit} = Restaura PERMANENTEMENTE o projeto para o estado do commit ID informado (obs: AÇÂO DESTRUTIVA).

---

- git branch = lista as branches existentes.
- git branch {nomeDaNovaBranch} = cria uma nova branch.
- git checkout {nomeDaBranch} = muda para branch informada.
- git checkout -b {nomeDaNovaBranch} = Cria uma nova branch e muda para branch criada.

---

- git checkout {codigoDoCommit} = reseta o projeto ao estado do commit informado(encontra com git log) temporariamente (retorne para o último commit com "git checkout {NomeDaBranch}).

---

- git merge {nomeDaBranch} = Une a branch informada com a branch atualmente em uso.
- git diff {nomeDoArquivo} = mostra as auterações em um arquivo informado desde do último commit.

---

- git reset = remove do stage os arquivos desde o último commit.

---

- git remote -v = verifica para qual projeto no github está associado.

---

- git remote set-url git@github.com:seuusuario/seurepositorio.git = aponta para um outro projeto.
