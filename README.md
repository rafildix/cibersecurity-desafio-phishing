# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

- No navegadores Opera, Google Chrome e Microsoft Edge o clone não funcionou. 
Acredito que esses navegadores mais modernos tenham algum mecanismo que bloqueia.
Para ver o resultado destes navegadores, veja a foto: outrosnavegadores.jpg

- Abri uma VM de Windows XP e fiz o teste com o navegador Internet Explorer.
Neste caso deu certo, conforme a printe: internetexplorer.jpg ele pegou o email e a senha digitado. 

- Fiz mais um teste com uma página fake do twitter que já tinha no próprio setoolkit.
A página não é 100% fiel a página atual (2023) mas acabou rodando perfeitamente. 
conforme a printe twitterfake.jpg, da pra ver que ele conseguiu pegar o email e a senha digitada no site. 



![Alt text](./passwd.png "Optional title")