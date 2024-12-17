Aqui está um README.md detalhado e estilizado para o GitHub com emojis e um layout claro:

```markdown
# 🚀 SSH Brute Force Enumerator 🔑

![CTF Tool] (https://img.shields.io/badge/CTF-Tool-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-green?style=for-the-badge)


### 📜 **Descrição**
Uma ferramenta poderosa e prática para uso em **CTFs** ou aprendizado em segurança cibernética!  
Esta aplicação realiza **brute force** em servidores SSH utilizando uma chave privada (`id_rsa`) para identificar usuários válidos.  

🔒 **Atenção**: Este projeto é para **fins educacionais e éticos** apenas. Não use para fins maliciosos!

---

## 📦 **Funcionalidades**
- 🎨 **Interface CLI** com banner estilizado.
- 🧑‍🤝‍🧑 Teste de múltiplos usuários em servidores SSH.
- 🛠️ Gravação de resultados bem-sucedidos em arquivos locais.
- 🚀 Otimizado para operações rápidas e testes em ambientes controlados.

---

## 🎯 **Pré-requisitos**
Antes de começar, você precisará ter as seguintes ferramentas instaladas em seu sistema:
- Python 3.x 🐍
- Bibliotecas Python:
  - `paramiko` - Cliente SSH.
  - `colorama` - Para cores no terminal.

Instale as dependências com:
```bash
pip install paramiko colorama
```

---

## 🚀 **Como Usar**
1. Clone o repositório:
   ```bash
   git clone https://github.com/SeuUsuario/SSH-BruteForce-Enumerator.git
   cd SSH-BruteForce-Enumerator
   ```

2. Execute o script:
   ```bash
   python3 bfssh.py
   ```

3. Forneça as informações solicitadas:
   - **IP do servidor SSH** (ex: `192.168.0.1`)
   - **Caminho do arquivo de usuários** (ex: `users.txt`)
   - **Caminho da chave privada** (ex: `/home/user/id_rsa`)

4. ⚡ Acompanhe os testes de autenticação diretamente no terminal.

---

## 📖 **Exemplo de Uso**
```bash
$ python3 bfssh.py

███████╗███████╗██╗  ██╗    ████████╗ ██████╗  ██████╗ ██╗     
██╔════╝██╔════╝██║  ██║    ╚══██╔══╝██╔═══██╗██╔═══██╗██║     
███████╗███████╗███████║       ██║   ██║   ██║██║   ██║██║     
╚════██║╚════██║██╔══██║       ██║   ██║   ██║██║   ██║██║     
███████║███████║██║  ██║       ██║   ╚██████╔╝╚██████╔╝███████╗
╚══════╝╚══════╝╚═╝  ╚═╝       ╚═╝    ╚═════╝  ╚═════╝ ╚══════╝

[*] SSH Login Enumerator - Brute Force com ID_RSA!

Digite o IP do servidor SSH: 192.168.0.1
Digite o arquivo com a lista de usuários: users.txt
Digite o caminho da chave privada (id_rsa): /home/user/.ssh/id_rsa

[*] 10 usuários carregados para teste...

Tentando usuário (1/10): admin...
[-] admin: Autenticação falhou.
Tentando usuário (2/10): root...
[+] Sucesso! Usuário válido: root
[!] Resultado salvo em: root_id_rsa
```

---

## 📂 **Estrutura do Projeto**
```plaintext
.
├── bfssh.py          # Script principal
├── users.txt         # Exemplo de arquivo de lista de usuários
├── README.md         # Documentação
```

---

## 🛡️ **Aviso Legal**
Este projeto é destinado **exclusivamente para fins educacionais** e práticas éticas. O uso em sistemas não autorizados é **estritamente proibido** e pode violar leis locais ou internacionais. 🚨

---

## 💡 **Contribuição**
Contribuições são sempre bem-vindas!  
1. Faça um fork do projeto.
2. Crie sua branch (`git checkout -b feature/AmazingFeature`).
3. Faça um commit (`git commit -m 'Adicionei uma nova feature'`).
4. Envie um push para a branch (`git push origin feature/AmazingFeature`).
5. Abra um Pull Request.

---
