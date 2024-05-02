# GIT AND GITHUB

## Iniciar novo packet na máquina de desenvolvimento local.
```
git init
```

## Definir as configurações do usuário.
```
git config --local user.name seu-usuario
```
```
git config --local user.email seuusuario@email.com
```


## Fazer o clone do repositório para a máquina local.
```
git clone <repository_url>
```
```
git clone https://github.com/eremitaio79/pauloeremita.git
```
```
git clone --branch <branch_name> <repository_url>
```
```
git clone --branch Version-1.0 https://github.com/user/repositorio.git
```


## Verificar a branch.
```
git branch
```

## Baixar as atualizações.
```
git pull
```

## Para verificar se há alterações para serem enviadas para o github.
```
git status
```

## Para colocar as alterações na área de preparação.
```
git add <nome_do_arquivo>
```
```
git add . (para enviar todos os arquivos de uma única vez)
```


## Commit das alterações para o github.
```
git commit -m "Arquivo v1"
```

## Enviar os commits locais para um repositório remoto.
```
git push <remote> <branch>
```
```
git push origin developer
```
```
git push
```

## Para criar uma nova branch
```
git checkout -b <nome_da_nova_branch>
```
```
git checkout -b desenvolvimento
```


## Para alternar para outra branch
```
git checkout <nome_da_nova_branch>
```


## Para alternar para a branch main
```
git checkout main <enter>
```

## Já estando na branch main, para fazer o merge de uma branch para a main
```
git merge v1.0 <enter>
```

## Após o merge, fazer o commit na main
```
git commit -m “commit de v1.0 para main” <enter>
```

## Por fim, para concluir o commit da branch v1.0 para a main
```
git push origin main <enter>
```

## O comando git push --set-upstream
```
git push --set-upstream origin prototype
```

O comando git push --set-upstream origin prototype serve para empurrar as alterações locais de uma branch (neste caso, a branch atual em que você está trabalhando) para o repositório remoto no GitHub e definir a conexão entre a branch local e a branch remota.
Vamos analisar cada parte do comando:
* git push: Este comando é usado para enviar os commits locais para um repositório remoto.
* --set-upstream ou -u: Esta opção configura a branch local para rastrear a branch remota. Isso significa que, após executar este comando uma vez, você pode simplesmente usar git push e git pull sem especificar o nome da branch remota e local. O Git lembrará automaticamente a associação entre elas.
* origin: Este é o nome do repositório remoto. Por convenção, quando você clona um repositório, o Git atribui o nome "origin" ao repositório remoto.
* prototype: Este é o nome da branch remota para onde você está empurrando as alterações.
Então, o comando completo está dizendo ao Git para empurrar as alterações da branch local atual para a branch remota chamada "prototype" no repositório remoto chamado "origin", e configurar a branch local para rastrear a branch remota "prototype". Isso é útil porque simplifica os comandos futuros, como git push e git pull, uma vez que a conexão entre as branches locais e remotas está estabelecida.
