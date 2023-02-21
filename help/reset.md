#### reset (usado enquanto local)
- **git reset** *[hash_do_commit]*
- **git reset** *[HEAD~2]* [2 é quantidade de commits para reverter]
- **git reset** *[--soft]* (reverte commit para o index)
- **git reset** *[--mixed]* (reverte commit para working dir)
- **git reset** *[--hard]* (reverte commit excluindo tudo que foi feito)

#### revert (usado quando já deu push no commit)
No processo do revert ele cria um novo commit revertendo (apagando) até o commit solicitado. Para evitar conflitos o procedimento deve ser feito antes que o repositório receba outros commits de outros membros do time.
- **git revert** *[hash_do_commit]*
- **git revert** *[HEAD~1]*

[VOLTAR](../README.md)