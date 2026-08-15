# 🛒 Sistema Integrado ERP / CRM Multi-Loja & PDV Web

![Status do Projeto](https://img.shields.io/badge/Status-Em_Desenvolvimento-blue)
![Arquitetura](https://img.shields.io/badge/Arquitetura-Multi--Loja%20%7C%20PWA%20%7C%20Cloud-success)
![Versão](https://img.shields.io/badge/Vers%C3%A3o-1.0.0-informational)

Plataforma de gestão comercial sob medida para automatizar e otimizar as operações das 2 unidades operacionais do **Mercado Ki Joia**. O sistema substitui softwares legados por uma solução web/mobile moderna, centralizando estoque, validades, vendas e inteligência fiscal em nuvem.

---

## 🚀 Principais Módulos do Sistema

### 1. Painel Administrativo Web (Gestão Centralizada)
* **Gestão Multi-Loja:** Visão isolada e consolidada de faturamento e saldo de estoque das 2 unidades.
* **Controle de Validades (PVPS):** Monitoramento inteligente ("Primeiro que Vence, Primeiro que Sai") com alertas preventivos.
* **Entrada Rápida por XML:** Leitura de NF-e de fornecedores com mapeamento *De-Para*, atualização automática do custo médio e entrada de lote/validade sem digitação manual.
* **Logística e Transferência:** Solicitação, bipagem de recebimento e movimentação rastreável de estoque entre as lojas.
* **Motor de Promoções:** Preço por quantidade (atacarejo), ofertas "Leve X Pague Y" e promoções agendadas.
* **DRE Gerencial & Curva ABC:** Análise de DRE simplificado, CMV (Custo das Mercadorias Vendidas) e curva de giro de produtos.

### 2. Frente de Caixa — PDV Web (Alta Velocidade)
* **Operação 100% por Teclado:** Teclas de atalho para máxima performance no atendimento aos clientes.
* **Resiliência e Modo Offline (PWA):** Permite continuar vendendo mesmo com instabilidade ou queda de internet, sincronizando os dados automaticamente assim que a conexão retornar.
* **Emissão Fiscal (NFC-e):** Transmissão automatizada de cupom fiscal via API para a SEFAZ e integração com impressoras térmicas (ESC/POS).
* **Gestão de Caixa & Fechamento Cego:** Controle de sangria, suprimento e auditoria cega para apuração precisa de quebras de caixa.

### 3. Coletor PWA Mobile (Smartphone no Corredor)
* Transformação de smartphones em coletores de dados operacionais utilizando a câmera do celular.
* Realização de inventários, balanços de estoque, auditoria de preços de gôndola e bipagem rápida de vencimentos.

### 4. Clube Ki Joia (CRM & Fidelização)
* Identificação rápida de CPF no PDV.
* Aplicação de preços exclusivos para clientes cadastrados no clube de vantagens.

---

## 🛠️ Stack Tecnológica

* **Frontend (Admin & PDV):** React / TypeScript / Progressive Web App (PWA)
* **Mobile (Coletor):** PWA com suporte à leitura de código de barras via câmera (HTML5 QR Code Scanner)
* **Backend:** Python / Django Ninja
* **Banco de Dados:** PostgreSQL Centralizado
* **Serviço Fiscal:** API Focus NFe (Emissão de NFC-e)
* **Hospedagem & Nuvem:** Cloud VPS (Docker + Nginx)

---

## 📅 Cronograma Geral de Entregas (6 Meses)

| Fase | Prazo | Escopo Principal |
| :--- | :---: | :--- |
| **Fase 1** | Meses 1 e 2 | Banco de Dados Central + Coletor Mobile (PWA) + Módulo de Lotes e Validades (PVPS) |
| **Fase 2** | Mês 3 | Compras via XML + Transferência entre Lojas + Ajustes de Estoque |
| **Fase 3** | Meses 4 e 5 | Frente de Caixa (PDV Web) + Modo Offline + Emissão NFC-e + Impressão Térmica |
| **Fase 4** | Mês 6 | Motor de Descontos + CRM Clube Ki Joia + Relatórios Financeiros/DRE + Go-Live |

---

## 👤 Responsável pelo Desenvolvinento

**Maria Eduarda Claro**  
*Desenvolvedora de Software*  
📱 WhatsApp: [(15) 99742-2080](https://wa.me/5515997422080)  
✉️ E-mail: [eduardaclaro1dev@gmail.com](mailto:eduardaclaro1dev@gmail.com)  

---

*Propriedade intelectual desenvolvida sob medida para o **Mercado**.*