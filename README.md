# Desafio-BA


Link Api: https://desafio-ba.onrender.com

Obs: A primeira requisição pode demorar, pois a api fica inativa.

Link Swagger: https://desafio-ba.onrender.com/api#/

## Tests

  Testes unitários: podem ser encontrados na pasta test dentro de cada entidade. O comando para executar é "npm run test"
  
  Testes E2E: Podem ser encontrados na pasta test na raiz do projeto. O comando para executar é "npm run test:e2e"

## Diagrama Banco de Dados:
![image](https://github.com/user-attachments/assets/8c4796b2-4405-44ec-9a46-f23c719c1fa5)


A entidade login foi implementada para a implementação da autenticação JWT, o acesso ao token é pela rota auth/login com o body:

```
{
	"login":"adm",
	"password":"adm"
}
```
Os cpfs e cnpjs foram armazenados no banco encriptados.

Seeds foram criados e podem ser encontrados na pasta prisma.

As variáveis de ambiente necessarias podem ser encontradas no arquivo .env.example
