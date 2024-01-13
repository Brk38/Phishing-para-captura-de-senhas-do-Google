# Phishing-para-captura-de-senhas-do-Google
Esse conteúdo foi produzido e postado para fins educacionais.

<h2>Ferramentas<h2>

- Kali Linux
- setoolkit

<h2>Realizando a configuração do Phishing no Kali Linux</h2>

- Acesso root:
  ```Ruby
  - sudo su
  ```
- Iniciando o setoolkit:
  ```Ruby
  - setoolkit
   ```
- Selecionado o tipo de ataque como:
  ```Ruby
  - Social-Engineering Attacks
   ```
- Selecionado vetor de ataque:
  ```Ruby
  - Web Site Attack Vectors
   ```
- Selecionado método de ataque:
  ```Ruby
  - Credential Harvester Attack Method
   ```
- Selecionado Método de ataque:
  ```Ruby
  - Site Cloner
   ```
- Selecionar o IP:
  ```Ruby
  - Foi utilizado o endereço da máquina, apenas apertar enter no teclado:
  ```
- URL para clone:
```http://www.facebook.com``` ou ```http://google.com```

### Resutados

- Apresentou-se um erro que não poderia ser executado pois a porta 80 estava habilitada
- Iniciei o fechamento dessa porta.
  
   ![Porta 80 closed](https://github.com/Brk38/Phishing-para-captura-de-senhas-do-Google/assets/142850480/d5067f7d-f67b-4be0-98ee-9821b218beca) 

- Após isso refiz a configuração e gerou corretamente o Phishing.

  ![Login facebook win10](https://github.com/Brk38/Phishing-para-captura-de-senhas-do-Google/assets/142850480/c6b077a4-6321-42c6-8342-1c15f5351ba1)

 > [!IMPORTANT]
 > Apesar de ter gerado a página clone o navegador não redireciona para o site oficial. Apesar de testes o problema continuou, acredito que seja um bloqueio do próprio script. Vale uma pesquisa para se aprofundar para fins de curiosidade

## Clone Google
 - Realizei testes gerando uma página clone do Google e funcionou perfeitamente, mas com o problema de não ser uma página clone perfeita apresentando claramente ser uma página falsa.

### Tela oficial

  ![Tela login google oficial](https://github.com/Brk38/Phishing-para-captura-de-senhas-do-Google/assets/142850480/491ccf40-be6e-4e66-b942-74d65cf5a1cb)

### Tela gerada

  ![Tela login google falsa](https://github.com/Brk38/Phishing-para-captura-de-senhas-do-Google/assets/142850480/032bd83e-aa7c-4f03-8aad-b9f5d74efd49)

- A tela google capturou com sucesso o login e redirecionamento

  ![image](https://github.com/Brk38/Phishing-para-captura-de-senhas-do-Google/assets/142850480/e366963c-4f4c-4078-8c8b-777797feb1f4)

> [!IMPORTANT]
>## Testes no Windows 7
>- Refiz testes em outra VM, agora utilizando o Windows 7 e o phishing funciona perfeitamente, redirecionando para a página oficial do Facebook.
>- > ![image](https://github.com/Brk38/Phishing-para-captura-de-senhas-do-Google/assets/142850480/6eba41cd-510a-4214-81c8-af57524523c7)
 
