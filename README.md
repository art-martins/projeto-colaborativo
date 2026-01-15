# projeto-colaborativo
Projeto da tarefa_01 de treino de Git e GitHub
## 1. Criação do repositório no GitHub

Nesta etapa foi criado um repositório chamado `projeto-colaborativo` diretamente no GitHub. Com a criação dos arquivos "README.md" e "tarefas.txt".

![Criação do repositório no GitHub](prints/criacao_repositorio.png)

---

## 2. Clonagem do repositório

O repositório remoto foi clonado para a máquina local utilizando o comando "git clone".

![Git clone realizado com sucesso](prints/git_clone.png)

---

## 3. Sincronização com o repositório remoto (git pull)

Após a clonagem, foi executado o comando "git pull".  
Como não havia alterações adicionais no repositório remoto, o Git retornou a mensagem
informando que o repositório já estava atualizado.

![Git pull sem alterações](prints/git_pull.png)

---

## 4. Criação da branch de desenvolvimento

Foi criada uma nova branch chamada "feature-nova-tarefa", onde as alterações foram realizadas
sem afetar diretamente a branch principal ("main").

![Criação da branch feature-nova-tarefa](prints/criacao_nova_branch_feature.png)

---

## 5. Alteração do arquivo "tarefas.txt" e verificação das alterações (git status)

Após a edição do arquivo e inserção de duas novas "tarefas", foi utilizado o comando "git status" para verificar os arquivos modificados.

![Verficação dos arquivos modificados ](prints/git_status.png)

---

## 6. Preparação e commit das alterações (git add) e (git commit)

O arquivo modificado foi adicionado à staging area e, em seguida, foi realizado o commit
com uma mensagem descritiva.

![Modificações adicionadas](prints/git_add.png)
![Commit realizado](prints/git_commit.png)

---

## 7. Envio da branch para o repositório remoto (git push)

A branch "feature-nova-tarefa" foi enviada para o repositório remoto no GitHub utilizando o comando "git push".

![Git push da branch feature-nova-tarefa](prints/git_push.png)

---

## 8. Abertura do Pull Request

Após o envio da branch, foi aberto um Pull Request solicitando a integração das alterações
da branch `feature-nova-tarefa` para a branch `main`.

![Criação do Pull Request](prints/criacao_PR.png)

---
## 9. Pull Request criado com sucesso

O Pull Request foi criado com sucesso e ficou disponível para revisão e aprovação, finalizando o fluxo básico de colaboração proposto na atividade.

![Pull Request criado](prints/PR_criado.png)

---
## 🔗 Links

- Repositório: https://github.com/art-martins/projeto-colaborativo
- Pull Request: https://github.com/art-martins/projeto-colaborativo/pull/1