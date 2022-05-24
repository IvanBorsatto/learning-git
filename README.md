# learning-git

_1º- Passo - Crio uma pasta dentro da minha máquina, onde irei alocar meu “projeto” (no terminal)._

```bash
mkdir "nome-da-pasta"
```

_2º- Passo - Joga o que é printado na tela para dentro de um arquivo._

```bash
echo "# teste" >> README.md
```

_3º- Passo - Inicialização do git no projeto._

```bash
git init
```

_4º- Passo - Verificar a situação atual do projeto em relação ao git._

```bash
git status
```

_5º- Passo - Adicionar o arquivo no git._

```bash
git add .
```

_6º- Passo - Especifica a minha alteração no código_

```bash
git commit -m "primeiro commit"
```

_7º- Passo - Cria e especifica a branch(raiz/ramo) principal do projeto no git._

```bash
git branch -M master
```

_8º- Passo - Adicionar um link de origem ao meu repositório._

```bash
git remote add origin https://github.com/<seu-repositorio.git>
```

_9º- Passo - Enviar/Empurrar meus commits para o repositório._

```bash
git push -u origin master
```

## Variations of the git branch

```bash
git branch
```

Lista todas as ramificações do seu repositório.

```bash
 git branch --list.
```

Sinônimo de git branch

```bash
git branch <nome-da-branch>
```

Criar uma nova ramificação.

```bash
git branch -d <-nome-da-branch>
```

Exclui uma ramificação especificada. Esta é uma operação “segura” em que o Git impede que você exclua a ramificação se tiver mudanças não mescladas.

```bash
git branch -D <branch>
```

Força a exclusão da ramificação especificada, mesmo que ela tenha mudanças não mescladas. Este é o comando a ser usado se você quiser excluir de modo permanente todas as confirmações associadas a uma linha particular de desenvolvimento.

```bash
git branch -m <branch>
```

Renomear a ramificação atual para .

```bash
git branch -a
```

Listar todas as ramificações remotas.
