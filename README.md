# 🚀 BoraUp - Segunda Etapa do Processo Seletivo

Parabéns! 🎉  
Você foi aprovado(a) para a **segunda etapa** do nosso processo seletivo.  
Agora vamos para o teste prático! 💻

## 📌 Desafio
Crie uma **tela de login** com os seguintes requisitos:

1. **Login** com botão de acesso.
2. Após o login, exibir uma **tela mostrando os dados do usuário**. (nome, email e phone)
3. Essa tela deve **atualizar os dados a cada 5 segundos**.
4. Utilizar **`refreshToken`** para renovar o **`accessToken`** automaticamente quando ele expirar.
5. Considere que a validade é informada na resposta do **`accessToken`** JWT.

---

## 🛠 Tecnologias
* Utilize **react native** para realizar o desenvolvimento.
* Organização do código será um diferencial.

---

## 📑 Documentação
* A api que você usará para fazer as requisições é: `https://api-dev.boraup.com.br`
* Para o login, você precisa enviar um POST para o endpoint `/auth/login` com o body:
```
{
  "email": "string",
  "password": "string"
}
```
* para renovar o `accessToken` basta enviar um POST para o endpoint `/auth/sessions/refresh-token` com o body:
```
{
  "refreshToken": "string"
}
```
response das duas requisições:
```
{
    "accessToken": "string",
    "refreshToken": "string"
}
```

---

## 📤 Entrega
* Envie o link do repositório **GitHub** (ou qualquer outro) com o código e instruções para rodar o projeto.
* Prazo de entrega: **24/08/2025** até 23h59.
* Tempo de execução previsto: 2 horas.
---

💡 Boa sorte! Estamos ansiosos para ver sua solução.  
_Time **BoraUp**_
