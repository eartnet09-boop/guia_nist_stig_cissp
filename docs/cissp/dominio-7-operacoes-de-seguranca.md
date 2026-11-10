# Domínio 7 — Operações de Segurança — 13%

## O que é

O Domínio 7 da certificação Profissional Certificado em Segurança de Sistemas de Informação (Certified Information Systems Security Professional, CISSP), do Consórcio Internacional de Certificação de Segurança de Sistemas de Informação (International Information System Security Certification Consortium, ISC2), cobre atividades contínuas que mantêm controles eficazes e permitem responder a eventos. Inclui incidentes, continuidade, monitoramento, mudanças e operação segura.

## Por que importa

Incidentes e falhas acontecem mesmo com controles preventivos. Operações consistentes ajudam a detectar problemas, conter impactos, preservar evidências e restaurar serviços com previsibilidade.

## Para quem serve

Serve a equipes de operações, resposta a incidentes, continuidade, administradores, gestores e candidatos à CISSP. É útil para quem precisa manter serviços seguros no dia a dia.

## Conceitos-chave

### Tópicos do outline oficial, em síntese

- Investigação, resposta a incidentes e tratamento de evidências.
- Registro, monitoramento, detecção e prevenção de ameaças.
- Gestão de configuração, mudanças, vulnerabilidades e patches.
- Recuperação de desastres e continuidade de negócios.
- Operação de controles, segurança física e gestão de instalações.
- Proteção de dados operacionais, backup e descarte seguro.

### Conceitos essenciais

Um processo de resposta a incidentes prepara a organização, detecta e analisa eventos, contém impactos, erradica causas, recupera serviços e registra lições aprendidas. A cadeia de custódia documenta quem coletou, manuseou e transferiu uma evidência e em que condições, preservando sua integridade e rastreabilidade.

Uma cópia de segurança (backup) é uma cópia recuperável; continuidade mantém processos prioritários; recuperação de desastres restaura tecnologia e serviços após interrupção. O objetivo de tempo de recuperação (Recovery Time Objective, RTO) define o prazo-alvo para retomada; o objetivo de ponto de recuperação (Recovery Point Objective, RPO) define a perda de dados tolerável, expressa em tempo. Esses objetivos orientam planejamento e testes. Registros precisam de proteção, sincronização temporal, retenção e revisão útil.

## Como usar na prática

1. Identifique serviços prioritários, responsáveis e dependências.
2. Defina metas de recuperação e mantenha planos para incidentes e interrupções.
3. Colete e proteja registros e evidências; documente ações e decisões.
4. Teste restauração e resposta, registre falhas e atualize os planos.

### Dicas de estudo

- Em incidentes, preserve evidências e contenha o dano conforme o plano e a autoridade definida.
- Diferencie alta disponibilidade, backup, continuidade e recuperação de desastres.
- Para controles operacionais, considere pessoas, processo, tecnologia, registros e revisão periódica.

## Como pesquisar na fonte oficial

Na página da ISC2, abra **CISSP Exam Outline**, confirme a versão vigente e localize **Domain 7**. Consulte o peso e os objetivos publicados, depois procure os materiais oficiais na seção de preparação para o exame. Para controles, consulte o Instituto Nacional de Padrões e Tecnologia dos Estados Unidos (National Institute of Standards and Technology, NIST), acesse o Centro de Recursos de Segurança de Computadores (Computer Security Resource Center, CSRC) e pesquise a Publicação Especial (Special Publication, SP) 800-53, Revisão (Revision, Rev.) 5. Para orientação de resposta a incidentes, consulte publicações oficiais do NIST relacionadas.

## Erros comuns / armadilhas

- Confundir cópias de segurança com um plano completo de continuidade ou recuperação.
- Considerar registros úteis sem proteger sua integridade, acesso e sincronização temporal.
- Retomar sistemas antes de confirmar integridade e entender o alcance do incidente.

## Links oficiais

- [ISC2 CISSP](https://www.isc2.org/certifications/cissp) — página da certificação, outline e recursos de estudo.
- [NIST SP 800-53 Rev. 5](../nist/sp-800-53.md) — catálogo de controles de resposta, contingência e monitoramento.
- [Visão geral dos DISA STIGs](../stig/visao-geral.md) — guia de avaliação técnica de configurações.
- Anterior: [Domínio 6 — Avaliação e Testes](dominio-6-avaliacao-e-testes-de-seguranca.md); próximo: [Domínio 8 — Segurança no Desenvolvimento de Software](dominio-8-seguranca-no-desenvolvimento-de-software.md)

## Exercício rápido

1. Um serviço precisa voltar em até quatro horas e pode perder no máximo quinze minutos de dados. Quais são suas metas de RTO e RPO?
2. Por que uma restauração deve ser testada, e não apenas presumida a partir da existência de cópias?