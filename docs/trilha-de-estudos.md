# Trilha de estudos

## O que é

Esta trilha organiza uma primeira leitura do repositório, do vocabulário fundamental à aplicação de controles e aos domínios da certificação Profissional Certificado em Segurança de Sistemas de Informação (Certified Information Systems Security Professional, CISSP). O percurso completo leva aproximadamente 12 horas, sem contar pausas ou pesquisa adicional.

## Por que importa

Estudar por camadas ajuda a conectar governança, requisitos e implementação técnica. A sequência também dá contexto para os conceitos que voltam a aparecer nos domínios da CISSP.

## Para quem serve

É voltada a iniciantes e estudantes intermediários que querem uma visão estruturada do Instituto Nacional de Padrões e Tecnologia dos Estados Unidos (National Institute of Standards and Technology, NIST), dos Guias de Implementação Técnica de Segurança (Security Technical Implementation Guides, STIGs) e da CISSP. Profissionais podem adaptar a ordem às responsabilidades que exercem.

## Conceitos-chave

O Instituto Nacional de Padrões e Tecnologia dos Estados Unidos (National Institute of Standards and Technology, NIST) publica a Publicação Especial (Special Publication, SP) 800-53, Revisão (Revision, Rev.) 5, usada como referência nesta trilha.

| Etapa | Leitura | Tempo estimado | Objetivo |
|---|---|---:|---|
| 1 | [Glossário](glossario.md) | 20 min | Familiarizar-se com termos e siglas antes dos guias. |
| 2 | [NIST CSF 2.0](nist/csf-2.0.md) | 1 h | Entender funções, perfis, resultados e governança. |
| 3 | [NIST SP 800-53 Rev. 5](nist/sp-800-53.md) | 2 h | Conhecer famílias, controles, privacidade e baselines. |
| 4 | [Visão geral dos DISA STIGs](stig/visao-geral.md) | 1 h | Aprender a localizar e interpretar requisitos técnicos. |
| 5 | Domínios CISSP 1 a 4 | 3 h | Estudar risco, ativos, arquitetura e redes, cerca de 45 min por domínio. |
| 6 | Domínios CISSP 5 a 8 | 3 h | Estudar identidade, avaliação, operações e desenvolvimento, cerca de 45 min por domínio. |
| 7 | Revisão e exercícios | 1 h 40 min | Refazer exercícios, revisar lacunas e consultar fontes primárias. |

A CISSP é a certificação Profissional Certificado em Segurança de Sistemas de Informação (Certified Information Systems Security Professional) do Consórcio Internacional de Certificação de Segurança de Sistemas de Informação (International Information System Security Certification Consortium, ISC2). Os domínios e pesos apresentados refletem o outline vigente a partir de 15 de abril de 2024; confirme a versão atual na página oficial antes de usar este cronograma para a prova.

## Como usar na prática

1. Siga a tabela na ordem sugerida e anote dúvidas em um caderno ou arquivo próprio.
2. Ao final de cada guia, responda ao exercício sem consultar o texto; depois confira sua resposta.
3. Leia os documentos CISSP em sequência: [Domínio 1](cissp/dominio-1-seguranca-e-gestao-de-riscos.md), [Domínio 2](cissp/dominio-2-seguranca-de-ativos.md), [Domínio 3](cissp/dominio-3-arquitetura-e-engenharia-de-seguranca.md), [Domínio 4](cissp/dominio-4-seguranca-de-comunicacao-e-redes.md), [Domínio 5](cissp/dominio-5-gestao-de-identidade-e-acesso.md), [Domínio 6](cissp/dominio-6-avaliacao-e-testes-de-seguranca.md), [Domínio 7](cissp/dominio-7-operacoes-de-seguranca.md) e [Domínio 8](cissp/dominio-8-seguranca-no-desenvolvimento-de-software.md).
4. Ao encontrar um termo desconhecido, use o [glossário](glossario.md) e depois retorne à explicação completa.
5. Feche cada sessão registrando o que consegue explicar e o que precisa revisar.

## Como pesquisar na fonte oficial

- **NIST**: acesse o Centro de Recursos de Segurança de Computadores (Computer Security Resource Center, CSRC) em `csrc.nist.gov`. Pesquise pela Publicação Especial (Special Publication, SP) 800-53, Revisão (Revision, Rev.) 5; confira atualização e revisão. No catálogo, filtre por família ou procure o identificador (Identifier, ID) do controle e leia título, declaração e discussão. Para o framework, use a página do [CSF 2.0](https://www.nist.gov/cyberframework).
- **DISA**: abra o catálogo da Agência de Sistemas de Informação de Defesa (Defense Information Systems Agency, DISA), filtre os Guias de Implementação Técnica de Segurança (Security Technical Implementation Guides, STIGs) pelo produto e versão, e leia as regras e instruções do pacote. O STIG Viewer ajuda a percorrer requisitos compatíveis e registrar resultados; não executa nem comprova sozinho todas as verificações.
- **ISC2**: na página oficial do Consórcio Internacional de Certificação de Segurança de Sistemas de Informação (International Information System Security Certification Consortium, ISC2), procure o **Exam Outline** da [certificação CISSP](https://www.isc2.org/certifications/cissp), verifique sua data e compare os oito domínios e percentuais. Consulte também a área de preparação para localizar os recursos oficiais de estudo.

## Erros comuns / armadilhas

- Memorizar listas de controles sem entender o risco e o resultado que se pretende alcançar.
- Tratar um STIG como configuração universal, sem confirmar versão e impacto operacional.
- Estudar para a prova com percentuais de um outline antigo.
- Confundir estimativa de tempo com garantia de domínio do assunto; ajuste a trilha conforme seus conhecimentos prévios.

## Links oficiais

- [NIST CSF 2.0](https://www.nist.gov/cyberframework) — framework e recursos oficiais.
- [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final) — catálogo de controles.
- [DISA STIGs](https://public.cyber.mil/stigs/) — guias técnicos oficiais.
- [ISC2 CISSP](https://www.isc2.org/certifications/cissp) — página da certificação, outline e preparação.

## Exercício rápido

1. Complete as etapas 1 a 3 e explique como um resultado do CSF pode se relacionar a uma família de controles da SP 800-53.
2. Monte um plano semanal usando o tempo estimado, reservando um período de revisão para os temas mais difíceis.
