WsusDashboard 📊
O WsusDashboard é uma ferramenta client-side leve e moderna para a visualização e análise de relatórios de atualização do Windows Server Update Services (WSUS). Ela permite consolidar múltiplos arquivos (CSV ou Excel) em um painel interativo inspirado no design do Microsoft Azure.

🚀 Funcionalidades
Consolidação Multiarquivo: Suporte para carregar até 15 arquivos simultaneamente, unificando os dados em um único dashboard.

Compatibilidade Inteligente:

Lê arquivos .csv, .xls e .xlsx.

Algoritmo de busca automática por colunas (Computer Name, Status, Approval).

Suporte específico para extração automática da aba Sheet3 (padrão de exportação de alguns sistemas de automação).

Visualização de Dados:

Cards de resumo com total de máquinas e pendências.

Gráfico de barras horizontais dinâmico (via Chart.js) para distribuição de status.

Alerta crítico visual quando há máquinas com status diferente de "Installed".

Foco em Resolução: Tabela detalhada listando apenas as máquinas que exigem atenção (Not Installed, Pending Reboot, etc.).

Privacidade Total: O processamento é feito 100% no navegador. Nenhum dado é enviado para servidores externos.

🛠️ Tecnologias Utilizadas
Frontend: HTML5, CSS3 (Fluent Design / Azure UI), JavaScript (ES6+).

Gráficos: Chart.js para visualização de dados.

Parsing de Dados: * PapaParse para processamento de CSV.

SheetJS (XLSX) para leitura de planilhas Excel.

📂 Como Utilizar
Exportação: Exporte o relatório de status de máquinas do seu console WSUS ou via PowerShell/Apps Script em formato CSV ou Excel.

Upload: Abra o WsusDashboard.html em qualquer navegador moderno e selecione os arquivos desejados.

Análise: * Confira o gráfico para identificar gargalos de atualização.

Utilize a tabela de pendências para identificar quais máquinas precisam de intervenção manual ou reinicialização.

🏗️ Estrutura do Projeto
O projeto é entregue em um arquivo único (Single Page Application), facilitando a portabilidade em ambientes de TI restritos:

Plaintext
WsusDashboard.html  # Contém toda a lógica, estilos e estrutura.
✒️ Autor
Desenvolvido por um profissional de Systems Administration & IT focado em automação e monitoramento de infraestrutura de alto desempenho.

Dicas para o seu Repositório:
Screenshots: Tire um print do dashboard funcionando com dados fictícios e adicione ao repositório.

GitHub Pages: Como o projeto é estático (HTML/JS), você pode ativar o GitHub Pages nas configurações para ter uma URL funcional do seu dashboard online.
