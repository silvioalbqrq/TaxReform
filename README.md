# Calculadora IBS/CBS — Dentro ou Fora do DAS? | Simples Nacional

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/status-active-brightgreen.svg)](https://silvioalbqrq.github.io/IBSCBS-SimplesNacional/)
[![Resolução CGSN](https://img.shields.io/badge/CGSN-186%2F2026-0f172a.svg)](https://www.in.gov.br/)
[![Base Legal LC 214/2025](https://img.shields.io/badge/LC-214%2F2025-2563eb.svg)](https://www.planalto.gov.br/)

Aplicação web interativa para simulação e tomada de decisão estratégica em relação à opção de recolhimento dos novos tributos sobre consumo (**IBS** — Imposto sobre Bens e Serviços e **CBS** — Contribuição sobre Bens e Serviços) por empresas optantes pelo **Simples Nacional**, no contexto da Reforma Tributária brasileira.

---

## 💡 Sobre o Projeto

Com a regulamentação da Reforma Tributária (Lei Complementar nº 214/2025 e Resolução CGSN nº 186/2026), entre **1º e 30 de setembro de 2026**, as empresas optantes pelo Simples Nacional devem tomar uma decisão crucial para o primeiro semestre de 2027:

1. **Manter IBS e CBS dentro do DAS:** Mantém a apuração unificada no regime simplificado.
2. **Optar pelo Modelo Híbrido (Recolher por Fora):** Mantém tributos federais/locais não substituídos no DAS e apura IBS/CBS no regime regular de débito e crédito.

Esta ferramenta realiza a comparação analítica do custo tributário próprio e da transferência de créditos para clientes da cadeia B2B (PJ do Lucro Real e Presumido), indicando para qual lado pende a recomendação de migração ou manutenção no DAS.

---

## ⚡ Principais Funcionalidades

- **Simulação Dinâmica por Perfil de Empresa:**
  - **Atividades/Anexos:** Anexo I (Comércio), Anexo II (Indústria), Anexo III/V (Serviços com cálculo do Fator R) e Anexo IV.
  - **Receita Bruta Mensal:** Projeção contínua e cálculo das faixas efetivas.
  - **Composição da Carteira B2B vs. B2C:** Ajuste do percentual de vendas destinadas a pessoas jurídicas do regime regular.
  - **Crédito de Entradas:** Apuração do aproveitamento de insumos e compras de fornecedores fora do Simples Nacional.
  - **Folha de Pagamento & Encargos:** Análise do Fator R para prestadores de serviços.
- **Painel de Premissas Ajustáveis da Transição (2027):**
  - Ajuste da alíquota de referência estimada do IVA Dual (IBS + CBS em 2027).
  - Ajuste da fração do DAS correspondente aos tributos substituídos.
- **Diagnóstico Automático:**
  - Comparativo do DAS Normal x DAS Reduzido.
  - Cálculo do IBS/CBS Líquido no Regime Híbrido.
  - Análise do diferencial competitivo em vendas B2B via transferência de créditos cheios.
  - Classificação visual do veredito: *Pende para Híbrido*, *Pende para o DAS* ou *Decisão Apertada*.
- **Acessibilidade e Layout Responsivo:** Design corporativo de alta definição, pronto para dispositivos móveis e desktops.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** & **CSS3** (Variáveis CSS, CSS Grid, Flexbox e componentes modernos)
- **JavaScript ES6+** (Cálculos e manipulação reativa da DOM sem dependências externas)
- **Google Fonts** (*Inter*)
- **Font Awesome 6** (Iconografia vetorial)

---

## 🚀 Como Executar ou Publicar

### Visualização Local

1. Clone este repositório:
   ```bash
   git clone [https://github.com/silvioalbqrq/IBSCBS-SimplesNacional.git](https://github.com/silvioalbqrq/IBSCBS-SimplesNacional.git)