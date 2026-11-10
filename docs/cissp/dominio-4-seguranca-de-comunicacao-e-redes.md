# Domínio 4 — Segurança de Comunicação e Redes — 13%

## O que é

O Domínio 4 da certificação Profissional Certificado em Segurança de Sistemas de Informação (Certified Information Systems Security Professional, CISSP), do Consórcio Internacional de Certificação de Segurança de Sistemas de Informação (International Information System Security Certification Consortium, ISC2), cobre arquitetura, componentes, protocolos e operação de redes. Seu foco é proteger comunicações e segmentar sistemas.

## Por que importa

As redes conectam usuários, sistemas e serviços, mas também permitem que um problema se propague. Entender fluxos e limites ajuda a reduzir interceptação, alteração, abuso e indisponibilidade.

## Para quem serve

Serve a profissionais de redes e segurança, arquitetos, administradores e candidatos à CISSP. Iniciantes podem usar diagramas simples de comunicação para visualizar onde cada controle atua.

## Conceitos-chave

### Tópicos do outline oficial, em síntese

- Arquiteturas e modelos de comunicação em rede.
- Componentes, protocolos, serviços e meios de transmissão.
- Comunicação segura e controles de proteção de rede.
- Segmentação, segurança de dispositivos e redes sem fio.
- Acesso remoto, conectividade de terceiros e ambientes distribuídos.
- Monitoramento, disponibilidade e proteção de tráfego.

### Conceitos essenciais

Segmentação divide a rede em zonas com regras explícitas, limitando movimento lateral. Firewalls aplicam regras de tráfego; sistemas de detecção ou prevenção analisam atividades suspeitas. Redes privadas virtuais (Virtual Private Networks, VPNs) criam canais protegidos sobre redes não confiáveis, mas não tornam seguro um dispositivo comprometido. Segurança da Camada de Transporte (Transport Layer Security, TLS) protege comunicações conforme configuração e validação de certificados. O Sistema de Nomes de Domínio (Domain Name System, DNS), o roteamento e os protocolos de gestão também precisam de proteção.

Disponibilidade de rede depende de redundância, capacidade, proteção contra abuso e planejamento de recuperação. Uma arquitetura deve limitar fluxos necessários entre zonas e monitorá-los, em vez de confiar apenas no perímetro.

## Como usar na prática

1. Desenhe origem, destino, zonas e fluxos necessários para uma comunicação.
2. Marque onde ocorrem autenticação, criptografia, filtragem e monitoramento.
3. Avalie o que acontece se um dispositivo ou segmento for comprometido.
4. Revise regras e registros para confirmar que os fluxos observados correspondem ao desenho aprovado.

### Dicas de estudo

- Desenhe o caminho da comunicação e identifique onde autenticação, criptografia e filtragem ocorrem.
- Diferencie controle de camada de rede, transporte e aplicação e reconheça os limites de cada um.
- Em cenários sem fio ou remotos, avalie identidade do usuário e do dispositivo, não só a existência de um túnel.

## Como pesquisar na fonte oficial

Na página da ISC2, abra o **CISSP Exam Outline** e confirme a data de vigência antes de usar os pesos do exame. Localize **Domain 4** para revisar os objetivos cobrados. Consulte também a seção oficial de preparação para o exame. Para controles, acesse o Centro de Recursos de Segurança de Computadores (Computer Security Resource Center, CSRC), do Instituto Nacional de Padrões e Tecnologia dos Estados Unidos (National Institute of Standards and Technology, NIST), e pesquise a Publicação Especial (Special Publication, SP) 800-53, Revisão (Revision, Rev.) 5.

## Erros comuns / armadilhas

- Supor que uma VPN protege um dispositivo já comprometido ou substitui controle de identidade.
- Achar que criptografia do canal protege os dados depois que chegam ao destino.
- Confiar apenas no perímetro sem limitar e monitorar comunicação entre zonas internas.

## Links oficiais

- [ISC2 CISSP](https://www.isc2.org/certifications/cissp) — página da certificação, outline e recursos de estudo.
- [NIST CSF 2.0](../nist/csf-2.0.md) — resultados para organizar gestão de risco de cibersegurança.
- Anterior: [Domínio 3 — Arquitetura e Engenharia](dominio-3-arquitetura-e-engenharia-de-seguranca.md); próximo: [Domínio 5 — Gestão de Identidade e Acesso](dominio-5-gestao-de-identidade-e-acesso.md)

## Exercício rápido

1. Desenhe o acesso remoto de uma pessoa a um sistema interno e indique três controles em pontos diferentes.
2. O que a criptografia de um canal não protege depois que a informação chega ao servidor?