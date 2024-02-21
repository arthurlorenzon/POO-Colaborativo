# POO-Colaborativo
- Enzo Barbi 
- Arthur Lorenzon
- Henrique Patricio
- Eduardo Ferraz

## Comandos Git

### init

- Criar novo repositório

```
git init

```

### status

- Verificar estado dos arquivos/diretórios

```
git status

```

### add
- O comando git add é muito famoso por “adicionar conteúdo” (propor uma mudança qualquer, seja ela alterar, adicionar ou remover um conteúdo) de um arquivo local ao índice ou staging area, que terá a mudança confirmada,
```
git add "nome_do_arquivo"

```

### commit
 - O comando git commit captura um instantâneo das mudanças preparadas do projeto no momento. Os instantâneos com commit podem ser considerados versões "seguras" de um projeto, o Git nunca os altera, a menos que você peça a ele.
```
git commit -m "mensagem explicando o que foi alterado"

```


### pull

- Este comando 'puxa' todos os commits feito pelos colegas para o computador local, sincrinizando sempre todos os membros.

```
git pull

```

### push

- Este comando 'empurra' todos os commits feitos para o repositório remoto.

```
git push origin 'nome da branch'

```


### log

- Mostrar registros de commit


```
git log [<options>] [<revision-range>] [[--] <path>…​]

```

### restore

- Restaurar arquivos da árvore de trabalho

```
git restore [<options>] [--source=<tree>] [--staged] [--worktree] [--] <pathspec>…​

git restore [<options>] [--source=<tree>] [--staged] [--worktree] --pathspec-from-file=<file> 
[--pathspec-file-nul]

git restore (-p|--patch) [<options>] [--source=<tree>] [--staged] [--worktree] [--] [<pathspec>…​]

``````

