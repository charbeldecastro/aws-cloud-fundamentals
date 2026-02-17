# Capítulo 02 – Modelos de Serviço

Após compreender a implantação, é necessário entender como os serviços são consumidos.

Os modelos são classificados por nível de abstração:

- IaaS
- PaaS
- SaaS

---

## IaaS – Infrastructure as a Service

Fornece infraestrutura virtualizada:

- Máquinas virtuais
- Redes
- Armazenamento
- Sistemas operacionais

### Responsabilidades

Cliente:
- Sistema operacional
- Aplicação
- Dados
- Segurança do ambiente

Provedor:
- Hardware físico
- Virtualização
- Datacenter
- Rede física

### Exemplos

- Amazon EC2
- Azure Virtual Machines
- Google Compute Engine

---

## PaaS – Platform as a Service

Fornece ambiente completo para desenvolvimento e deploy de aplicações.

### Características

- Ambiente pré-configurado
- Escalabilidade automática
- Atualizações gerenciadas
- Foco em produtividade

### Responsabilidades

Cliente:
- Código e lógica da aplicação

Provedor:
- Infraestrutura
- Sistema operacional
- Runtime
- Banco de dados (quando gerenciado)

### Exemplos

- Heroku
- Google App Engine
- Azure App Services

---

## SaaS – Software as a Service

Software pronto entregue via navegador ou aplicativo.

### Características

- Acesso direto
- Atualizações automáticas
- Infraestrutura totalmente gerenciada

### Responsabilidades

Cliente:
- Uso da aplicação
- Gestão dos dados inseridos

Provedor:
- Aplicação completa
- Infraestrutura
- Segurança e manutenção

### Exemplos

- Gmail
- Zoom
- Google Docs
- Salesforce
