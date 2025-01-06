# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

1. Com usuário root: No terminal, use o comando sudo su e insira sua senha root.
2. Entre na ferramenta setoolkit: No terminal, digite setoolkit para entrar na ferramenta de ataques de engenharia social.
3. Na seleção do menu, escolha: 1) Social-Engineering Attacks (Tipo de ataque).
4. Na próxima seleção do menu, escolha: 2) Website Attack Vectors (Vetor de ataque).
5. Na próxima seleção do menu, escolha: 3) Credential Harvester Attack Method (Método de ataque).
6. Na próxima seleção do menu, escolha: 2) Site Cloner (Método de ataque).
7. Obtendo o endereço da máquina: Use o comando ifconfig (A própria ferramenta já indica o seu IP, que será o servidor onde receberá os dados dos ataques realizados).
8. URL para clone: http://www.facebook.com (Essa URL será clonada neste ataque).
9. Em uma aba de qualquer navegador, insira o seu IP 192.168.0.15, que servirá de servidor para onde os dados irão.
10. Digite um email e senha de exemplo para que o ataque possa recolher esses dados.
11. Agora, na tela do Kali Linux, você verá que o ataque foi bem-sucedido, pois colheu os dados que o usuário inseriu na tela de login falsa do Facebook.

### Resutados

![Alt text](./passwd.png "Optional title")
