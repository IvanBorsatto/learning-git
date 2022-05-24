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

4º- Passo - Verificar a situação atual do projeto em relação ao git.

```bash
git status
```

5º- Passo - Adicionar o arquivo no git.

```bash
git add .
```

6º- Passo - Especifica a minha alteração no código

```bash
git commit -m "primeiro commit"
```

7º- Passo - Cria e especifica a branch(raiz/ramo) principal do projeto no git.

```bash
git branch -M master
```

8º- Passo - Adicionar um link de origem ao meu repositório.

```bash
git remote add origin https://github.com/<seu-repositorio.git>
```

9º- Passo - Enviar/Empurrar meus commits para o repositório.

```bash
git push -u origin master
```

## Variações do git branch

```bash
git branch
```

Lista todas as ramificações do seu repositório.
