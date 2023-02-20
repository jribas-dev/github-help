O Git tem uma área chamada **stash** (algo como 'esconderijo', em português), onde você pode armazenar temporariamente um instantâneo de suas alterações sem fazer o commit delas para o repositório. Ele é separado do workspace, da área de staging e do próprio repositório.

Essa funcionalidade é útil quando você fez alterações a uma branch da qual você  não quer fazer o commit, mas precisa alternar para outra branch.

- **git stash save** *"mensagem opcional para você mesmo"*
	> Isso salvará suas alterações e reverterá o workspace ao que parecia anteriormente ao último commit.
    > As alterações em stash estão disponíveis para qualquer branch daquele repositório.
- **git stash list**
    > Retornará uma lista de seus instantâneos salvos com seu respectivo índice dentro da stash
- **git stash apply** *INDICE_NO_STASH*
	> Aplica as alterações e deixa uma cópia no stash
- **git stash pop** *INDICE_NO_STASH*
    > Aplica as alterações e remove os arquivos do stash
- **git stash drop** *INDICE_NO_STASH*
    > Vai remover alterações do stash sem aplicá-las
- **git stash clear**
    > Vai limpar todo o stash

[VOLTAR](../README.md)