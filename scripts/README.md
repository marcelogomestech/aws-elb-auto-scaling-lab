#  AWS — Elastic Load Balancing e EC2 Auto Scaling

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![EC2](https://img.shields.io/badge/Amazon-EC2-orange)
![ELB](https://img.shields.io/badge/Elastic-Load%20Balancing-blue)
![Auto Scaling](https://img.shields.io/badge/EC2-Auto%20Scaling-green)
![CloudWatch](https://img.shields.io/badge/Amazon-CloudWatch-purple)

##  Sobre o projeto

Laboratório prático realizado durante a formação da **Escola da Nuvem**, com foco em **balanceamento de carga, escalabilidade automática, alta disponibilidade e monitoramento na AWS**.

Neste laboratório foi construída uma arquitetura utilizando **Amazon EC2, Application Load Balancer, EC2 Auto Scaling, VPC, sub-redes privadas e Amazon CloudWatch**.

##  Objetivo

Construir uma arquitetura capaz de:

- Distribuir o tráfego entre múltiplas instâncias EC2;
- Manter a aplicação disponível;
- Aumentar automaticamente a capacidade durante períodos de alta demanda;
- Reduzir a capacidade quando a demanda diminui;
- Monitorar a infraestrutura utilizando o CloudWatch.

##  Serviços AWS utilizados

| Serviço | Utilização |
|---|---|
| Amazon EC2 | Execução das aplicações |
| AMI | Modelo para criação das instâncias |
| Application Load Balancer | Distribuição do tráfego |
| Target Group | Gerenciamento dos destinos |
| Launch Template | Modelo para criação das instâncias |
| EC2 Auto Scaling | Escalabilidade automática |
| Amazon VPC | Rede da aplicação |
| Sub-redes privadas | Hospedagem das instâncias |
| CloudWatch | Monitoramento e alarmes |

##  Arquitetura

A arquitetura utiliza um Application Load Balancer para distribuir as requisições entre instâncias EC2 executadas em sub-redes privadas e diferentes Zonas de Disponibilidade.

O Auto Scaling mantém a quantidade de instâncias de acordo com as regras configuradas.

##  Atividades realizadas

- Criação de uma AMI a partir de uma instância EC2;
- Criação de um Application Load Balancer;
- Criação de um Target Group;
- Criação de um Launch Template;
- Criação de um Auto Scaling Group;
- Configuração de instâncias em sub-redes privadas;
- Configuração de duas Zonas de Disponibilidade;
- Configuração de escalabilidade baseada em utilização de CPU;
- Monitoramento utilizando Amazon CloudWatch;
- Teste de aumento de carga;
- Validação do escalonamento automático.

##  Configuração do Auto Scaling

| Configuração | Valor |
|---|---:|
| Capacidade mínima | 2 |
| Capacidade desejada | 2 |
| Capacidade máxima | 4 |
| Métrica | Utilização média da CPU |
| Target | 50% |

##  Principais aprendizados

Durante o laboratório, pratiquei conceitos de:

- Cloud Computing;
- Alta disponibilidade;
- Balanceamento de carga;
- Escalabilidade horizontal;
- Auto Scaling;
- Health Checks;
- AMI;
- Launch Template;
- VPC;
- Sub-redes;
- Availability Zones;
- CloudWatch.

##  Evidências

As evidências da execução do laboratório estão disponíveis em:

`docs/evidencias/`

##  Formação

**Escola da Nuvem — AWS re/Start**

Laboratório prático: **Escalando e balanceando a carga da sua arquitetura**.

## 👨‍💻 Autor

**Marcelo Gomes**

Análise e Desenvolvimento de Sistemas | Cloud Computing | AWS | Dados

[LinkedIn](https://www.linkedin.com/in/marcelogsouza/)

[GitHub](https://github.com/marcelogomestech)

##  Tecnologias

`AWS` `EC2` `ELB` `ALB` `Auto Scaling` `CloudWatch` `VPC` `AMI` `Linux` `Cloud Computing` `DevOps`
