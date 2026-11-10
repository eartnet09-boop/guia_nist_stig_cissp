# Domínio 6 — Avaliação e Testes de Segurança — 12%

## O que é

O Domínio 6 da certificação Profissional Certificado em Segurança de Sistemas de Informação (Certified Information Systems Security Professional, CISSP), do Consórcio Internacional de Certificação de Segurança de Sistemas de Informação (International Information System Security Certification Consortium, ISC2), trata de verificar se controles foram projetados e operam conforme esperado. Avaliações fornecem evidências para decisões de risco e melhoria, desde que autorizadas e bem delimitadas.

## Por que importa

Controles podem falhar, estar mal configurados ou deixar de acompanhar mudanças. Testes e avaliações revelam evidências úteis para priorizar correções, mas seus resultados sempre dependem do escopo e do método utilizado.

## Para quem serve

Serve a avaliadores, auditores, profissionais de segurança, responsáveis por controles e candidatos à CISSP. Também ajuda gestores a interpretar resultados e decidir sobre riscos e correções.

## Conceitos-chave

### Tópicos do outline oficial, em síntese

- Estratégias de teste, avaliação e auditoria de segurança.
- Revisão de controles, processos, configurações e evidências.
- Testes de vulnerabilidade e de segurança autorizados.
- Análise e comunicação de resultados e recomendações.
- Métricas e monitoramento da eficácia dos controles.

### Conceitos essenciais

Uma **avaliação** compara evidências a critérios definidos; uma **auditoria** pode exigir independência e procedimentos formais; um teste técnico busca observar comportamentos específicos. Revisão de configuração, análise de código, varredura de vulnerabilidades e teste de penetração têm escopos e limitações distintos. Nenhum resultado isolado prova ausência de vulnerabilidades.

Antes de testar, defina autorização, escopo, regras de engajamento, janelas, tratamento de dados e plano de comunicação. Os achados devem descrever evidência, impacto, prioridade e ação recomendada. Uma retestagem verifica se a correção resolveu o problema sem introduzir regressões.

## Como usar na prática

1. Obtenha autorização e defina escopo, regras de engajamento, janelas e responsáveis.
2. Escolha um método adequado à pergunta e aos critérios de avaliação.
3. Registre evidências, limitações, impacto e prioridade dos achados.
4. Apresente recomendações e valide as correções com reteste proporcional ao risco.

### Dicas de estudo

- Diferencie teste de controle, teste de vulnerabilidade e auditoria pelo objetivo e pela evidência produzida.
- Confirme autorização e escopo antes de qualquer atividade técnica.
- Prefira resultados reproduzíveis e contextualizados a métricas sem explicação, como uma contagem bruta de achados.

## Como pesquisar na fonte oficial

Na página da ISC2, localize o **CISSP Exam Outline** vigente e confira a data de publicação ou entrada em vigor. Consulte **Domain 6** para verificar os objetivos de avaliação e testes. Na mesma página, procure a área de preparação para o exame e os recursos oficiais disponíveis. Para controles, consulte o Instituto Nacional de Padrões e Tecnologia dos Estados Unidos (National Institute of Standards and Technology, NIST), acesse o Centro de Recursos de Segurança de Computadores (Computer Security Resource Center, CSRC) e pesquise a Publicação Especial (Special Publication, SP) 800-53, Revisão (Revision, Rev.) 5.

## Erros comuns / armadilhas

- Tratar uma varredura automatizada como auditoria completa ou como prova de ausência de vulnerabilidades.
- Testar sistemas sem autorização explícita e escopo documentado.
- Reportar achados sem contexto, evidência, limitação ou recomendação verificável.

## Links oficiais

- [ISC2 CISSP](https://www.isc2.org/certifications/cissp) — página da certificação, outline e preparação oficial.
- [NIST SP 800-53 Rev. 5](../nist/sp-800-53.md) — catálogo que inclui controles de avaliação e monitoramento.
- Anterior: [Domínio 5 — Gestão de Identidade e Acesso](dominio-5-gestao-de-identidade-e-acesso.md); próximo: [Domínio 7 — Operações de Segurança](dominio-7-operacoes-de-seguranca.md)

## Exercício rápido

1. Explique por que um teste de penetração com escopo limitado não prova que todo o ambiente está seguro.
2. Liste três elementos que devem constar na autorização e no escopo de uma avaliação.