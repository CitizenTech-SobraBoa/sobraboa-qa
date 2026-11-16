# SobraBoa — QA · Global Solution 2026/2

Repositório de evidências de **Compliance, Quality Assurance & Tests** do projeto SobraBoa, desenvolvido para a Global Solution 2026/2 da FIAP — tema CitizenTech.

---

## Sobre o Projeto

O **SobraBoa** é uma plataforma de redistribuição de excedentes alimentares que conecta doadores (comércios e restaurantes), receptores (ONGs e cozinhas comunitárias) e voluntários, reduzindo o desperdício de alimentos e promovendo segurança alimentar.

**Stack:** Spring Boot (Java) · PostgreSQL · React Native

---

## Equipe

| Nome | RM |
|---|---|
| Felipe Kirschner Modesto | RM561810 |
| João Victor Luiz de Oliveira Resende | RM565139 |
| Pedro Vaz Ferreira | RM566551 |
| Vitor Dias dos Santos | RM565422 |

---

## Plano de Testes

### Azure DevOps

- **Organização:** https://dev.azure.com/RM561810/
- **Projeto:** https://dev.azure.com/RM561810/SobraBoa%20-%20%20CitizenTech%20(Fiap%20-%20GS2)

O backlog e os casos de teste estão estruturados no Azure DevOps seguindo a hierarquia:

```
Epic
└── Feature (F01 – F12)
    └── Product Backlog Item
        └── Test Case (27 TCs no total)
```

### Features cobertas

| Feature | Descrição | TCs |
|---|---|---|
| F01 | Autenticação e Cadastro de Usuários | 3 |
| F02 | Gestão de Doações | 3 |
| F03 | Reserva de Doação | 2 |
| F04 | Confirmação de Retirada | 2 |
| F05 | Notificações | 2 |
| F06 | Busca por Localização | 2 |
| F07 | Histórico de Doações | 2 |
| F08 | Categorias | 2 |
| F09 | Panel de Autenticação Mobile | 3 |
| F10 | Panel Administration | 2 |
| F11 | Composição de Doação | 2 |
| F12 | Fluxo Completo de Doação | 2 |
| **Total** | | **27** |

---

## Documentação

O arquivo [`SobraBoa-PlanoTestes-GS2026.pdf`](./docs/SobraBoa-PlanoTestes-GS2026.pdf) contém:

1. **Backlog do Projeto** — Epics, Features e PBIs no Azure DevOps
2. **Descrição e Critério de Aceite das Features** — F01 a F12
3. **Plano de Testes** — Árvore de Test Cases por Feature
4. **Steps dos Test Cases** — Action e Expected Result de todos os 27 TCs

---

## Informações Acadêmicas

- **Instituição:** FIAP
- **Curso:** Análise e Desenvolvimento de Sistemas
- **Semestre:** 3º — 2026
- **Disciplina:** Compliance, Quality Assurance & Tests
- **Entrega:** Global Solution 2026/2
