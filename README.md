Aqui está uma lista com os principais comandos do **Termux** e exemplos de uso. Para facilitar, os comandos estão organizados por categoria: navegação, manipulação de arquivos, gerenciamento de pacotes, controle de sistema, redes, e outros.

---

## **Navegação no Sistema de Arquivos**
1. **`pwd`**: Exibe o diretório atual.  
   - **Exemplo**:  
     ```bash
     pwd
     ```

2. **`ls`**: Lista os arquivos e diretórios.  
   - **Exemplo**:  
     ```bash
     ls -l
     ls -a
     ```

3. **`cd`**: Navega entre diretórios.  
   - **Exemplo**:  
     ```bash
     cd /sdcard
     cd ..
     ```

---

## **Manipulação de Arquivos e Diretórios**
4. **`touch`**: Cria um novo arquivo.  
   - **Exemplo**:  
     ```bash
     touch novo_arquivo.txt
     ```

5. **`mkdir`**: Cria um novo diretório.  
   - **Exemplo**:  
     ```bash
     mkdir meu_diretorio
     ```

6. **`cp`**: Copia arquivos ou diretórios.  
   - **Exemplo**:  
     ```bash
     cp arquivo.txt /sdcard/
     ```

7. **`mv`**: Move ou renomeia arquivos.  
   - **Exemplo**:  
     ```bash
     mv arquivo.txt novo_nome.txt
     mv arquivo.txt /sdcard/
     ```

8. **`rm`**: Remove arquivos ou diretórios.  
   - **Exemplo**:  
     ```bash
     rm arquivo.txt
     rm -r meu_diretorio
     ```

---

## **Gerenciamento de Pacotes**
9. **`pkg search`**: Pesquisa pacotes disponíveis.  
   - **Exemplo**:  
     ```bash
     pkg search python
     ```

10. **`pkg install`**: Instala pacotes.  
    - **Exemplo**:  
      ```bash
      pkg install git
      ```

11. **`pkg uninstall`**: Remove pacotes instalados.  
    - **Exemplo**:  
      ```bash
      pkg uninstall vim
      ```

12. **`pkg update`**: Atualiza os repositórios.  
    - **Exemplo**:  
      ```bash
      pkg update
      ```

13. **`pkg upgrade`**: Atualiza todos os pacotes instalados.  
    - **Exemplo**:  
      ```bash
      pkg upgrade
      ```

---

## **Controle do Sistema**
14. **`clear`**: Limpa o terminal.  
    - **Exemplo**:  
      ```bash
      clear
      ```

15. **`exit`**: Sai do terminal.  
    - **Exemplo**:  
      ```bash
      exit
      ```

16. **`termux-setup-storage`**: Concede acesso ao armazenamento do dispositivo.  
    - **Exemplo**:  
      ```bash
      termux-setup-storage
      ```

---

## **Comandos de Redes**
17. **`ping`**: Testa conectividade com outro host.  
    - **Exemplo**:  
      ```bash
      ping google.com
      ```

18. **`curl`**: Faz requisições HTTP.  
    - **Exemplo**:  
      ```bash
      curl https://example.com
      ```

19. **`wget`**: Baixa arquivos de URLs.  
    - **Exemplo**:  
      ```bash
      wget https://example.com/arquivo.zip
      ```

20. **`ssh`**: Acessa outro sistema via SSH.  
    - **Exemplo**:  
      ```bash
      ssh user@192.168.1.1
      ```

---

## **Outros Comandos Úteis**
21. **`git`**: Controle de versão.  
    - **Exemplo**:  
      ```bash
      git clone https://github.com/repositorio.git
      ```

22. **`python`**: Executa scripts Python.  
    - **Exemplo**:  
      ```bash
      python script.py
      ```

23. **`nano`**: Editor de texto no terminal.  
    - **Exemplo**:  
      ```bash
      nano arquivo.txt
      ```

24. **`top`**: Mostra processos em execução.  
    - **Exemplo**:  
      ```bash
      top
      ```

25. **`htop`**: Gerenciador de tarefas (instale antes).  
    - **Exemplo**:  
      ```bash
      htop
      ```

---

Caso precise de mais detalhes sobre um comando, use o manual:  
```bash
man [comando]
```

Ou peça ajuda diretamente:  
```bash
[comando] --help
```
