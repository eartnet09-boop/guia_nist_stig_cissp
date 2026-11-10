# Guia de Estudos: NIST, STIG e CISSP

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)](#)
[![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue)](LICENSE)
[![Versão do conteúdo](https://img.shields.io/badge/conte%C3%BAdo-1.0.0-informational)](#)

Material de referência em português para estudar estruturas, controles técnicos e práticas de segurança da informação. Use os guias como mapas de estudo e confirme requisitos e versões nas fontes oficiais antes de aplicá-los.

## Sumário

- [Visão geral](#vis%C3%A3o-geral)
- [Como navegar](#como-navegar)
- [Documentos de apoio](#documentos-de-apoio)
- [Guias de estudo](#guias-de-estudo)
- [Fontes oficiais](#fontes-oficiais)
- [Licença e citação](#licen%C3%A7a-e-cita%C3%A7%C3%A3o)
- [Contribuição](#contribui%C3%A7%C3%A3o)

## Visão geral

O Instituto Nacional de Padrões e Tecnologia dos Estados Unidos (National Institute of Standards and Technology, NIST) publica estruturas e padrões para ajudar organizações a gerir riscos de segurança e privacidade. O Cybersecurity Framework (CSF), ou Estrutura de Cibersegurança, 2.0 organiza resultados de alto nível em seis funções; a Publicação Especial (Special Publication, SP) 800-53 reúne controles que podem ser selecionados e adaptados ao contexto de cada sistema.

Os Guias de Implementação Técnica de Segurança (Security Technical Implementation Guides, STIGs) são publicados pela Agência de Sistemas de Informação de Defesa (Defense Information Systems Agency, DISA) e traduzem requisitos em verificações e orientações de configuração para tecnologias específicas. São úteis para orientar o fortalecimento de configurações e avaliações, mas precisam ser aplicados considerando missão, ambiente e versão do produto.

A certificação Profissional Certificado em Segurança de Sistemas de Informação (Certified Information Systems Security Professional, CISSP), do Consórcio Internacional de Certificação de Segurança de Sistemas de Informação (International Information System Security Certification Consortium, ISC2), cobre oito domínios amplos. Estudar o framework, controles e guias técnicos em conjunto ajuda a conectar governança e risco, requisitos e implementação; este repositório não substitui normas, documentação do fabricante nem o outline oficial do exame.

## Como navegar

Comece por esta página e siga a [trilha de estudos](docs/trilha-de-estudos.md), iniciando pelo [glossário](docs/glossario.md). A pasta `docs/` contém os guias; cada domínio CISSP aponta para o próximo. Os percentuais apresentados correspondem ao outline vigente a partir de 15 de abril de 2024; confira a versão atual antes de planejar a prova.

## Documentos de apoio

- [Glossário de siglas](docs/glossario.md) — expansões, explicações breves e links para os guias.
- [Trilha de estudos](docs/trilha-de-estudos.md) — ordem de leitura para iniciantes com tempo estimado por etapa.

### NIST

- [CSF 2.0](docs/nist/csf-2.0.md)
- [SP 800-53 Rev. 5](docs/nist/sp-800-53.md)

### DISA STIGs

- [Visão geral](docs/stig/visao-geral.md)

### CISSP

- [Domínio 1 — Segurança e Gestão de Riscos](docs/cissp/dominio-1-seguranca-e-gestao-de-riscos.md)
- [Domínio 2 — Segurança de Ativos](docs/cissp/dominio-2-seguranca-de-ativos.md)
- [Domínio 3 — Arquitetura e Engenharia de Segurança](docs/cissp/dominio-3-arquitetura-e-engenharia-de-seguranca.md)
- [Domínio 4 — Segurança de Comunicação e Redes](docs/cissp/dominio-4-seguranca-de-comunicacao-e-redes.md)
- [Domínio 5 — Gestão de Identidade e Acesso](docs/cissp/dominio-5-gestao-de-identidade-e-acesso.md)
- [Domínio 6 — Avaliação e Testes de Segurança](docs/cissp/dominio-6-avaliacao-e-testes-de-seguranca.md)
- [Domínio 7 — Operações de Segurança](docs/cissp/dominio-7-operacoes-de-seguranca.md)
- [Domínio 8 — Segurança no Desenvolvimento de Software](docs/cissp/dominio-8-seguranca-no-desenvolvimento-de-software.md)

## Fontes oficiais

- [NIST CSF 2.0](https://www.nist.gov/cyberframework)
- [NIST SP 800-53 Rev. 5, Update 1](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
- [DISA STIGs](https://public.cyber.mil/stigs/)
- [ISC2 CISSP e informações do exame](https://www.isc2.org/certifications/cissp)

## Licença e citação

O material original deste repositório é distribuído sob a [Licença MIT](LICENSE). As normas, marcas e documentos de terceiros permanecem sujeitos aos respectivos termos; links e referências não significam endosso. Para citar este material, indique: **Guia de Estudos: NIST, STIG e CISSP**, versão 1.0.0, URL deste repositório e data de acesso. Ao reutilizar conteúdo, mantenha o aviso de licença e identifique alterações.

## Contribuição

Leia [CONTRIBUTING.md](CONTRIBUTING.md) antes de propor correções ou novos guias. Sugestões de atualização devem incluir a fonte primária e a versão/data consultada.