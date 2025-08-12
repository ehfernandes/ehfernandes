Zenith ERP - Sistema de Gestão de Stock com IA
Descrição
O Zenith ERP é um sistema de gestão de stock (ERP - Enterprise Resource Planning) desenvolvido como uma aplicação web single-page. Construído com HTML, Tailwind CSS e JavaScript puro, o sistema oferece uma interface moderna e responsiva para a gestão completa de produtos, fornecedores e movimentações de stock. A aplicação foi desenhada para ser intuitiva, robusta e não requer um backend complexo, simulando todas as operações no lado do cliente.

Uma das características de destaque é a integração com a API da Gemini para gerar descrições de produtos de forma inteligente, otimizando o processo de cadastro.

Funcionalidades Principais
O sistema está organizado em várias abas, cada uma com funcionalidades específicas:

Cadastros:

Adicione, edite e remova produtos.

Visualize a lista de produtos com informações essenciais como SKU, stock atual e preço.

Gere QR Codes para cada produto para facilitar a sua identificação.

Campo de Densidade Condicional: Insira a densidade (kg/L) para produtos vendidos por peso ou volume, otimizando os cálculos.

Suprimentos:

Gestão completa de fornecedores (adicionar, editar, remover).

Movimentações:

Registe entradas e saídas de stock.

Filtre as movimentações por tipo, produto e período.

Relatórios:

Gere relatórios detalhados, como Posição de Estoque, Curva ABC e Produtos Abaixo do Mínimo.

Exporte os relatórios para formatos como PDF e CSV.

Dashboards:

Visualize dados de forma interativa através de um dashboard do Power BI incorporado, focado na análise da cadeia de suprimentos e gestão de inventário.

Leitor QR Code:

Utilize a câmara do dispositivo para ler QR Codes e códigos de barras.

Agilize o processo de movimentação de stock ou vincule um código a um produto existente.

Calculadora:

Calculadora de Densidade: Calcule a densidade de um material a partir da sua massa e volume.

Calculadora de Volume: Determine o volume em litros a partir do peso líquido e da densidade de um produto.

Utilizadores:

Adicione, edite e remova utilizadores do sistema.

Defina níveis de permissão (Administrador, Utilizador).

Tecnologias Utilizadas
Frontend:

HTML5

Tailwind CSS

JavaScript (ES6 Modules)

Bibliotecas Externas:

Font Awesome (Ícones)

Chart.js (Gráficos - atualmente não utilizado, mas presente na estrutura)

html5-qrcode (Leitor de QR Code)

jsPDF & jsPDF-AutoTable (Exportação para PDF)

QRCode.js (Geração de QR Codes)

APIs:

Gemini API: Para a geração de descrições de produtos com recurso a Inteligência Artificial.

Como Utilizar
Não é necessária instalação.

Basta abrir o ficheiro index.html num navegador web moderno (como Chrome, Firefox, Edge).

A aplicação irá carregar com dados de exemplo e estará pronta a ser utilizada.

Destaques do Código
Single-Page Application (SPA): A navegação entre as diferentes "abas" é gerida por JavaScript, que mostra e esconde os diferentes módulos (<main>) sem necessidade de recarregar a página.

Simulação de Backend: Todos os dados (produtos, fornecedores, etc.) são armazenados em arrays de JavaScript no início do script, simulando uma base de dados para fins de demonstração.

Component-Based Logic: Embora não utilize um framework, o código está estruturado de forma a separar a lógica de cada funcionalidade (produtos, fornecedores, calculadora, etc.) em blocos distintos.

Interação Dinâmica com o DOM: O sistema manipula o DOM de forma extensiva para renderizar tabelas, abrir modais e atualizar a interface em tempo real com base nas ações do utilizador.
