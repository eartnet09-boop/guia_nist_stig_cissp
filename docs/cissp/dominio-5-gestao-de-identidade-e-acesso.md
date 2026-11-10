# Domínio 5 — Gestão de Identidade e Acesso — 13%

## O que é

O Domínio 5 da certificação Profissional Certificado em Segurança de Sistemas de Informação (Certified Information Systems Security Professional, CISSP), do Consórcio Internacional de Certificação de Segurança de Sistemas de Informação (International Information System Security Certification Consortium, ISC2), cobre gestão de identidade e acesso (Identity and Access Management, IAM): quem ou o que pode acessar recursos, em quais condições e com quais permissões.

## Por que importa

Identidades comprometidas ou permissões excessivas podem expor dados e sistemas. Uma gestão adequada permite conceder o acesso necessário, revisar mudanças de função e revogar credenciais quando deixam de ser necessárias.

## Para quem serve

Serve a administradores, equipes de identidade, arquitetos, auditores, gestores e candidatos à CISSP. O tema também é útil a qualquer profissional que aprove ou use acessos a sistemas.

## Conceitos-chave

### Tópicos do outline oficial, em síntese

- Controle de acesso físico e lógico.
- Identidades, credenciais e autenticação de pessoas, dispositivos e serviços.
- Autorização, modelos de controle e princípios de acesso.
- Gestão do ciclo de vida, provisionamento e desprovisionamento.
- Federação, autenticação centralizada e acesso remoto.
- Revisão, monitoramento e auditoria de direitos de acesso.

### Conceitos essenciais

Identificação declara uma identidade; autenticação verifica uma alegação; autorização decide o que ela pode fazer; auditoria registra e permite atribuir ações. Fatores de autenticação podem ser algo que se sabe, possui ou é. A autenticação multifator (Multi-Factor Authentication, MFA) combina fatores distintos; duas senhas continuam sendo um único tipo de fator.

No controle de acesso discricionário (Discretionary Access Control, DAC), o proprietário pode delegar acesso; no controle de acesso obrigatório (Mandatory Access Control, MAC), regras centrais e rótulos governam decisões; no controle de acesso baseado em papéis (Role-Based Access Control, RBAC), permissões se associam a funções; no controle de acesso baseado em atributos (Attribute-Based Access Control, ABAC), atributos e contexto alimentam políticas. Menor privilégio e necessidade de saber reduzem exposição. Provisionar, alterar e revogar acesso no momento certo evita contas órfãs e privilégios acumulados.

## Como usar na prática

1. Identifique a pessoa, dispositivo ou serviço e o recurso solicitado.
2. Defina como a identidade será verificada e quais atributos determinam a decisão.
3. Conceda somente permissões necessárias e vincule-as a uma aprovação responsável.
4. Revise os direitos periodicamente e revogue-os quando a necessidade terminar.

### Dicas de estudo

- Separe autenticação de autorização em todo cenário.
- Para escolher um modelo, observe quem define a política e quais dados/contextos determinam a decisão.
- Inclua contas de serviço, máquinas, interfaces de programação de aplicações (Application Programming Interfaces, APIs) e acesso emergencial no ciclo de vida, não apenas usuários humanos.

## Como pesquisar na fonte oficial

Na página da ISC2, encontre a certificação CISSP e abra **Exam Outline**. Confirme a versão e sua data de vigência; então consulte **Domain 5** para conferir objetivos e peso. Na seção de preparação, procure recursos oficiais de estudo. Para relacionar IAM a controles, acesse o Centro de Recursos de Segurança de Computadores (Computer Security Resource Center, CSRC), do Instituto Nacional de Padrões e Tecnologia dos Estados Unidos (National Institute of Standards and Technology, NIST), e pesquise a Publicação Especial (Special Publication, SP) 800-53, Revisão (Revision, Rev.) 5. Consulte as famílias **AC — Access Control** e **IA — Identification and Authentication**.

## Erros comuns / armadilhas

- Confundir identificação, autenticação, autorização e auditoria.
- Considerar duas senhas como múltiplos fatores; fatores precisam pertencer a categorias distintas.
- Aplicar permissões por função sem revisar exceções, contas de serviço ou mudanças de função.

## Links oficiais

- [ISC2 CISSP](https://www.isc2.org/certifications/cissp) — página da certificação, outline e recursos de estudo.
- [NIST SP 800-53 Rev. 5](../nist/sp-800-53.md) — catálogo com famílias de controle de acesso e autenticação.
- Anterior: [Domínio 4 — Segurança de Comunicação e Redes](dominio-4-seguranca-de-comunicacao-e-redes.md); próximo: [Domínio 6 — Avaliação e Testes de Segurança](dominio-6-avaliacao-e-testes-de-seguranca.md)

## Exercício rápido

1. Escolha um modelo de acesso adequado para uma aplicação que permite regras com base em departamento, horário e local. Justifique.
2. Descreva o que deve ocorrer quando uma pessoa muda de função e deixa a organização.