# Projeto Retirada Escolar

---

Este projeto tem como objetivo organizar e facilitar o processo de retirada escolar, proporcionando uma visão clara e estruturada sobre a rotina de alunos, responsáveis e acompanhamento escolar.

A proposta central é melhorar a gestão das saídas e entradas dos estudantes, tornando o processo mais seguro, eficiente e transparente.

## Objetivos

- Centralizar informações relacionadas à retirada escolar;
- Facilitar o acompanhamento de alunos e responsáveis;
- Reduzir falhas no processo de autorização e controle;
- Melhorar a comunicação entre escola e família;
- Organizar o fluxo de informações de forma simples e legível.

## Fluxo do Processo

```mermaid
flowchart TD
    A[Responsável] --> B[Solicita retirada]
    B --> C[Escola valida autorização]
    C --> D{Autorizado?}
    D -- Sim --> E[Aluno liberado]
    D -- Não --> F[Solicitação negada]
    E --> G[Registro finalizado]
    F --> H[Contato com responsável]
```
