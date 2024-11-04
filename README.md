# Guia prático de uso do GitHub 
***importante:*** *na internet dá UnB não vai funcionar. É necessário conectar a outra internet para conseguir fazer o clone com ssh e o push *

1. **Criar um repositório no GitHub**:
   - Acesse a plataforma [GitHub](https://github.com/).
   - Clique em "New repository" no seu perfil.
   - Preencha o nome do repositório, a descrição opcional, e escolha entre "Público" ou "Privado".
   - Clique em "Create repository" para finalizar.

2. **Escolher local para Clonar**:
   - No terminal do seu computador, use o comando `cd` para navegar até o diretório onde você deseja clonar o repositório. Por exemplo:  
     ```bash
     cd /caminho/para/o/diretorio
     ```

3. **Clonar o repositório usando SSH**:
   - Copie o link SSH do repositório GitHub (começa com `git@github.com:`).
   - Execute o comando `git clone` seguido do link SSH:  
     ```bash
     git clone git@github.com:usuario/repositorio.git
     ```

4. **Navegar até o diretório da pasta clonada**:
   - Entre no diretório da pasta clonada usando:  
     ```bash
     cd repositorio
     ```

5. **Fazer alterações na pasta**:
   - Você pode editar arquivos existentes ou criar novos arquivos usando editores de texto, como `vim`, `nano` ou editores gráficos como o VSCode. Assim que selecionar o diretório, para abrir com VSCode, basta digitar no terminal:
    ```bash
    code .
    ```

6. **Adicionar as alterações ao staging com `git add .`**:
   - Para preparar todas as alterações feitas para o commit, utilize:  
     ```bash
     git add .
     ```

7. **Fazer o `git commit`**:
   - Crie um commit para registrar as alterações:  
     ```bash
     git commit -m "Mensagem descritiva das alterações"
     ```

8. **Fazer um `git pull`**:
   - Antes de enviar suas alterações, é recomendável atualizar sua branch local com as últimas mudanças do repositório remoto:  
     ```bash
     git pull origin main
     ```
   - (Substitua `main` pela branch correta, se for diferente).

