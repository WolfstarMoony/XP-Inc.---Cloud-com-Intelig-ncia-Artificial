### **Principais Modelos de Serviços em Nuvem**

#### **IaaS (Infrastructure as a Service)**
- **O que é:** Aluguel de infraestrutura básica (servidores, armazenamento, rede)
- **Exemplos:** AWS EC2, Azure Virtual Machines, Google Compute Engine
- **Prós:** Controle total sobre OS e aplicações, escalável
- **Contras:** Requer gerenciamento do SO e middleware

#### **PaaS (Platform as a Service)**
- **O que é:** Ambiente para desenvolvimento e deploy de aplicações
- **Exemplos:** Heroku, Google App Engine, AWS Elastic Beanstalk
- **Prós:** Não gerencia infra subjacente, foco no código
- **Contras:** Menos controle sobre configurações

#### **SaaS (Software as a Service)**
- **O que é:** Software pronto para uso via navegador
- **Exemplos:** Gmail, Salesforce, Microsoft 365
- **Prós:** Zero manutenção, acessível de qualquer lugar
- **Contras:** Personalização limitada

#### **BaaS (Backend as a Service)**
- **O que é:** Backend pronto para aplicações móveis/web
- **Exemplos:** Firebase, AWS Amplify, Parse
- **Prós:** Acelera desenvolvimento, autenticação e banco prontos
- **Contras:** Vendor lock-in potencial

#### **FaaS (Function as a Service)**
- **O que é:** Execução de funções sob demanda (serverless)
- **Exemplos:** AWS Lambda, Azure Functions, Google Cloud Functions
- **Prós:** Cobrança por execução, altamente escalável
- **Contras:** Cold starts, limitado por tempo de execução

#### **DBaaS (Database as a Service)**
- **O que é:** Banco de dados gerenciado pelo provedor
- **Exemplos:** MongoDB Atlas, Amazon RDS, Google Cloud SQL
- **Prós:** Backup automático, alta disponibilidade
- **Contras:** Performance pode ser limitada vs. self-hosted

### **Comparação Rápida**
| Tipo  | Controle | Gerenciamento | Exemplo Típico |
|-------|----------|---------------|----------------|
| IaaS  | Alto     | Infra + OS    | Servidor Cloud |
| PaaS  | Médio    | Apenas App    | Plataforma Dev |
| SaaS  | Baixo    | Nenhum        | Webmail        |

**Analogia:**  
- IaaS = Alugar terreno bruto (você constrói a casa)  
- PaaS = Alugar casa sem mobília (só coloca seus objetos)  
- SaaS = Alugar casa mobiliada (só entra e usa)