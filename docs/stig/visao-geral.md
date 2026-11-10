# Visão geral dos DISA STIGs

## O que é

Os Guias de Implementação Técnica de Segurança (Security Technical Implementation Guides, STIGs) são documentos técnicos publicados pela Agência de Sistemas de Informação de Defesa (Defense Information Systems Agency, DISA), do Departamento de Defesa dos Estados Unidos (Department of Defense, DoD). Eles definem verificações e orientações de configuração para reduzir riscos em tecnologias e ambientes específicos. Seu uso é especialmente associado ao DoD; fora desse contexto, avalie requisitos contratuais, regulatórios e compatibilidade antes de adotá-los.

## Por que importa

Um STIG transforma expectativas de segurança em verificações técnicas relativamente concretas. Ele ajuda equipes a identificar configurações fracas, registrar desvios e organizar correções. Não substitui avaliação de risco nem deve ser aplicado sem testar efeitos na operação.

## Para quem serve

Serve a administradores de sistemas e redes, profissionais de segurança, auditores e equipes de conformidade que trabalham com tecnologias cobertas por guias DISA. Estudantes podem usá-lo para aprender como requisitos se tornam verificações e ações de correção.

## Conceitos-chave

Os STIGs são específicos por produto e versão: podem existir guias para sistemas operacionais, servidores, equipamentos de rede, hipervisores e bancos de dados. Uma regra de uma versão não deve ser aplicada automaticamente a outra.

Uma regra costuma conter um identificador de vulnerabilidade (Vulnerability Identifier, Vulnerability ID), como `V-...`; uma severidade; um procedimento **Check** (verificação) para avaliar o requisito; e uma orientação **Fix** (correção) para tratar o desvio. Em geral, a Categoria I (Category I, CAT I) é a mais severa, a Categoria II (Category II, CAT II) é intermediária e a Categoria III (Category III, CAT III) é a menos severa. A categoria orienta prioridade no método DISA, mas não substitui a análise de risco própria da organização.

O Guia de Requisitos de Segurança (Security Requirements Guide, SRG) estabelece requisitos mais gerais para uma classe de sistemas ou tecnologia. Um STIG aplica requisitos a um produto ou implementação mais específica, com verificações e orientações concretas. Requisitos de SRG podem fundamentar STIGs diferentes; os documentos não são intercambiáveis.

O **STIG Viewer** é uma ferramenta DISA para abrir conteúdo STIG em formato compatível, navegar por regras e registrar resultados de avaliação, evidências e comentários conforme o fluxo de trabalho suportado. Ele não comprova conformidade automaticamente: a equipe ainda precisa executar os checks e validar evidências.

## Como usar na prática

1. Identifique produto, versão, ambiente e guia aplicável.
2. Leia os requisitos e avalie dependências operacionais antes de modificar configurações.
3. Use o STIG Viewer ou processo compatível para percorrer regras e registrar o estado de cada uma.
4. Execute o **Check**, guarde evidência e compare o resultado com a condição esperada.
5. Priorize correções conforme severidade e contexto, teste-as em ambiente controlado e registre exceções aprovadas.
6. Reavalie após atualizações do produto, da missão ou do próprio guia.

## Como pesquisar na fonte oficial

Acesse `public.cyber.mil/stigs` e use o catálogo ou a busca para filtrar por família de tecnologia e produto. Confirme a versão do produto e a data do guia antes de baixar arquivos. A página oficial disponibiliza os guias e recursos relacionados, incluindo informações sobre o STIG Viewer. Após baixar o pacote, consulte o README e os arquivos do guia para identificar o escopo, regras e formatos suportados. Para cada regra, leia identificador, severidade, descrição, **Check** e **Fix**; CAT I/II/III indicam prioridade de severidade, não a probabilidade personalizada de exploração no seu ambiente.

## Erros comuns / armadilhas

- Aplicar um STIG de outro produto ou versão sem verificar compatibilidade.
- Executar correções em produção sem teste: algumas podem interromper serviços legítimos.
- Interpretar CAT I/II/III como classificação completa de risco da organização.
- Tratar um resultado marcado como aprovado no Viewer como prova sem evidência.
- Confundir SRG (requisito geral) com STIG (orientação específica de implementação).

## Links oficiais

- [DISA Cyber Exchange — STIGs](https://public.cyber.mil/stigs/) — catálogo, guias por tecnologia e recursos oficiais.
- [DISA Cyber Exchange](https://public.cyber.mil/) — portal institucional que reúne recursos de cibersegurança da DISA.

## Exercício rápido

1. Escolha um produto no catálogo STIG e anote o nome e a versão do guia aplicável.
2. Em uma regra, localize Vulnerability ID, CAT, Check e Fix. Qual evidência seria necessária para sustentar o resultado do Check?
3. Explique com suas palavras por que um SRG não é simplesmente outro nome para STIG.
