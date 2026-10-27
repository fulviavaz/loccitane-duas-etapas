# LP L'Occitane — cadastro em duas etapas

Versão separada da landing de revenda. A primeira etapa envia à Gera só nome, e-mail, CPF, WhatsApp e CEP (`POST /api/lider`). Completar o cadastro usa OTP + `POST /api/cadastro`.

## Local

```bash
cd api
npm install
npm start
```

Abra http://localhost:3000 — não abra o `index.html` direto no arquivo.

Copie `api/.env.example` para `api/.env` com as mesmas credenciais da LP original (Gera, Indico, Dinamize, reCAPTCHA).
