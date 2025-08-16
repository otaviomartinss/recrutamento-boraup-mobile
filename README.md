# 🚀 BoraUp - Segunda Etapa do Processo Seletivo

Parabéns! 🎉  
Você foi aprovado(a) para a **segunda etapa** do nosso processo seletivo.  
Agora vamos para o teste prático! 💻

## 📌 Desafio
Crie uma **tela de login** com os seguintes requisitos:

1. **Login** com botão de acesso.
2. Após o login, exibir uma **tela mostrando os dados do usuário**. (nome, email e id)
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
* response das duas requisições:
```
{
    "accessToken": "string",
    "refreshToken": "string"
}
```

* Os dados do usuário está disponível no endpoint `/users/me` e o retorno é no seguinte formato:
```
{
    "id": "string",
    "name": "string",
    "email": "string",
    "phone": null,
    "birthday": null,
    "documents": [],
    "verified": false,
    "pixKey": null,
    "address": null,
    "userType": "consumer",
    "createdAt": "2025-08-16T00:00:00.000Z",
    "updatedAt": "2025-08-16T00:00:00.000Z",
    "verifiedEmail": false
}
```

---

## 📤 Entrega
* Envie o link do repositório **GitHub** (ou qualquer outro) com o código e instruções para rodar o projeto.
* Prazo de entrega: **24/08/2025** até 23h59.
* Tempo de execução previsto: 4 horas.
---

💡 Boa sorte! Estamos ansiosos para ver sua solução.  
_Time **BoraUp**_
