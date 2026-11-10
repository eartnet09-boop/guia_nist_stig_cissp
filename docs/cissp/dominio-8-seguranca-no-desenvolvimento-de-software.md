# Domínio 8 — Segurança no Desenvolvimento de Software — 10%

## O que é

O Domínio 8 da certificação Profissional Certificado em Segurança de Sistemas de Informação (Certified Information Systems Security Professional, CISSP), do Consórcio Internacional de Certificação de Segurança de Sistemas de Informação (International Information System Security Certification Consortium, ISC2), integra segurança ao ciclo de vida do software. O objetivo é reduzir falhas desde requisitos e desenho até testes, implantação e manutenção, incluindo dependências.

## Por que importa

Falhas de segurança são mais difíceis de corrigir depois que o software está implantado e em uso. Integrar requisitos e validações ao desenvolvimento reduz retrabalho e ajuda a evitar que vulnerabilidades cheguem às pessoas usuárias.

## Para quem serve

Serve a desenvolvedores, arquitetos, equipes de qualidade e segurança, gestores de produto e candidatos à CISSP. Mesmo quem não programa precisa entender como requisitos, fornecedores e mudanças afetam o risco do software.

## Conceitos-chave

### Tópicos do outline oficial, em síntese

- Ciclo de vida de desenvolvimento e modelos de processo.
- Requisitos de segurança, privacidade e arquitetura de software.
- Práticas seguras de projeto, codificação e revisão.
- Testes de segurança e integração no processo de entrega.
- Gestão de mudanças, configuração, componentes e dependências.
- Aquisição, manutenção e segurança de software terceirizado.

### Conceitos essenciais

Segurança no ciclo de vida começa com requisitos verificáveis e modelagem de ameaças, continua com padrões de codificação e revisão, e é validada por testes proporcionais ao risco. Análise estática examina código sem executá-lo; análise dinâmica observa o programa em execução; revisão manual pode encontrar contexto que ferramentas não reconhecem. Nenhuma técnica é suficiente sozinha.

Dependências de terceiros, pipelines de build, segredos e artefatos também fazem parte da superfície de risco. Gestão de mudanças exige revisão, teste e aprovação compatíveis com o impacto. Corrigir vulnerabilidades não encerra o trabalho: atualizações, monitoramento e suporte ao software mantêm a segurança após a implantação.

## Como usar na prática

1. Identifique dados, usuários, ameaças e requisitos de segurança e privacidade.
2. Converta requisitos em critérios verificáveis e inclua-os no desenho e no processo de desenvolvimento.
3. Revise código, dependências, configurações e pipeline com métodos proporcionais ao risco.
4. Antes da liberação, valide resultados e estabeleça processo de atualização e correção.

### Dicas de estudo

- Associe atividades de segurança às fases do ciclo de vida e antecipe controles para evitar retrabalho.
- Diferencie análise estática, dinâmica, revisão de código e teste de penetração.
- Em cenários de desenvolvimento, avalie requisitos, dependências, pipeline, validação e manutenção, não só a codificação.

## Como pesquisar na fonte oficial

Na página da ISC2, abra o **CISSP Exam Outline** oficial e confirme sua versão e data de vigência. Consulte **Domain 8** para revisar os objetivos cobrados. A mesma página direciona para recursos oficiais de preparação. Para controles, consulte o Instituto Nacional de Padrões e Tecnologia dos Estados Unidos (National Institute of Standards and Technology, NIST), acesse o Centro de Recursos de Segurança de Computadores (Computer Security Resource Center, CSRC) e pesquise a Publicação Especial (Special Publication, SP) 800-53, Revisão (Revision, Rev.) 5.

## Erros comuns / armadilhas

- Achar que testes no fim do projeto compensam requisitos ausentes e desenho inseguro.
- Depender de uma única ferramenta para encontrar todas as classes de falha.
- Ignorar bibliotecas, serviços, segredos e processos de build como parte do software.

## Links oficiais

- [ISC2 CISSP](https://www.isc2.org/certifications/cissp) — página da certificação, outline e recursos de estudo.
- [NIST SP 800-53 Rev. 5](../nist/sp-800-53.md) — catálogo de controles aplicáveis a desenvolvimento e aquisição.
- Anterior: [Domínio 7 — Operações de Segurança](dominio-7-operacoes-de-seguranca.md); reinicie: [Domínio 1 — Segurança e Gestão de Riscos](dominio-1-seguranca-e-gestao-de-riscos.md)

## Exercício rápido

1. Escolha um requisito de segurança para um formulário de cadastro e descreva como verificá-lo antes da liberação.
2. Cite dois riscos de uma biblioteca de terceiros e uma forma de acompanhá-los.