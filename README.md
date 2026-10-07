# op7-proposta-odontologica

Landing page OP7 exportada da VPS cypher em 07/10/2026.

- **Domínio:** propostacomercial.op7franquia.com.br
- **Como roda:** nginx estático + nginx.conf (Dockerfile), porta 80
- **Subir:** `docker build -t op7-proposta-odontologica .` e `docker run -d -p <porta>:<porta da linha acima> op7-proposta-odontologica`
- **Atenção:** Depende da API op7-proposta-comercial-api (o nginx.conf encaminha pra ela).
