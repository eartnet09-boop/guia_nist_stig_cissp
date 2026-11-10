# Domínio 3 — Arquitetura e Engenharia de Segurança — 13%

## O que é

O Domínio 3 da certificação Profissional Certificado em Segurança de Sistemas de Informação (Certified Information Systems Security Professional, CISSP), do Consórcio Internacional de Certificação de Segurança de Sistemas de Informação (International Information System Security Certification Consortium, ISC2), aplica princípios de segurança ao projeto, construção e avaliação de sistemas. Abrange modelos, mecanismos de proteção, criptografia, resiliência e segurança física.

## Por que importa

Decisões de arquitetura determinam quais riscos serão difíceis ou caros de corrigir depois. Projetar salvaguardas desde o início reduz exposição e permite equilibrar proteção, operação e custo.

## Para quem serve

Serve a arquitetos, engenheiros, profissionais de segurança, avaliadores e candidatos à CISSP. Iniciantes podem usar os modelos para organizar a compreensão de mecanismos e propriedades de segurança.

## Conceitos-chave

### Tópicos do outline oficial, em síntese

- Conceitos centrais, modelos e princípios de arquitetura segura.
- Avaliação de requisitos e seleção de controles de segurança.
- Modelagem de ameaças, superfícies de ataque e padrões de projeto.
- Segurança de sistemas, componentes, ambientes e tecnologias emergentes.
- Criptografia e gestão do ciclo de vida de chaves.
- Princípios de segurança física e ambiental.

### Conceitos essenciais

**Defesa em profundidade** usa camadas de controles para que a falha de uma salvaguarda não exponha imediatamente o sistema. **Menor privilégio** limita permissões ao necessário; **fail secure** busca manter uma condição protegida quando ocorre falha; **separação de funções** reduz concentração de poder. Modelos como Bell–LaPadula e Biba são abstrações para raciocinar, respectivamente, sobre confidencialidade e integridade em contextos específicos.

Criptografia simétrica usa uma chave compartilhada e costuma ser eficiente para grandes volumes; criptografia assimétrica usa um par de chaves e dá suporte a troca de chaves e assinaturas digitais. Funções hash criptográficas produzem resumos e ajudam a verificar integridade, mas não cifram dados. Certificados associam uma identidade a uma chave pública conforme uma infraestrutura de confiança. A segurança depende também de geração, armazenamento, rotação, cópia de segurança e revogação de chaves.

## Como usar na prática

1. Identifique os ativos, as ameaças e as propriedades que precisam ser protegidas.
2. Selecione princípios e controles desde a arquitetura, incluindo falhas e dependências.
3. Verifique a gestão de chaves, certificados, acesso e recuperação junto com o algoritmo escolhido.
4. Teste se o desenho atende às necessidades de segurança e operação.

### Dicas de estudo

- Associe cada mecanismo à propriedade que oferece e ao que ele não oferece.
- Em questões de arquitetura, prefira controles preventivos desde o projeto e valide consequências operacionais.
- Revise modelos de controle de acesso e modelos de confidencialidade/integridade sem tratá-los como implementações universais.

## Como pesquisar na fonte oficial

Na página da ISC2, localize o **CISSP Exam Outline** oficial, confirme sua data de vigência e consulte **Domain 3** para comparar os objetivos deste resumo com o outline. A página de preparação para o exame reúne os recursos oficiais disponíveis. Para aprofundar controles, consulte o Instituto Nacional de Padrões e Tecnologia dos Estados Unidos (National Institute of Standards and Technology, NIST), acesse o Centro de Recursos de Segurança de Computadores (Computer Security Resource Center, CSRC) e pesquise a Publicação Especial (Special Publication, SP) 800-53, Revisão (Revision, Rev.) 5.

## Erros comuns / armadilhas

- Confundir criptografia com hash: hash não cifra nem pode ser revertido para recuperar o conteúdo.
- Supor que uma assinatura digital, sem validação de identidade e contexto, prova automaticamente que o conteúdo é confiável.
- Tratar um modelo teórico como implementação completa de um sistema seguro.

## Links oficiais

- [ISC2 CISSP](https://www.isc2.org/certifications/cissp) — página da certificação, outline e preparação oficial.
- [NIST SP 800-53 Rev. 5](../nist/sp-800-53.md) — catálogo de controles aplicáveis à arquitetura e engenharia.
- Anterior: [Domínio 2 — Segurança de Ativos](dominio-2-seguranca-de-ativos.md); próximo: [Domínio 4 — Segurança de Comunicação e Redes](dominio-4-seguranca-de-comunicacao-e-redes.md)

## Exercício rápido

1. Explique com uma analogia a diferença entre criptografia simétrica, assimétrica e hash.
2. Cite uma camada de defesa que limitaria o impacto da falha de outra camada.