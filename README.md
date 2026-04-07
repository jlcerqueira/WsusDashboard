WsusDashboard 📊
O WsusDashboard é uma ferramenta client-side leve e moderna, desenvolvida especificamente para facilitar o processo de auditoria de segurança mensal em ambientes de TI complexos.

🛡️ Contexto de Auditoria
Esta aplicação nasceu da necessidade crítica de consolidar relatórios de conformidade de 7 servidores WSUS distribuídos no ambiente.

Frequência Mensal: O dashboard é utilizado para gerar a visão consolidada exigida pelas auditorias de segurança, garantindo que o status de atualização de todo o parque tecnológico seja transparente e auditável.

Visão Centralizada: Permite que o administrador de sistemas apresente o estado de saúde das atualizações de múltiplos servidores em uma única interface, economizando horas de compilação manual de dados.

🚀 Funcionalidades Principais
Consolidação em Lote: Suporte para carregar até 15 arquivos simultaneamente (ideal para cobrir os 7 servidores WSUS e redundâncias).

Compatibilidade de Formatos:

Lê arquivos .csv, .xls e .xlsx.

Algoritmo de busca automática por colunas (Computer Name, Status, Approval).

Extração inteligente da aba Sheet3 (padrão de exportação via automação/Apps Script).

Visualização de Conformidade (Compliance):

Cards de resumo com total de máquinas e dispositivos com pendências.

Gráfico dinâmico de distribuição de status via Chart.js.

Alerta Crítico: Destaque visual imediato para máquinas com status diferente de "Installed", facilitando a remediação pré-auditoria.

🛠️ Tecnologias Utilizadas
Frontend: HTML5, CSS3 (Fluent Design / Azure UI), JavaScript (ES6+).

Visualização: Chart.js para gráficos interativos.

Processamento de Dados: * PapaParse para CSV.

SheetJS (XLSX) para planilhas Excel.

📂 Como Utilizar
Exportação: Gere os relatórios de status dos seus 7 servidores WSUS.

Upload: Selecione todos os arquivos no botão de carregamento do WsusDashboard.html.

Apresentação: Utilize os gráficos e a tabela de pendências para demonstrar o nível de conformidade do ambiente na auditoria.

🔒 Segurança e Privacidade
Como o processamento é feito 100% no lado do cliente (browser), os dados sensíveis dos servidores e nomes de máquinas nunca saem da sua rede local ou estação de trabalho, atendendo aos requisitos de sigilo da auditoria de segurança.

<img width="1792" height="839" alt="image" src="https://github.com/user-attachments/assets/2bbd8318-bb69-4578-b466-d3c591eb4638" />
