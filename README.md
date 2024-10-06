# Projeto Odontologia App

## Descrição Geral

O **Odontologia App** é uma solução tecnológica voltada para a melhoria da experiência dos pacientes e a eficiência das práticas odontológicas. O aplicativo oferece funcionalidades para o registro de consultas, monitoramento de hábitos de higiene bucal e integração com análise preditiva, visando a redução de custos e a sustentabilidade do negócio.

## Funcionalidades

### 1. Agenda de Procedimentos e Visitas ao Dentista
- **Registro de Consultas:** Permite que o paciente registre suas visitas ao dentista, como limpezas, extrações e outros procedimentos. O aplicativo calcula o tempo desde a última consulta e envia notificações lembrando o paciente de agendar um novo check-up após um período determinado (ex: 6 meses).
- **Sugestão de Próximas Visitas:** Com base na análise preditiva, o app sugere uma data ideal para o próximo acompanhamento, considerando o histórico do paciente e o risco de problemas futuros.

### 2. Monitoramento dos Hábitos de Higiene Bucal
- **Registro de Escovação:** Permite que o paciente registre manualmente quando escovou os dentes, mantendo um histórico desses registros.
- **Notificações para Lembrar de Escovar os Dentes:** O app envia lembretes em horários específicos para que o paciente não esqueça de escovar os dentes.
- **Relatórios de Hábitos:** Gera relatórios com gráficos mostrando quantas vezes o paciente escovou os dentes por dia, semana ou mês.

### 3. Integração com Análise Preditiva
- **Prevenção de Problemas:** O app integra um modelo preditivo que avalia o risco de desenvolvimento de cáries e gengivites, sugerindo ações preventivas.
- **Histórico do Paciente:** Fornece ao dentista uma visão completa do histórico de higiene bucal e consultas do paciente.

### 4. Funcionalidades Adicionais
- **Personalização:** O paciente pode personalizar o app para receber lembretes em horários específicos.
- **Educação Bucal:** O app oferece dicas sobre saúde bucal, como técnicas de escovação e a importância do uso do fio dental.
- **Integração com Wearables:** Integra-se com dispositivos como smartwatches para enviar notificações e monitorar comportamentos.

## Integrantes do Projeto
- [Gabriel Leal Onodera RM553779](#)
- [Atila Rebolo Moita da Costa RM552650](#)
- [Gabriel Artacho Plasa Moreira RM553527](#)

## Projeto Java

### Descrição

Este projeto é uma aplicação Java desenvolvida com Spring Boot, que visa gerenciar consultas odontológicas e monitorar hábitos de higiene bucal. A aplicação utiliza conceitos de Programação Orientada a Objetos (POO) e JPA para persistência de dados em um banco de dados relacional (Oracle).

### Funcionalidades

- **Registro de Consultas:** Permite ao paciente registrar suas visitas ao dentista.
- **Listagem de Consultas:** O paciente pode listar todas as suas consultas registradas.
- **Notificações:** O app pode enviar notificações ao paciente com base em suas visitas e hábitos de higiene.

## Estrutura do Projeto

│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── exemplo
│   │   │           └── odontologia
│   │   │               ├── OdontologiaApp.java
│   │   │               ├── controller
│   │   │               │   └── ConsultaController.java
│   │   │               ├── model
│   │   │               │   └── Consulta.java
│   │   │               ├── repository
│   │   │               │   └── ConsultaRepository.java
│   │   │               └── service
│   │   │                   └── ConsultaService.java
│   │   └── resources
│   │       ├── application.properties
│   │       └── static
│   └── test
│       └── java
│           └── com
│               └── exemplo
│                   └── odontologia
│                       └── OdontologiaAppTests.java
├── pom.xml

