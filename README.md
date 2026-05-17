# Labymod-bypass
Этот bypass позволит вам играть на LabyMod 4 через оригинальный лаунчер не имея лицении.

# Использование
Данный файл закидываете по пути `%appdata%\.minecraft\labymod-neo`

Также перекидываете/создаете файл с названием `accounts.json` преждевременно написав свой игровой ник в строке `"username": "YOUR_NICKNAME",`.

После перезапускаете лаунчер и радуетесь жизни!

## Текст для **accounts.json**
```json
{
  "accounts": {
    "80794e46-3f87-44b5-8ab4-0a2ff049459b": {
      "tokens": {
        "microsoft": {
          "token": null,
          "expires_at": 0,
          "additional_data": {}
        },
        "xbl": {
          "token": null,
          "expires_at": 0,
          "additional_data": {}
        },
        "xsts": {
          "token": null,
          "expires_at": 0,
          "additional_data": {}
        },
        "azure": null
      },
      "uuid": "80794e46-3f87-44b5-8ab4-0a2ff049459b",
      "username": "YOUR_NICKNAME",
      "access_token": "cAIco172Ypo=",
      "access_token_expires_at": 0
    }
  },
  "client_token": "a54927d2b8414c1dafe80030d0bc826d",
  "encrypted": true,
  "version": 1
}
```
