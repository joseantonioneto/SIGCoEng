# Contribuindo

## Solicitações de alteração / Pull Requests

Primeiro, você precisa criar um fork do repositório [joseantonioneto/SIGCoEng](https://github.com/joseantonioneto/SIGCoEng) para confirmar suas alterações. Métodos para dar um fork num repositório podem ser encontrados no [Documentação do GitHub ](https://docs.github.com/en/get-started/quickstart/fork-a-repo).

Em seguida, adicione seu fork como um projeto local:

```
# Using HTTPS
https://github.com/joseantonioneto/SIGCoEng.git

# Using SSH
git@github.com:joseantonioneto/SIGCoEng.git
```

> [Qual URL remoto deve ser usado?](https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories)

## Receba atualizações remotas

Para se manter atualizado com o repositório central:

```
git pull upstream master
```

## Escolha um branch base

Antes de iniciar o desenvolvimento, você precisa saber em qual branch basear suas modificações/adições. Em caso de dúvida, use master.

| Type of change    |      |              Branches |
| :---------------- | :--: | --------------------: |
| Documentation     |      |              `master` |
| Bug fixes         |      |              `master` |
| New features      |      |              `master` |
| New issues models |      | `YOUR-USERNAME:patch` |

```
# Mude para o branch desejado
git switch master

# Retire quaisquer alterações upstream
git pull

# Crie um novo branch para trabalhar
git switch --create patch/1234-name-issue
```
