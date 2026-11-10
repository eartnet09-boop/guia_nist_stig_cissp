# NIST Cybersecurity Framework 2.0

## O que é

O Instituto Nacional de Padrões e Tecnologia dos Estados Unidos (National Institute of Standards and Technology, NIST) publica o Cybersecurity Framework (CSF), ou Estrutura de Cibersegurança, para ajudar organizações a compreender, priorizar e comunicar riscos. A versão 2.0, publicada em 2024, organiza resultados desejáveis; não prescreve uma tecnologia, uma sequência obrigatória nem uma lista única de controles.

O Núcleo (Core) organiza resultados em funções, categorias e subcategorias. Perfis descrevem resultados atuais e pretendidos em um contexto específico. Os níveis (Tiers) podem caracterizar o rigor das práticas de gestão de risco, do Parcial (1) ao Adaptativo (4); não são uma nota de maturidade universal nem uma certificação por si só.

## Por que importa

O framework oferece uma linguagem comum para que equipes técnicas, gestores e direção conversem sobre resultados e prioridades. Ajuda a identificar lacunas sem obrigar a organização a adotar um produto ou um conjunto fixo de controles.

## Para quem serve

Serve a organizações públicas e privadas, equipes de segurança e risco, auditores, gestores e iniciantes que precisam organizar prioridades de cibersegurança. É adaptável a diferentes portes, desde que os resultados sejam escolhidos conforme o contexto.

## Conceitos-chave

As seis funções são resultados de alto nível que se complementam. **Governar (Govern, GV)** orienta as demais e aparece em posição central no CSF 2.0. **Identificar (Identify, ID)**, **Proteger (Protect, PR)**, **Detectar (Detect, DE)**, **Responder (Respond, RS)** e **Recuperar (Recover, RC)** cobrem o entendimento dos riscos, salvaguardas, detecção, tratamento de incidentes e retomada.

| Função | Finalidade | Exemplo de aplicação |
|---|---|---|
| Governar (GV) | Define estratégia, responsabilidades, políticas, apetite a risco e supervisão. | A direção aprova critérios de risco e revisa riscos de fornecedores. |
| Identificar (ID) | Entende ativos, serviços, contexto, dependências e riscos. | Mantém inventário de sistemas críticos, mapeia dependências e avalia ameaças. |
| Proteger (PR) | Aplica salvaguardas para reduzir probabilidade e impacto de eventos. | Implementa autenticação forte, treinamento, proteção de dados e configurações seguras. |
| Detectar (DE) | Encontra e analisa possíveis eventos em tempo hábil. | Centraliza registros, define alertas e investiga comportamento anômalo. |
| Responder (RS) | Contém e trata incidentes, coordenando comunicação e análise. | Aciona o plano, isola sistemas afetados e comunica as partes pertinentes. |
| Recuperar (RC) | Restaura capacidades e serviços e incorpora aprendizados. | Restaura cópias testadas, valida integridade e acompanha a retomada. |

### Novidade da versão 2.0

A principal ampliação foi a função **Govern**, que torna explícitos resultados de governança e gestão de risco organizacional. Ela não existia como função no CSF 1.1. A versão 2.0 também amplia a aplicabilidade para organizações de todos os portes e reforça a gestão de risco de terceiros, entre outras atualizações. O CSF 2.0 não substitui controles técnicos detalhados: pode ser combinado com catálogos como o [NIST SP 800-53](sp-800-53.md).

## Como usar na prática

1. Defina o escopo (por exemplo, um serviço essencial) e reúna as partes responsáveis pelo negócio, tecnologia, privacidade e risco.
2. Descreva o perfil atual usando resultados do Core pertinentes ao contexto; documente evidências e lacunas, sem presumir que todo resultado precisa ter a mesma prioridade.
3. Crie um perfil pretendido alinhado a requisitos legais, objetivos e tolerância a risco.
4. Priorize ações, responsáveis, recursos e prazos. Use referências informativas do NIST para localizar práticas e controles relevantes.
5. Revise o perfil quando houver mudanças de negócio, tecnologia, ameaças ou requisitos.

## Como pesquisar na fonte oficial

No site do NIST, abra **Cybersecurity Framework** e procure pelos recursos da versão 2.0, incluindo o documento do Núcleo, perfis, níveis e referências informativas. No portal do Centro de Recursos de Segurança de Computadores (Computer Security Resource Center, CSRC), use a busca pelo título ou número da publicação para localizar documentos e suas versões. Para conectar resultados do framework a controles detalhados, pesquise a Publicação Especial (Special Publication, SP) 800-53, Revisão (Revision, Rev.) 5, e consulte também a SP 800-53B.

## Erros comuns / armadilhas

- Tratar as seis funções como etapas rígidas ou sequenciais; são resultados que se reforçam continuamente.
- Supor que a adoção do framework, por si só, comprova conformidade ou certifica a organização.
- Confundir os níveis (Tiers) com uma nota universal de maturidade ou usar controles sem considerar o contexto.

## Links oficiais

- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) — página do framework, versão 2.0, documentos e recursos.
- [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final) — catálogo de controles relacionado aos resultados do framework.

## Exercício rápido

1. Para um serviço de folha de pagamento, dê um exemplo de resultado em Governar, Proteger e Recuperar.
2. Explique por que um perfil pretendido não é uma lista universal de controles.