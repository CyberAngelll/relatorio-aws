# ☁️ Implementação de Serviços AWS — Abstergo Industries

> Projeto de migração e otimização de infraestrutura em nuvem para plataforma virtual de farmácia, com foco em **redução de custos imediatos** utilizando serviços da AWS.

---

## 📋 Sobre o Projeto

Este projeto documenta a implementação de três serviços da Amazon Web Services (AWS) na empresa **Abstergo Industries**, com o objetivo de modernizar a infraestrutura de TI da plataforma virtual de farmácia, eliminar custos com servidores físicos e aumentar a escalabilidade, disponibilidade e segurança dos sistemas.

A proposta foi desenvolvida como parte de um estudo prático de computação em nuvem, simulando desafios reais encontrados em ambientes corporativos.

---

## 🎯 Objetivo

Selecionar e implementar **3 serviços AWS** capazes de gerar **redução de custos imediata**, substituindo infraestrutura local por soluções gerenciadas na nuvem, com ganhos em desempenho e confiabilidade.

---

## 🛠️ Serviços Implementados

### Etapa 1 — Amazon EC2 + Auto Scaling
**Foco:** Redução de custos com servidores e escalabilidade automática

Substituição dos servidores físicos locais por instâncias EC2 na AWS. O Auto Scaling ajusta automaticamente a capacidade computacional conforme a demanda da plataforma — escalando para cima em períodos de pico (campanhas, datas sazonais) e reduzindo em momentos de baixo tráfego, garantindo que a empresa pague apenas pelo que utiliza.

---

### Etapa 2 — Amazon S3 + Amazon CloudFront
**Foco:** Armazenamento econômico e entrega rápida de conteúdo estático

O catálogo de produtos da farmácia virtual (imagens de medicamentos, bulas em PDF, vídeos explicativos) foi migrado para buckets S3. O CloudFront foi configurado como CDN para distribuir esse conteúdo a partir de pontos de presença próximos aos usuários, reduzindo latência e custos de transferência de dados.

---

### Etapa 3 — Amazon RDS com Multi-AZ
**Foco:** Banco de dados gerenciado, seguro e com alta disponibilidade

Migração do banco de dados da plataforma para o Amazon RDS com configuração Multi-AZ. Backups automáticos, atualizações de SO e patches de segurança passam a ser gerenciados pela AWS, eliminando custos com DBA para tarefas rotineiras e garantindo replicação automática entre zonas de disponibilidade.

---

## 💰 Benefícios Esperados

| Benefício | Descrição |
|---|---|
| 📉 Redução de custos | Eliminação de gastos com servidores físicos e manutenção manual |
| ⚡ Escalabilidade | Ajuste automático de capacidade conforme a demanda |
| 🔒 Segurança | Criptografia em trânsito e em repouso nos serviços de armazenamento e banco de dados |
| 🌐 Desempenho | Entrega de conteúdo mais rápida via CDN para usuários em qualquer região |
| 🔁 Alta disponibilidade | Redundância automática com Multi-AZ e replicação de dados |


---

## 🏢 Informações do Projeto

| Campo | Detalhe |
|---|---|
| **Empresa** | Abstergo Industries |
| **Responsável** | Luiz Otávio F. Silva |
| **Data de Início** | 24/08/2025 |
| **Plataforma** | Amazon Web Services (AWS) |

---

## 🚀 Próximos Passos

- [ ] Implementar **AWS Lambda** para funções serverless e redução adicional de custos computacionais
- [ ] Configurar **Amazon SES** para comunicação automatizada com clientes (e-mails transacionais)
- [ ] Habilitar **AWS Cost Explorer** para monitoramento contínuo de gastos
- [ ] Avaliar uso de **Amazon ElastiCache** para cache de dados e redução de carga no RDS

---

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais e de demonstração de competências em computação em nuvem com AWS.

---

*Desenvolvido por **Luiz Otávio F. Silva** — Abstergo Industries*
