# 🤖 UiPath: Explorando o Core da Automação (Estudos Introdutórios)

Bem-vindo ao meu repositório de aprendizado em **RPA (Robotic Process Automation)**. Este espaço reúne projetos iniciais e fundamentais desenvolvidos no **UiPath Studio**, focados em consolidar os pilares necessários para construir automações robustas, escaláveis e profissionais.

O objetivo deste portfólio é demonstrar o domínio sobre a arquitetura da ferramenta, dependências e lógica de programação aplicada ao RPA, antes de avançar para estruturas mais complexas como o REFramework.

---

## 🏗️ Fundamentos e Arquitetura Explorados

Nestes projetos, foquei em dominar os componentes que garantem a estabilidade de um robô:

* **Gestão de Dependências:** Configuração e atualização de pacotes NuGet (Excel, Mail, System, UIAutomation) para garantir a compatibilidade e performance das atividades.
* **Modelos de Processos (Workflows):** * **Sequences:** Para fluxos lineares e simples.
    * **Flowcharts:** Para processos com tomadas de decisão complexas e loops lógicos.
    * **State Machines:** Para gestão de estados e controle de transições.
* **Modularização e Reuso:** Criação de componentes isolados e uso da atividade `Invoke Workflow File`, facilitando a manutenção e o reaproveitamento de código.
* **Comunicação entre Fluxos:** Domínio sobre o painel de **Arguments** (In, Out, In/Out) para transferência de dados entre diferentes arquivos `.xaml`.
* **Escopo e Variáveis:** Gerenciamento preciso de tipos de dados (.NET), escopo de variáveis e conversão de tipos (Casting/Parsing).

---

## 🛠️ Stack Tecnológica
* **UiPath Studio** (Community Edition).
* **VB.NET Expressions** (Manipulação de strings, datas e coleções).
* **Excel / Mail / System Activities**.
* **Git** (Versionamento profissional, gestão de histórico e segurança de credenciais com `.gitignore`).

---

## 💼 Sobre o Desenvolvedor
Sou um desenvolvedor especializado em **RPA e Automação de Processos**, com foco em transformar tarefas manuais e repetitivas em fluxos estratégicos de alta eficiência, integrando tecnologia e inteligência artificial para otimizar operações.

**Conecte-se comigo:**
* [LinkedIn](https://www.linkedin.com/in/jabes-christian)
* [GitHub](https://github.com/jabes-christian)
* **Email:** jabescristian08@gmail.com

---

### 💡 Como utilizar este repositório?
Cada pasta representa um projeto independente contendo o arquivo `Main.xaml` e o `project.json` (onde residem as definições de dependências). Para executar, abra o projeto no UiPath Studio e certifique-se de configurar as variáveis de ambiente ou caminhos de pastas locais conforme a necessidade de cada robô.
