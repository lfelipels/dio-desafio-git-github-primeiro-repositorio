# Fluxo básico de trabalho com GIT
Define as atividades básicas do fluxo de trabalho com o Git.


## Atividades:
- Criar repositório remoto(GitLab ou GitHub)
- Clonar repositório remoto usando o comando ```git clone <endereco_repositorio_remoto> ```
- Realizar alterações necessárias no working directory
- Enviar todas as alterações para staging area usando o comando ```git add *```
    - Podendo especificar quais arquivos serão enviados usando o comando ```git add <nome_arquivo>```
- Adicionar os arquivos ao repositório local(Git Directory) usando o comando ```git commit -m "mensagem de commit"```

- Enviar as modificações para o repositório remoto usando o comando ```git push <remote_alias> <remote_branch>```.

    Exemplo: ```git push origin master```.

    **Considerações:**
    - Caso o repositório local esteja desatualizado em relação ao repositório remoto deve-se atualizar o repositório local usando o comando ```git pull <remote_alias> <remote_branch>```
            Exemplo: ```git pull origin master```

