# Automação de API Carrefour

## Objetivo
Projeto de automação de testes de API utilizando Postman, Newman e GitHub Actions.

## Tecnologias
- Postman
- Newman
- GitHub Actions
- GitHub

## Estrutura do projeto

.github/workflows/
collections/
environments/
evidence/
README.md

## Como executar

1. Importe a Collection no Postman.
2. Importe o Environment.
3. Execute a Collection Runner.

## Integração Contínua (CI)

Os testes são executados automaticamente pelo GitHub Actions a cada push na branch main.

## Evidências

### Execução da Collection

![Collection](evidence/postman-run.png)

### GitHub Actions

![GitHub Actions](evidence/github-actions-success.png)
