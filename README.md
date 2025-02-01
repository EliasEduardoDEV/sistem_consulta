# **Sistema de Consultas Médicas**

## **1. Introdução**
Atualmente, a marcação de consultas médicas enfrenta diversos desafios, como falta de organização, dificuldades no agendamento e problemas de comunicação entre pacientes, médicos e clínicas. Para resolver essa questão, desenvolvi um **Sistema de Consultas Médicas**, estruturado com um banco de dados eficiente.

## **2. O Problema**
Os sistemas tradicionais de agendamento de consultas podem apresentar problemas como:
- Falta de integração entre pacientes, médicos e clínicas.
- Erros na marcação e gestão das consultas.
- Dificuldade no acompanhamento do histórico médico.
- Baixa eficiência na comunicação e confirmação de consultas.

Esses problemas resultam em atrasos, desencontros e insatisfação tanto para os pacientes quanto para os profissionais de saúde.

## **3. A Solução**
O **Sistema de Consultas Médicas** propõe um banco de dados estruturado para facilitar:
- O agendamento e gerenciamento eficiente das consultas.
- A organização dos dados de pacientes e médicos.
- A conexão entre médicos e clínicas.
- O armazenamento do histórico de consultas para fácil acesso.

## **4. Modelo de Banco de Dados**
Para implementar essa solução, desenvolvi um **Modelo Conceitual** e um **Modelo Lógico**, que organizam os dados essenciais para o funcionamento do sistema.

### **4.1. Entidades do Modelo Conceitual**
O sistema conta com as seguintes entidades principais:
- **Paciente:** Armazena os dados dos pacientes.
- **Médico:** Registra informações dos médicos.
- **Consulta:** Relaciona médicos e pacientes, armazenando data, status e tipo de consulta.
- **Clínica:** Contém informações sobre as clínicas onde os médicos atendem.

### **4.2. Relacionamentos**
- Um **Paciente** pode agendar várias **Consultas**, mas uma consulta pertence a apenas um paciente.
- Um **Médico** pode atender várias **Consultas**, mas cada consulta é atendida por um único médico.
- Um **Médico** pode atuar em diversas **Clínicas**, e uma clínica pode contar com vários médicos.

## **5. Implementação do Modelo Lógico**
Para transformar esse conceito em um banco de dados funcional, utilizei o **dbdiagram.io** para estruturar as tabelas e definir as chaves primárias e estrangeiras. O código inclui:
- Definição das entidades com seus atributos e tipos de dados.
- Relacionamentos entre as tabelas utilizando **chaves primárias** e **chaves estrangeiras**.
- Tabelas intermediárias para lidar com relações **N:N**, como a associação entre médicos e clínicas.

## **6. Conclusão**
Com este **Sistema de Consultas Médicas**, garantimos:
✅ Maior organização e eficiência no agendamento.
✅ Facilidade de acesso aos dados dos pacientes e médicos.
✅ Redução de erros e falhas na comunicação.
✅ Melhor experiência tanto para pacientes quanto para profissionais de saúde.

Dessa forma, esse sistema resolve um problema real e melhora a gestão médica de forma prática e eficiente. 




