#### Cenário: Realizar login com usuário cadastrado

### 1 - Obtém token de acesso
```javascript
Request: {
    method: POST.
    URL: "{{API_BASE_AUTH_URL}}/token"
}
```

```javascript
response: {
    "access_token": "W1jWZ5irQ4G3sBpvDuD-dsGMj5E",
    "token_type": "bearer",
}
```

Respose:
Status code: 200  
{
"access_token": "W1jWZ5irQ4G3sBpvDuD-dsGMj5E",
"token_type": "bearer",
"refresh_token": "e_Fk-VjdVmsVcQ3mSP8-QBYTUOw",
"expires_in": 43199,
"scope": "basic"A
}

### 2 - Obtém dados do usuário

Request:
Method: GET.
URL: ,
body: {

}

Respose:
Status code: 200  
{

}
