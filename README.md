# Solar Calculator by VH | v0.9
Uma ferramenta web portátil desenvolvida para o cálculo rápido, preciso e automatizado de orçamentos e dimensionamento de sistemas de energia solar fotovoltaica.

## Funcionalidades
* **Dimensionamento Bidirecional Dinâmico:** Alterne livremente entre cálculo baseado no consumo mensal (kWh/mês) ou diretamente pela potência de pico (kWp). O sistema ajusta automaticamente os valores em tempo real.
* **Cálculo Automático de Módulos:** Determina instantaneamente a quantidade exata de placas solares necessárias com base na potência informada do painel.
* **Orçamento em Cascata Estruturado:** Computa com precisão taxas progressivas e cumulativas, incluindo custos de equipamentos, instalação unitária, projeto técnico, infraestrutura, markup, reserva de caixa e impostos.
* **Interface Moderna e Responsiva:** Desenvolvida com foco em usabilidade (Dark Mode), otimizada para uso rápido em desktops ou dispositivos móveis.
* **Suporte a PWA (Progressive Web App):** Contém manifesto e registro de *Service Worker* para funcionamento offline.

## Tecnologias Utilizadas
* **HTML5 & CSS3** (Interface limpa, moderna e estilizada em Dark Mode)
* **JavaScript (Vanilla)** (Lógica reativa de cálculo em tempo real)
* **PWA / Service Worker** (Suporte a cache e execução portátil)

## Como Usar
1. Baixe ou abra o arquivo `index.html` do projeto em qualquer navegador web moderno.
2. Na seção **Dimensionamento**, insira o **Consumo Mensal (kWh/mês)** ou a **Potência de Pico (kWp)** desejada. Os campos de consumo diário, potência e número de placas serão calculados automaticamente.
3. Ajuste os parâmetros de eficiência, radiação solar e potência do módulo, caso necessário.
4. Na seção **Custos Diretos**, informe os valores de equipamentos, custo de instalação por placa e taxa do projeto técnico.
5. Personalize as **Taxas em Cascata** (Infraestrutura, Markup, Reserva de Caixa e Impostos) conforme a sua estratégia comercial.
6. Acompanhe o **VALOR TOTAL** atualizado instantaneamente na parte inferior da tela.