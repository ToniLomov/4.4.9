Регистрация

Запрос:

{ "user": 
    { "username": "antonlomov", 
    "email": "toni.lomov@gmail.com", 
    "password": "123"} 
    }

Ответ:
{
    "user": {
        "username": "antonlomov",
        "email": "toni.lomov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0NDAzNjlkNjBjNjc1MWIwMGI3NjhjMiIsInVzZXJuYW1lIjoiYW50b25sb21vdiIsImV4cCI6MTY4NzExMzg4NSwiaWF0IjoxNjgxOTI5ODg1fQ.ThVt27maE-S0080i0sOptqrIp5Kb1NXco68meKBPNMo"
    }
}

Вход

Запрос:

{ "user": 
    {
    "email": "toni.lomov@gmail.com", 
    "password": "123"} 
    }

Ответ:

{
    "user": {
        "username": "antonlomov",
        "email": "toni.lomov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0NDAzNjlkNjBjNjc1MWIwMGI3NjhjMiIsInVzZXJuYW1lIjoiYW50b25sb21vdiIsImV4cCI6MTY4NzExNjQ3NCwiaWF0IjoxNjgxOTMyNDc0fQ.5Z2HAMf3-9ZTfK_tO8fs7cCZzMSYNBvZwTEd8nVpbQc"
    }
}

Получение пользователя

Запрос:

В Authorization вписал токен

Ответ:

{
    "user": {
        "username": "antonlomov",
        "email": "toni.lomov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0NDAzNjlkNjBjNjc1MWIwMGI3NjhjMiIsInVzZXJuYW1lIjoiYW50b25sb21vdiIsImV4cCI6MTY4NzExNjk4MiwiaWF0IjoxNjgxOTMyOTgyfQ.sRAK1668CAMHT68kic-41qBk9uaZPAaDjglj1v-tpUA"
    }
}
