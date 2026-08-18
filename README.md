# GestaoEPI V2

Versao historica de um sistema web para gestao de EPIs, colaboradores, estoque, entregas e rastreabilidade operacional.

## Visao geral

O GestaoEPI V2 evolui a base inicial do sistema com modulos administrativos, historico de entregas, controle de perfis e melhorias no fluxo de acompanhamento de EPIs. O projeto combina frontend React, backend FastAPI e MongoDB.

Este repositorio deve ser entendido como uma etapa intermediaria da familia GestaoEPI, anterior as versoes V3, V4 e 5.x.

## Problema resolvido

O controle de EPIs exige visibilidade sobre colaboradores, equipamentos, fornecedores, kits, estoque, validade e entregas. Esta versao busca concentrar esse fluxo em uma plataforma web para reduzir registros dispersos e apoiar auditoria operacional.

## Publico e contexto de uso

- Times de seguranca do trabalho.
- Almoxarifado e responsaveis por entrega de materiais.
- Gestores que acompanham indicadores e historico de uso.

## Principais funcionalidades confirmadas

- Login com autenticacao.
- Dashboard e navegacao por modulos.
- Cadastro de colaboradores, empresas, fornecedores, EPIs e ferramentas.
- Gestao de kits de EPIs.
- Controle de estoque e alertas.
- Historico de entregas.
- Perfis de acesso identificados no codigo.
- Recursos de QR Code e reconhecimento facial identificados nas dependencias e telas.
- Testes backend para kits, EPIs e templates faciais.

## Como funciona

O frontend React oferece a interface operacional e consome endpoints do backend FastAPI. O backend concentra regras de autenticacao, persistencia em MongoDB, cadastros, estoque, entregas e consultas utilizadas pelo dashboard.

## Tecnologias utilizadas

- Python
- FastAPI
- MongoDB
- React
- JavaScript
- Tailwind CSS
- face-api.js
- html5-qrcode
- qrcode
- ReportLab
- OpenPyXL

## Arquitetura resumida

- `backend/`: API, autenticacao, banco, schemas, seed e testes.
- `frontend/`: interface React, paginas, componentes, layout e modelos de reconhecimento facial.
- `test_reports/`: resultados historicos de testes.
- `memory/`: registro historico de produto e evolucao.

## Status

Versao historica/intermediaria. O repositorio documenta uma fase anterior do GestaoEPI e nao deve substituir as versoes mais recentes no portfolio principal.

## Relacao com outras versoes

Esta versao sucede `GestaoEPI` e antecede `GestaoEPI-v3`, `GestaoEPI-V4` e a linha 5.x. A evolucao identificada inclui historico de entregas e amadurecimento dos fluxos de permissao e rastreabilidade.

## Limitacoes conhecidas

- O repositorio contem artefatos operacionais antigos que exigem revisao antes de destaque publico.
- Uso em producao nao foi confirmado.
- Como versao antiga, pode conter decisoes tecnicas superadas por releases posteriores.

## Participacao no desenvolvimento

O projeto demonstra experiencia em desenvolvimento full stack, regras de negocio para controle de EPIs, integracao de leitura/identificacao, organizacao de dashboards e evolucao incremental de sistemas empresariais.

## Autoria

Desenvolvido por Alexandre Santana dos Santos — Kalion Tecnologia
