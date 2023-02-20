As ***branches*** permitem que você trabalhe em diferentes partes de um projeto sem afetar a ***branch*** principal. Quando o trabalho estiver concluído, uma ***branch*** pode ser mesclada com o projeto principal. Você pode até alternar entre ***branches*** e trabalhar em diferentes projetos sem que eles interfiram uns nos outros.

A ***Branch*** no Git é muito leve e rápida.

- **git checkout -b** *[nome da branch]*
	> Vai criar uma branch e mover-se para ela
- **git checkout** *[nome da branch]*
    > Move-se para branch informada
    > **cuidado:** seu workspace é movido junto, garanta que ele esteja limpo.
- **git branch**
	> vai listar todas branchs criadas e qual esta ativa
- **git branch -m** *[novo_nome_da_branch]*
    > vai renomear a branch ativa
- **git branch -m** *[nome_da_branch] [novo_nome_da_branch]*
    > vai renomear a branch informarda
- **git branch -d** *[nome_da_branch]*
    > vai apagar a branch informada

- ### Merge de Branch
    1. Crie uma nova branch (git checkout -b *[nome]*)
    1. Faça o trabalho na branch criada.
    2. Execute o commit do seu trabalho na branch criada.
    3. Mova-se para a branch destino (git checkout main)
    4. **git merge** *[nome_da_branch_criada]*

[VOLTAR](../README.md)