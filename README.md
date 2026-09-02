<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="./images/guia.png" alt="Guia de Consul" width="160" height="160">
  </a>
  <h1 align="center">Guia de Consul</h1>
</p>

## :dart: O guia para alavancar a sua carreira

> Consul é a ferramenta da HashiCorp para service discovery, service mesh, configuração distribuída (KV store) e checagem de saúde de serviços — a peça que faz microsserviços se encontrarem e conversarem com segurança em qualquer ambiente (VMs, Kubernetes, containers, multi-cloud). Desde agosto de 2023 o código do Consul é licenciado sob a **Business Source License 1.1 (BSL)**, não mais MPL 2.0 — e, desde 2025, a HashiCorp é uma empresa do grupo **IBM**. Diferente do Terraform (que ganhou o fork [OpenTofu](https://opentofu.org/)) e do Vault (que ganhou o [OpenBao](https://openbao.org/)), até o momento **não existe um fork open source equivalente e amplamente adotado do Consul** — vale entender essa diferença antes de decidir sua stack. Este guia reúne documentação oficial, cursos, ferramentas do ecossistema, projetos práticos e um capítulo dedicado a usar IA na prática com Consul — tudo verificado e organizado para quem já entende o básico de redes/microsserviços e quer dominar service discovery e service mesh de verdade.

<sub> <strong>Siga nas redes sociais para acompanhar mais conteúdos: </strong> <br>
[<img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">](https://github.com/arthurspk)
[<img src = "https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white">](https://www.facebook.com/seixasqlc/)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/arthurspk/)
[<img src = "https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">](https://twitter.com/manotoquinho)
[![Discord Badge](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/NbMQUPjHz7)
[<img src = "https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/guiadevbrasil/)
[![Youtube Badge](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCzmXzz_VR0Li8-YOvWN_t3g)
</sub>

## ⚠️ Aviso importante

> Antes de tudo você pode me ajudar e colaborar, deu bastante trabalho fazer esse repositório e organizar para fazer seu estudo ou trabalho melhor, portanto você pode me ajudar das seguintes maneiras:

- Me siga no [Github](https://github.com/arthurspk)
- Acesse as redes sociais do [Guia Dev Brasil](https://linktr.ee/guiadevbrasil)
- Mande feedbacks no [LinkedIn](https://www.linkedin.com/in/arthurspk/)

## 💡 Nossa proposta

> A proposta deste guia é dar uma ideia sobre o atual panorama e guiá-lo se você estiver confuso sobre qual será o seu próximo aprendizado, sem influenciar você a seguir os 'hypes' e 'trends' do momento. Acreditamos que com um maior conhecimento das diferentes estruturas e soluções disponíveis poderá escolher a ferramenta que melhor se aplica às suas demandas. E lembre-se, 'hypes' e 'trends' nem sempre são as melhores opções.

## :beginner: Para quem está começando agora

> Não se assuste com a quantidade de conteúdo apresentado neste guia. Acredito que quem está começando pode usá-lo não como um objetivo, mas como um apoio para os estudos. <b>Neste momento, dê enfoque no que te dá produtividade e o restante marque como <i>Ver depois</i></b>. Ao passo que seu conhecimento se torna mais amplo, a tendência é este guia fazer mais sentido e ficar fácil de ser assimilado. Bons estudos e entre em contato sempre que quiser! :punch:

## 🚨 Colabore

- Abra Pull Requests com atualizações
- Discuta ideias em Issues
- Compartilhe o repositório com a sua comunidade

## 🌍 Tradução

> Se você deseja acompanhar esse repositório em outro idioma que não seja o Português Brasileiro, você pode optar pelas escolhas de idiomas abaixo, você também pode colaborar com a tradução para outros idiomas e a correções de possíveis erros ortográficos, a comunidade agradece.

<img src = "https://i.imgur.com/lpP9V2p.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>English — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>
<img src = "https://i.imgur.com/GprSvJe.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Spanish — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>
<img src = "https://i.imgur.com/4DX1q8l.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Chinese — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>
<img src = "https://i.imgur.com/6MnAOMg.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Hindi — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>
<img src = "https://i.imgur.com/8t4zBFd.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Arabic — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>
<img src = "https://i.imgur.com/iOdzTmD.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>French — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>
<img src = "https://i.imgur.com/PILSgAO.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Italian — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>
<img src = "https://i.imgur.com/0lZOSiy.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Korean — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>
<img src = "https://i.imgur.com/3S5pFlQ.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Russian — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>
<img src = "https://i.imgur.com/i6DQjZa.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>German — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>
<img src = "https://i.imgur.com/wWRZMNK.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Japanese — </b> [Click Here](https://github.com/arthurspk/guiadeconsul)<br>

## 📚 ÍNDICE

[🗺️ Roadmap](#️-roadmap) <br>
[📖 Documentação oficial](#-documentação-oficial) <br>
[🔤 Sites e cursos para aprender Consul](#-sites-e-cursos-para-aprender-consul) <br>
[📚 Livros](#-livros) <br>
[🎥 Canais no Youtube](#-canais-no-youtube) <br>
[🛠️ Ferramentas](#️-ferramentas) <br>
[🧪 Projetos práticos e desafios](#-projetos-práticos-e-desafios) <br>
[🤖 IA na prática](#-ia-na-prática) <br>
[💼 Carreira e vagas](#-carreira-e-vagas) <br>
[👥 Comunidades](#-comunidades) <br>
[🎓 Certificações](#-certificações) <br>

## 🗺️ Roadmap

Não existe um roadmap visual oficial do Consul no estilo roadmap.sh. O caminho reconhecido pela própria HashiCorp é: entender os conceitos (agente, catálogo, DNS) → registrar e descobrir serviços → checagens de saúde → KV store e configuração dinâmica → ACLs e segurança → Consul Connect (service mesh) → rodar em produção (VMs ou Kubernetes).

- [Consul — O que é (documentação oficial)](https://developer.hashicorp.com/consul/docs/intro) — ponto de partida oficial: conceitos, casos de uso e onde o Consul se encaixa.
- [Consul — Arquitetura](https://developer.hashicorp.com/consul/docs/architecture) — como servidores, agentes, consenso (Raft) e gossip (Serf) se encaixam por baixo do capô.
- [Consul — Notas de versão](https://developer.hashicorp.com/consul/docs/release-notes) — o que muda em cada versão, útil para acompanhar para onde o projeto está indo.
- [CHANGELOG do Consul (GitHub)](https://github.com/hashicorp/consul/blob/main/CHANGELOG.md) — histórico completo de mudanças, versão a versão.
- [Releases do Consul (GitHub)](https://github.com/hashicorp/consul/releases) — binários e notas de cada lançamento.

## 📖 Documentação oficial

- [developer.hashicorp.com/consul](https://developer.hashicorp.com/consul) — portal oficial: docs, tutoriais, API e referência de comandos.
- [Documentação (docs hub)](https://developer.hashicorp.com/consul/docs) — índice completo da documentação atual.
- [Instalação](https://developer.hashicorp.com/consul/install) — como instalar o Consul em Linux, macOS, Windows ou via pacote.
- [Referência de comandos (CLI)](https://developer.hashicorp.com/consul/commands) — todos os subcomandos do binário `consul`.
- [Referência da API HTTP](https://developer.hashicorp.com/consul/api-docs) — todos os endpoints da API do Consul.
- [Registrar serviços](https://developer.hashicorp.com/consul/docs/register) — como um serviço se registra no catálogo do Consul.
- [Descobrir serviços](https://developer.hashicorp.com/consul/docs/discover) — DNS e API para localizar serviços saudáveis.
- [Service mesh com Consul Connect](https://developer.hashicorp.com/consul/docs/connect) — mTLS, sidecars e proxies (Envoy) entre serviços.
- [Implantar o Consul](https://developer.hashicorp.com/consul/docs/deploy) — visão geral de topologias de implantação.
- [Rodar o Consul em Docker](https://developer.hashicorp.com/consul/docs/deploy/server/docker) — servidor e agentes em containers.
- [Rodar o Consul em Kubernetes](https://developer.hashicorp.com/consul/docs/deploy/server/k8s) — Helm chart oficial e arquitetura no k8s.
- [Segurança do Consul](https://developer.hashicorp.com/consul/docs/secure) — ACLs, TLS/mTLS e boas práticas de hardening.
- [Gerenciar o Consul](https://developer.hashicorp.com/consul/docs/manage) — operação do cluster no dia a dia.
- [DNS forwarding](https://developer.hashicorp.com/consul/docs/manage/dns/forwarding) — como integrar o DNS do Consul ao resolvedor do sistema.
- [Monitorar o Consul](https://developer.hashicorp.com/consul/docs/monitor) — métricas, logs e telemetria.
- [Upgrade do Consul](https://developer.hashicorp.com/consul/docs/upgrade) — como atualizar um cluster em produção com segurança.
- [Referência do arquivo de configuração do agente](https://developer.hashicorp.com/consul/docs/reference/agent/configuration-file) — todas as opções de configuração do agente Consul.
- [Tutoriais oficiais (HashiCorp Developer)](https://developer.hashicorp.com/consul/tutorials) — trilhas guiadas por caso de uso, do zero ao avançado.
- [Código-fonte do Consul (GitHub)](https://github.com/hashicorp/consul) — repositório oficial, sob licença BSL 1.1.
- [Licença do Consul (BSL 1.1)](https://github.com/hashicorp/consul/blob/main/LICENSE) — o texto legal da licença, direto do repositório.
- [Terraform Provider Consul (documentação)](https://registry.terraform.io/providers/hashicorp/consul/latest/docs) — como provisionar recursos do Consul via Terraform/OpenTofu.

## 🔤 Sites e cursos para aprender Consul

> Cursos para aprender Consul em Português

- [Service Discovery na prática com Consul (Full Cycle)](https://www.youtube.com/watch?v=cOQQYrhYH4U) — aula prática sobre por que e como usar service discovery com Consul em uma arquitetura de microsserviços.
- [#2 SEMANA DEVOPS — O incrível CONSUL by Hashicorp (LINUXtips)](https://www.youtube.com/watch?v=0erwMnIG0tc) — aula da Semana DevOps da LINUXtips dedicada ao Consul.
- [Service Discovery e Configuração Dinâmica com Consul e Golang (HunCoding)](https://www.youtube.com/watch?v=xkYdLB9UiMo) — como usar o Consul para service discovery e configuração dinâmica em uma aplicação Go.
- [Aula ao vivo: Trabalhando com Service Discovery com Consul (School of Net)](https://www.youtube.com/watch?v=crKKwiewJkg) — replay de aula ao vivo cobrindo os fundamentos práticos de service discovery com Consul.
- [Iniciando com o Consul (Cloud Treinamentos | by UpperStack)](https://www.youtube.com/watch?v=K2xey6yw_Nc) — primeiros passos: instalação, agente e conceitos básicos.
- [Implementando SERVICE DISCOVERY usando CONSUL e OCELOT (Emerging Code)](https://www.youtube.com/watch?v=da7RXDqU1Y4) — service discovery com Consul integrado a um API Gateway (Ocelot, .NET).
- [Implementando o HashiCorp Consul: um guia para gerenciamento de serviços e descoberta (dev.to)](https://dev.to/gabriel755/implementando-o-hashicorp-consul-um-guia-para-gerenciamento-de-servicos-e-descoberta-3h9n) — artigo introdutório sobre os conceitos e o uso prático do Consul.
- [Desvendando o HashiCorp Consul: o pilar de conectividade além do Terraform e Vault (leonam.io)](https://leonam.io/posts/desvendando-o-hashicorp-consul-o-pilar-de-conectividade-al%C3%A9m-do-terraform-e-vault/) — artigo que situa o Consul dentro do ecossistema HashiCorp, além do Terraform e do Vault.
- [Curso Vault and Consul by HashiCorp (IT Solutions)](https://www.itsolutionss.com.br/cursos/curso-vault-and-consul-by-hashicorp/) — treinamento corporativo brasileiro cobrindo Vault e Consul. Curso pago.
- [Curso HashiCorp Consul Administration and Service Mesh (IT Solutions)](https://www.itsolutionss.com.br/cursos/curso-hashicorp-consul-administration-and-service-mesh/) — treinamento corporativo brasileiro focado em administração do Consul e service mesh. Curso pago.

> Cursos para aprender Consul em Inglês

- [Consul Service Mesh Tutorial for Beginners [Crash Course] (TechWorld with Nana)](https://www.youtube.com/watch?v=s3I1kKKfjtQ) — o crash course mais completo e didático sobre Consul Connect disponível gratuitamente.
- [Introduction to HashiCorp Consul with Armon Dadgar (HashiCorp)](https://www.youtube.com/watch?v=mxeMdl0KvBI) — introdução conceitual dada pelo próprio cocriador do Consul.
- [Introduction to HashiCorp Consul Connect (HashiCorp)](https://www.youtube.com/watch?v=8T8t4-hQY74) — como o Consul Connect resolve service mesh com mTLS.
- [Getting into HashiCorp Consul, Part 4: Security, Traffic Encryption, and ACLs (HashiCorp)](https://www.youtube.com/watch?v=wIub6PZWRmY) — parte da série de aprofundamento em segurança e criptografia de tráfego.
- [Getting into HashiCorp Consul, Part 5: All About Access Control Lists (HashiCorp)](https://www.youtube.com/watch?v=HB4u_C85HV8) — tudo sobre ACLs no Consul, direto da série oficial.
- [Getting into HashiCorp Consul, Part 11: Mesh Federation (HashiCorp)](https://www.youtube.com/watch?v=3Cct7LtTGnc) — como federar múltiplos datacenters/clusters Consul em um único mesh.
- [Network Automation: Consul and Terraform (HashiCorp)](https://www.youtube.com/watch?v=_BbOk9cJI-w) — como Consul e Terraform se complementam na automação de rede.
- [Consul and Chaos Engineering (HashiCorp)](https://www.youtube.com/watch?v=XJlqDGO6Irk) — usando engenharia do caos para validar a resiliência de um mesh Consul.
- [Learning HashiCorp Consul with Envoy (Phillip Hocking)](https://www.youtube.com/watch?v=inonHcLDNuE) — como o Consul se integra ao proxy Envoy na prática.
- [Ultimate Guide to HashiCorp Core Products (2025): Terraform, Vault, Consul, Nomad & More Explained (FlashGenius)](https://www.youtube.com/watch?v=bitzcDmwd7s) — panorama de 2025 sobre todo o ecossistema HashiCorp, incluindo o papel do Consul.

## 📚 Livros

Consul é um tema de nicho: não encontramos livros dedicados a ele publicados originalmente em português, e a oferta em inglês também é escassa (a maioria dos livros de HashiCorp foca em Terraform ou Vault). O único título dedicado e verificado que encontramos:

- [Simplifying Service Management with Consul (Robert E. Jackson, Packt)](https://books.google.com/books/about/Simplifying_Service_Management_with_Cons.html?id=fhihzgEACAAJ) — livro dedicado à administração do Consul: service discovery, service mesh e operação em produção. Livro pago.

## 🎥 Canais no Youtube

> Em português

- [Full Cycle](https://www.youtube.com/@FullCycle) — arquitetura de microsserviços, DDD e Clean Architecture, com conteúdo prático sobre Consul.
- [LINUXtips](https://www.youtube.com/@LINUXtips) — referência brasileira em Linux, DevOps e infraestrutura, com aulas sobre o ecossistema HashiCorp.
- [HunCoding](https://www.youtube.com/@HunCoding) — Go, microsserviços e infraestrutura, incluindo service discovery com Consul.

> Em inglês

- [HashiCorp, an IBM Company](https://www.youtube.com/@HashiCorp) — canal oficial: anúncios de versão, aprofundamentos técnicos e demos do Consul direto de quem o mantém.
- [TechWorld with Nana](https://www.youtube.com/@TechWorldwithNana) — um dos canais de DevOps mais assistidos do mundo, com crash courses de alta qualidade.

## 🛠️ Ferramentas

> Ecossistema oficial HashiCorp

- [consul-template](https://github.com/hashicorp/consul-template) — gera arquivos de configuração automaticamente a partir de dados no Consul (KV, catálogo).
- [consul-k8s](https://github.com/hashicorp/consul-k8s) — CLI e Helm chart oficiais para rodar o Consul (incluindo service mesh) no Kubernetes.
- [envconsul](https://github.com/hashicorp/envconsul) — injeta valores do Consul (e do Vault) como variáveis de ambiente em um processo.
- [consul-esm](https://github.com/hashicorp/consul-esm) — monitora a saúde de serviços externos (fora do cluster) e reporta ao Consul.
- [consul-replicate](https://github.com/hashicorp/consul-replicate) — replica dados de KV entre datacenters Consul.
- [consul-aws](https://github.com/hashicorp/consul-aws) — sincroniza serviços entre o catálogo do Consul e o AWS Cloud Map.
- [consul-api-gateway](https://github.com/hashicorp/consul-api-gateway) — API Gateway nativo do Consul, baseado em Envoy.
- [Terraform Provider Consul](https://github.com/hashicorp/terraform-provider-consul) — provisione e gerencie recursos do Consul via Terraform ou OpenTofu.
- [Imagem oficial do Consul no Docker Hub](https://hub.docker.com/_/consul) — imagem oficial para rodar o Consul em containers.

> Integrações do ecossistema

- [Envoy Proxy](https://www.envoyproxy.io/) — o proxy padrão usado pelo Consul Connect para formar o service mesh.
- [Prometheus — consul_sd_config](https://prometheus.io/docs/prometheus/latest/configuration/configuration/#consul_sd_config) — descoberta automática de alvos de monitoramento a partir do catálogo do Consul.
- [Fabio](https://fabiolb.net/) — load balancer HTTP/TCP que se configura sozinho a partir do catálogo do Consul.
- [Traefik — provedor Consul Catalog](https://doc.traefik.io/traefik/reference/install-configuration/providers/hashicorp/consul-catalog/) — como o Traefik descobre e roteia serviços registrados no Consul.
- [Grafana](https://grafana.com/) — dashboards para visualizar as métricas exportadas pelo Consul e pelo Consul Connect.

> Contexto de licenciamento (leitura recomendada)

- [OpenTofu](https://opentofu.org/) — fork open source do Terraform mantido pela Linux Foundation, criado após a mudança de licença de 2023.
- [OpenBao](https://openbao.org/) — fork open source do Vault mantido pela Linux Foundation, mesmo contexto de licenciamento. Não existe (ainda) um projeto equivalente para o Consul.

## 🧪 Projetos práticos e desafios

- [Tutoriais oficiais — Primeiros passos em VMs](https://developer.hashicorp.com/consul/tutorials/get-started-vms) — trilha prática oficial: suba um cluster Consul do zero em máquinas virtuais.
- [Tutoriais oficiais — Primeiros passos no Kubernetes](https://developer.hashicorp.com/consul/tutorials/get-started-kubernetes) — trilha prática oficial: instale e explore o Consul dentro de um cluster Kubernetes.
- [Tutoriais oficiais — Consul em produção (VMs)](https://developer.hashicorp.com/consul/tutorials/production-vms) — checklist prático para levar um cluster Consul a produção em VMs.
- [Tutoriais oficiais — Consul em produção (Kubernetes)](https://developer.hashicorp.com/consul/tutorials/production-kubernetes) — checklist prático para produção no Kubernetes.
- [hashicorp/demo-consul-101](https://github.com/hashicorp/demo-consul-101) — código e binários do curso introdutório oficial do Consul.
- [hashicorp-education/learn-consul-docker](https://github.com/hashicorp-education/learn-consul-docker) — laboratório prático para aprender Consul usando Docker Compose.
- [hashicorp/consul-helm](https://github.com/hashicorp/consul-helm) — Helm chart histórico do Consul para Kubernetes (hoje mantido dentro do `consul-k8s`), útil como referência de configuração.
- [Projetos com a tag "consul" no GitHub](https://github.com/topics/consul) — explore projetos reais da comunidade que usam Consul em produção.

## 🤖 IA na prática

Consul é uma ferramenta de infraestrutura: configuração declarativa (HCL/JSON), CLI e uma API HTTP bem definida — um cenário ótimo para assistentes de IA, desde que você valide tudo antes de aplicar em produção.

**Para aprender**
- Peça para a IA **explicar um trecho de `agent.hcl` ou `service.hcl`** linha a linha antes de rodar `consul validate` nele.
- Cole a saída de `consul members` ou `consul catalog services` e peça para a IA explicar o estado do cluster.
- Peça exemplos comparativos: "mostre como registrar o mesmo serviço via arquivo de configuração e via API HTTP do Consul".
- Peça para gerar uma política de ACL mínima (`consul acl policy create`) para um caso específico e explique cada regra — depois confira na [documentação de segurança](https://developer.hashicorp.com/consul/docs/secure).

**Para trabalhar**
- Use [GitHub Copilot](https://github.com/features/copilot), [Cursor](https://cursor.com/) ou [Claude Code](https://code.claude.com/docs/en/overview) para gerar arquivos de configuração do agente, políticas de intenção (`service-intentions`) do Consul Connect e manifests do Helm chart oficial.
- O [Terraform MCP Server](https://github.com/hashicorp/terraform-mcp-server) da própria HashiCorp permite que um agente de IA consulte a documentação de providers (incluindo o `hashicorp/consul`) diretamente dentro do editor, reduzindo alucinação de argumentos de recurso.
- Depois de qualquer configuração gerada por IA, rode `consul validate` e, em produção, valide em um ambiente de staging antes do rollout — a IA erra nomes de campos e assume versões antigas do agente com frequência.

**Limites e boas práticas**
- IA **mistura sintaxe de versões diferentes** do Consul (a API e o formato de configuração mudaram bastante entre versões 1.x). Confirme sempre na [referência oficial](https://developer.hashicorp.com/consul/docs/reference/agent/configuration-file) a versão que você está usando.
- Nunca cole tokens de ACL, certificados TLS ou segredos do KV store em ferramentas de IA sem a política de segurança da sua empresa.
- Regras de ACL e `service-intentions` geradas por IA controlam **quem fala com quem** no seu mesh — revise cada intenção antes de aplicar; um erro aqui pode expor ou derrubar um serviço em produção.

## 💼 Carreira e vagas

Consul raramente aparece como requisito isolado — normalmente vem dentro de vagas de DevOps, SRE, Platform Engineering ou Infraestrutura que citam "ecossistema HashiCorp" (Terraform, Vault, Nomad, Consul) ou "service mesh".
- [Programathor — vagas de DevOps](https://programathor.com.br/jobs-devops) — vagas de tecnologia no Brasil filtradas por DevOps.
- [Programathor — vagas com HashiCorp](https://programathor.com.br/jobs-hashicorp) — vagas brasileiras que citam ferramentas HashiCorp.
- [GeekHunter](https://www.geekhunter.com.br/) — plataforma brasileira onde empresas fazem propostas a devs e a profissionais de infraestrutura.
- [Coodesh](https://coodesh.com/) — vagas tech no Brasil com processos seletivos padronizados.
- [Remotar](https://remotar.com.br/) — vagas 100% remotas para brasileiros, incluindo DevOps/SRE.
- [backend-br/vagas](https://github.com/backend-br/vagas) — vagas de back-end e infraestrutura publicadas como issues no GitHub.
- [LinkedIn — vagas "Consul HashiCorp"](https://www.linkedin.com/jobs/search/?keywords=consul%20hashicorp) — busca filtrada por Consul/HashiCorp no maior banco de vagas do mundo.
- [RemoteOK — vagas remotas de DevOps](https://remoteok.com/remote-devops-jobs) — vagas remotas internacionais de DevOps/infraestrutura.
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — preparação completa para entrevistas técnicas, incluindo perguntas de sistemas distribuídos.

## 👥 Comunidades

- [HashiCorp Discuss](https://discuss.hashicorp.com/) — fórum oficial da HashiCorp para todas as ferramentas.
- [HashiCorp Discuss — categoria Consul](https://discuss.hashicorp.com/c/consul/29) — dúvidas, anúncios e discussões técnicas específicas do Consul.
- [r/hashicorp](https://www.reddit.com/r/hashicorp/) — subreddit da comunidade de ferramentas HashiCorp (Terraform, Vault, Nomad, Consul).
- [r/devops](https://www.reddit.com/r/devops/) — subreddit geral de DevOps, onde Consul aparece com frequência em discussões de service mesh.
- [He4rt Developers](https://heartdevs.com/) — comunidade brasileira open source com Discord ativo e projetos de infraestrutura.
- [TabNews](https://www.tabnews.com.br/) — comunidade brasileira de conteúdo técnico, boa para buscar discussões sobre infraestrutura e DevOps.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — comunidade brasileira com canais de infraestrutura, dicas e vagas.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — diretório de grupos brasileiros no Telegram, incluindo DevOps/infraestrutura.
- [HashiCorp no X/Twitter](https://x.com/hashicorp) — anúncios oficiais de produto, incluindo Consul.
- [HashiCorp no LinkedIn](https://www.linkedin.com/company/hashicorp/) — página oficial da empresa.

## 🎓 Certificações

Não existe atualmente uma certificação oficial ativa de Consul. A HashiCorp mantinha a "HashiCorp Certified: Consul Associate", mas em 2026 a [página oficial de certificações](https://developer.hashicorp.com/certifications) lista apenas certificações de Terraform e de Vault — o exame de Consul foi descontinuado. Desconfie de cursos e "simulados" que ainda anunciam essa certificação como se estivesse ativa: verifique sempre a lista oficial acima antes de pagar por qualquer preparatório.

## 🚨 Como contribuir

Toda contribuição é bem-vinda — de um recurso novo a uma correção de link quebrado. Veja os critérios completos e o passo a passo em [CONTRIBUTING.md](./CONTRIBUTING.md).

## 📄 Licença

Este guia é distribuído sob a licença [MIT](./LICENSE). O conteúdo listado (cursos, livros, ferramentas etc.) pertence aos seus respectivos autores — este repositório apenas organiza e credita as fontes.

## 💙 Apoie o projeto

Se este guia te ajudou, considere dar uma ⭐ no repositório e seguir as redes sociais do [Guia Dev Brasil](https://linktr.ee/guiadevbrasil) para acompanhar as próximas atualizações.
