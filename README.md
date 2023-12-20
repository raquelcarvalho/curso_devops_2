## CI - continuous integration
Integração continua: executar testes automatizados, criação de rotina de integração contínua e estratégias para rodar esses testes em vários ambientes distintos. Utilizando GitHub Actions uma ferramenta de CI e CD.

### Projeto
Vamos utilizar o projeto ci-project para entendermos sobre ci.

Primeiramente vamo subir a base de dados:

```bash
ansible-playbook playbook.yml -u ubuntu --private-key conect_instacias_aws.pem -i hosts.yml
```
