# TaxReform | Calculadora IBS/CBS — Simples Nacional Pro

Simulador técnico e estratégico para tomada de decisão no Simples Nacional frente à Reforma Tributária sobre o Consumo (**Emenda Constitucional nº 132/2023**, **Lei Complementar nº 123/2006**, **PLP 68/2024** e **Resolução CGSN nº 186/2026**).

---

## 🎯 Principais Funcionalidades

1. **Alíquota da CBS (Federal) Totalmente Editável**:
   - Como a alíquota final da CBS ainda depende de fixação pelo Senado Federal e Comitê Gestor, a calculadora possui um módulo dedicado onde o usuário pode **digitar qualquer alíquota** (ex: `7.0%`, `8.5%`, `8.8%`, `9.5%`, etc.) ou usar o slider interativo.
   - Botões de presets rápidos (`7.5% Mínimo`, `8.8% Estimativa Oficial Fazenda`, `9.5% Conservador`).
   - Alíquota do IBS (Subnacional) também ajustável, com exibição instantânea do **IVA Total (CBS + IBS)**.

2. **Cálculo Oficial da LC 123/2006 por RBT12**:
   - Eliminação de alíquotas estáticas fixas.
   - Tabelas completas dos **Anexos I, II, III, IV e V** com alíquotas nominais e parcelas a deduzir oficiais.
   - Aplicação da fórmula legal da alíquota efetiva:  
     $$\text{Alíquota Efetiva} = \frac{(\text{RBT12} \times \text{Alíquota Nominal}) - \text{Parcela a Deduzir}}{\text{RBT12}}$$
   - Partição exata dos tributos substituídos (PIS, COFINS, ICMS ou ISS) conforme cada faixa e anexo.

3. **Cronograma Escalonado da Transição (2026 a 2033)**:
   - **2026 (Ano Teste)**: CBS 0,9% e IBS 0,1% compensáveis com PIS/Cofins.
   - **2027 (CBS Plena)**: Entrada da CBS integral e extinção do PIS/Cofins; ICMS e ISS continuam no DAS.
   - **2029 a 2032 (Transição do IBS)**: Redução gradual do ICMS/ISS à proporção de 1/10 ao ano.
   - **2033 (Regime Pleno Definitivo)**: Vigência integral do IVA Dual (~26,5%).

4. **Métrica de Ponto de Equilíbrio (Break-Even de Vendas B2B)**:
   - Apuração do percentual exato de faturamento com clientes PJ necessário para cobrir o sobrecusto fiscal e operacional do modelo híbrido.
   - Barra visual de status em relação à meta de break-even.

5. **Custo Oculto de Conformidade**:
   - Campo para estimar honorários contábeis e sistemas de TI para entrega de obrigações acessórias (SPED, auditoria de XMLs, conciliação de débito/crédito).

6. **Compartilhamento de Simulações (URL State)**:
   - Todos os dados inseridos (ano, CBS, IBS, anexo, receita, RBT12, B2B, compras, folha e custos) são sincronizados em tempo real nos parâmetros da URL.
   - Botão **"Compartilhar"** copia o link direto para a área de transferência.

7. **Impressão e Emissão de Parecer Técnico (PDF)**:
   - Estilos `@media print` otimizados para gerar um relatório executivo formal, pronto para anexar a propostas de consultoria tributária.

8. **Proteção de Código com Texto Copiável**:
   - Bloqueio de atalhos comuns de inspeção (`F12`, `Ctrl+Shift+I`, `Ctrl+Shift+J`, `Ctrl+Shift+C`, `Ctrl+U`, `Ctrl+S`).
   - Botão direito inteligente: bloqueia a inspeção se não houver seleção, mas **permite a cópia de qualquer texto ou valor selecionado**.
   - Atalho `Ctrl + C` totalmente mantido e operacional.

---

## 🚀 Como Publicar no GitHub Pages

Para atualizar o seu site no GitHub Pages (`silvioalbqrq/TaxReform`):

1. Clone o repositório existente ou abra a pasta local:
   ```bash
   git clone https://github.com/silvioalbqrq/TaxReform.git
   cd TaxReform
   ```
2. Substitua o arquivo `index.html` pelo novo arquivo gerado em:
   `taxreform-simples-nacional/index.html`
3. Faça o commit e o push para o GitHub:
   ```bash
   git add index.html README.md
   git commit -m "feat: Aliquota da CBS customizavel, calculo RBT12 e protecao"
   git push origin main
   ```
4. O GitHub Pages atualizará o site automaticamente em:  
   `https://silvioalbqrq.github.io/TaxReform/`
