# RelatorioDevendas 🤖

Processo que manipulação e criação de Relatório de Vendas, explorando os subsWorkflows utilizando UiPath.

## 🛠️ Estrutura do Projeto
- **Main.xaml**: Fluxo principal de execução.
- **CalcularResumo.xaml**: SubWorkflow.
- **GerarResultados.xaml**: SubWorkflow.
- **LerVendas**: Arquivo de configuração e metadados do projeto.
- **Dependencies**:
  - UiPath.Excel.Activities (v3.4.1)
  - UiPath.System.Activities (v26.2.0)
  - UiPath.UIAutomation.Activities (v25.1.x)
- **Entities/Templates**: Pastas de suporte para dados e modelos.
- **Resources**: Pastas com sub-pastas de Input e Output.

## 🚀 Como usar
1. Clone o repositório.
2. Abra o arquivo `project.json` no UiPath Studio.
3. Execute o `Main.xaml`.