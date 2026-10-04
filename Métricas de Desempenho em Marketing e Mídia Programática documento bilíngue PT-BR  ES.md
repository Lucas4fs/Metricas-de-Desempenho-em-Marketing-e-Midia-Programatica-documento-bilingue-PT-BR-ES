# 📚 Métricas de Desempenho em Marketing e Mídia Programática

> Documento bilíngue com métricas, conceitos, fórmulas e interpretação prática em português do Brasil e espanhol.

<a id="selecao-de-idioma"></a>

## 🌐 Seleção de idioma

- [Português BR](#portugues-br)
- [Español ES](#espanol-es)

---

## 🇧🇷 Português BR

<a id="portugues-br"></a>

[↩ Voltar à seleção de idioma](#selecao-de-idioma)

# 📊 Métricas de Desempenho em Marketing e Mídia Programática

> Guia completo com siglas, conceitos, fórmulas e interpretação prática.
> Ideal para consulta rápida, estudos e documentação de projetos.

---

## 📑 Índice

1. [Conceitos-base](#portugues-br-secao-1)
2. [Métricas de Custo](#portugues-br-secao-2)
3. [Métricas de Entrega e Audiência](#portugues-br-secao-3)
4. [Métricas de Engajamento e Conversão](#portugues-br-secao-4)
5. [Métricas de Retorno](#portugues-br-secao-5)
6. [Métricas de Mídia Programática](#portugues-br-secao-6)
7. [Exemplo Numérico](#portugues-br-secao-7)
8. [Qual Métrica Usar por Objetivo](#portugues-br-secao-8)
9. [Cuidados Importantes](#portugues-br-secao-9)
10. [Apêndice: Impressão x Visualização por Plataforma](#portugues-br-secao-10)

---

<a id="portugues-br-secao-1"></a>
## 1. Conceitos-base

| Conceito | Definição |
|---|---|
| **Impressão** | Anúncio exibido/entregue uma vez. Métrica de **entrega**, não de atenção. |
| **Clique** | Usuário clicou no anúncio. |
| **Sessão/Visita** | Usuário chegou ao site/app. |
| **Conversão** | Ação desejada: compra, lead, cadastro, instalação etc. |
| **Receita** | Valor gerado pelas conversões. |
| **Investimento/Custo** | Quanto foi gasto em mídia. |
| **Margem** | Parte da receita que sobra após custos. Essencial para o ROI real. |

### 🔍 Observação a fundo: o que é uma Impressão?

**Impressão = o anúncio foi entregue/carregado pelo navegador ou app e o sistema contou aquela exibição.**

É como deixar um panfleto na porta da pessoa: ele foi entregue, mas ela pode nem olhar.

**Por que não significa que foi visto?**

A impressão pode ter acontecido quando o anúncio estava:
- Abaixo da dobra, fora da tela;
- Em outra aba/minimizado;
- Pré-carregado, sem aparecer de fato;
- Em um espaço invisível;
- Gerado por robô/tráfego inválido.

**Para contar como visto, usa-se visibilidade (`viewability`):**
- **Display:** 50% dos pixels visíveis por pelo menos **1 segundo**.
- **Vídeo:** 50% visível por pelo menos **2 segundos**.

Isso gera a **Impressão Visível** — métrica usada pelo **vCPM**.

> ⚠️ **Atenção:** "uma vez" significa uma exibição do anúncio, não uma pessoa única.
> - **Alcance** = pessoas únicas.
> - **Frequência** = quantas vezes, em média, cada pessoa viu.

### ✅ Resumo

| Termo | Significado |
|---|---|
| **Impressão** | Anúncio entregue |
| **Visualização** | Anúncio realmente visto (critério mínimo) |
| **CPM** | Paga entrega |
| **vCPM** | Paga entrega visível |

---

<a id="portugues-br-secao-2"></a>
## 2. Métricas de Custo

| Sigla | Nome | Fórmula | Observação |
|---|---|---|---|
| **CPM** | Custo por Mil Impressões | `(Investimento ÷ Impressões) × 1.000` | Métrica clássica de reconhecimento. |
| **vCPM** | CPM Visível | `(Investimento ÷ Impressões visíveis) × 1.000` | Mais justo para marca. |
| **CPC** | Custo por Clique | `Investimento ÷ Cliques` | Usado em busca, social e display. |
| **eCPC** | CPC Efetivo/Médio | `Investimento ÷ Cliques` | CPC médio real. |
| **CPA** | Custo por Ação/Aquisição | `Investimento ÷ Conversões` | Compra, lead, cadastro etc. |
| **eCPA** | CPA Efetivo | `Investimento ÷ Conversões` | CPA realizado na prática. |
| **CPL** | Custo por Lead | `Investimento ÷ Leads` | Geração de leads. |
| **CPQL** | Custo por Lead Qualificado | `Investimento ÷ Leads qualificados` | Lead validado por CRM/vendas. |
| **CPI** | Custo por Instalação | `Investimento ÷ Instalações` | Muito usado em aplicativos. |
| **CPV** | Custo por Visualização | `Investimento ÷ Visualizações` | Pode ser visualização de vídeo ou visita. |
| **CPCV** | Custo por Visualização Completa | `Investimento ÷ Visualizações completas` | Vídeo assistido até o fim. |
| **CPO** | Custo por Pedido | `Investimento ÷ Pedidos` | Comércio eletrônico. |
| **CPS** | Custo por Venda | `Investimento ÷ Vendas` | Similar ao CPA para venda. |

---

<a id="portugues-br-secao-3"></a>
## 3. Métricas de Entrega e Audiência

| Sigla | Nome | Fórmula | Observação |
|---|---|---|---|
| **Impressões** | — | — | Volume total de exibições. |
| **Alcance** | Alcance | — | Pessoas únicas impactadas. |
| **Frequência** | Frequência | `Impressões ÷ Alcance` | Quantas vezes a mesma pessoa viu. |
| **SOV** | Participação de Voz | `Sua participação ÷ total do mercado` | Espaço publicitário ocupado. |
| **Visibilidade** | Visibilidade | `(Impressões visíveis ÷ Impressões) × 100` | Padrão IAB: display 50%/1s; vídeo 50%/2s. |
| **TCC** | Taxa de Conclusão de Vídeo | `(Visualizações completas ÷ Inícios) × 100` | Taxa de conclusão do vídeo. |
| **TTV** | Taxa de Transferência de Visualização | `(Visualizações ÷ Impressões) × 100` | Taxa de visualização em vídeo. |
| **Quartis** | Q1, Q2, Q3, Q4 | `25%, 50%, 75%, 100%` | Até onde o usuário assistiu. |
| **TIV** | Tráfego Inválido | — | Tráfego inválido: robôs, fraude etc. |

---

<a id="portugues-br-secao-4"></a>
## 4. Métricas de Engajamento e Conversão

| Sigla | Nome | Fórmula | Observação |
|---|---|---|---|
| **TCC** | Taxa de Cliques | `(Cliques ÷ Impressões) × 100` | Atratividade do anúncio. |
| **TCV** | Taxa de Conversão | `(Conversões ÷ Cliques ou Sessões) × 100` | Sempre veja a base: clique ou sessão. |
| **Taxa de Engajamento** | Taxa de Engajamento | `(Interações ÷ Impressões) × 100` | Curtidas, comentários, compartilhamentos etc. |
| **Taxa de Rejeição** | Taxa de Rejeição | `(Sessões sem interação ÷ Total de sessões) × 100` | Página não prendeu o usuário. |
| **Tempo na Página** | — | — | Quanto tempo o usuário ficou. |
| **CVV** | Conversão por Visualização | Conversão após ver o anúncio, sem clicar | Importante em display/vídeo. |
| **CVC** | Conversão por Clique | Conversão após clicar no anúncio | Atribuição direta. |

---

<a id="portugues-br-secao-5"></a>
## 5. Métricas de Retorno

| Sigla | Nome | Fórmula | Observação |
|---|---|---|---|
| **ROAS** | Retorno sobre Gasto em Anúncios | `(Retorno com anúncios pagos ÷ Custos com anúncios pagos) × 100 (por cento)` | Ex.: ROAS 5 = R$5 de receita por R$1 gasto. Ignora margem. |
| **ROI** | Retorno sobre Investimento | `(Ganho − Custo) ÷ Custo × 100` | Se usar lucro: `(Lucro ÷ Investimento) × 100`. |
| **LTV** | Valor Vitalício do Cliente | Receita total esperada do cliente | Pode ser de receita ou margem. |
| **CAC** | Custo de Aquisição de Cliente | `Investimento total em aquisição ÷ Novos clientes` | Quanto custa conquistar um cliente. |
| **AOV** | Ticket Médio | `Receita ÷ Pedidos` | Valor médio por pedido. |
| **ACOS** | Custo de Publicidade sobre Vendas | `(Custo de publicidade ÷ Receita de vendas) × 100` | Muito usado em Amazon. |
| **TACOS** | Custo Total de Publicidade sobre Vendas | `(Custo total de publicidade ÷ Receita total) × 100` | Inclui mídia e outros custos. |
| **Payback** | Retorno do Investimento | Tempo para recuperar o CAC | Quanto tempo leva para o cliente se pagar. |

### ⚖️ ROAS x ROI

| Métrica | O que mede | Fórmula |
|---|---|---|
| **ROAS** | Retorno sobre gasto em mídia | `Receita ÷ Investimento em mídia` |
| **ROI** | Retorno sobre investimento total | `Lucro ÷ Investimento` |

> 💡 Um ROAS alto pode esconder prejuízo se a margem for baixa.

---

<a id="portugues-br-secao-6"></a>
## 6. Métricas de Mídia Programática

| Termo | Significado |
|---|---|
| **RTB** | Compra em Tempo Real: leilão em tempo real. |
| **DSP** | Plataforma do Lado da Demanda: plataforma de compra de mídia. |
| **SSP** | Plataforma do Lado da Oferta: plataforma de venda de mídia. |
| **Bolsa de Anúncios** | Mercado onde DSPs e SSPs negociam. |
| **Solicitação de Lance** | Solicitação de lance enviada ao DSP. |
| **Resposta de Lance** | Resposta do DSP com lance e criativo. |
| **Taxa de Vitória** | `(Leilões ganhos ÷ Lances enviados) × 100` |
| **Preço Mínimo** | Preço mínimo aceito pelo veículo. |
| **Preço de Fechamento** | Preço final pago no leilão. |
| **Taxa de Preenchimento** | `(Anúncios entregues ÷ Solicitações) × 100` |
| **eCPM** | Receita ou custo por mil impressões. |
| **Leilão Aberto** | Leilão aberto. |
| **Mercado Privado** | Leilão privado. |
| **Acordo Preferencial** | Acordo preferencial, preço fixo sem garantia total. |
| **Programático Garantido** | Compra programática garantida. |
| **CVV** | Conversão por Visualização. |
| **Atribuição** | Último clique, primeiro clique, linear, baseada em dados etc. |
| **Incrementalidade/Efeito** | Mede o impacto causal real da campanha. |
| **Limite de Frequência** | Limite de impressões por usuário. |
| **Otimização do Caminho de Compra** | Otimização do caminho de compra. |
| **Segurança de Marca** | Evitar conteúdo inadequado. |

---

<a id="portugues-br-secao-7"></a>
## 7. Exemplo Numérico

**Campanha:**
- Investimento: `R$ 5.000`
- Impressões: `1.000.000`
- Cliques: `5.000`
- Vendas: `100`
- Receita: `R$ 25.000`

**Cálculos:**

| Métrica | Cálculo | Resultado |
|---|---|---|
| **CPM** | `5.000 ÷ 1.000.000 × 1.000` | **R$ 5** |
| **TCC** | `5.000 ÷ 1.000.000 × 100` | **0,5%** |
| **CPC** | `5.000 ÷ 5.000` | **R$ 1** |
| **TCV** | `100 ÷ 5.000 × 100` | **2%** |
| **CPA** | `5.000 ÷ 100` | **R$ 50** |
| **ROAS** | `25.000 ÷ 5.000` | **5** |
| **ROI** (margem 40%) | Lucro bruto = R$ 10.000 → `(10.000 − 5.000) ÷ 5.000 × 100` | **100%** |

---

<a id="portugues-br-secao-8"></a>
## 8. Qual Métrica Usar por Objetivo

| Objetivo | Métricas recomendadas |
|---|---|
| **Reconhecimento** | CPM, vCPM, alcance, frequência, visibilidade, TCC |
| **Consideração** | TCC, CPC, CPV, tempo de atenção, engajamento |
| **Conversão** | CPA, CPL, TCV, ROAS, ROI, CAC |
| **Retenção/Relacionamento** | LTV, CAC, taxa de cancelamento, payback |

---

<a id="portugues-br-secao-9"></a>
## 9. Cuidados Importantes

1. **ROAS não é lucro.** Sem margem, você pode escalar campanha que dá prejuízo.
2. **Atribuição muda tudo.** Último clique supervaloriza fundo de funil.
3. **Métrica de vaidade x métrica acionável.** Impressões e cliques não bastam.
4. **CPV pode significar coisas diferentes.** Confirme se é visualização de vídeo ou visita.
5. **Referências de mercado variam** por setor, canal, país e formato.
6. **Privacidade e cookies** afetam mensuração. Incrementalidade e MMM ganham espaço.

---

<a id="portugues-br-secao-10"></a>
## 10. Apêndice: Impressão x Visualização por Plataforma

### 📱 Meta (Instagram)

| Métrica | Definição |
|---|---|
| **Impressão** | Anúncio entregue/carregado no feed. |
| **Visualização** | Desde abr/2025, a Meta unificou as métricas. "Visualizações" substituiu Impressões, Reproduções e Visualizações de Vídeo no painel orgânico. |
| **Critério técnico** | O vídeo precisa ser reproduzido por pelo menos **1 milissegundo**. Na prática, qualquer "passada" rápida pelo vídeo no feed já conta como visualização. |
| **Conclusão** | No Instagram, **Visualização = exibição**, não atenção real. Os números tendem a ser inflados. |

### 🔍 Google / YouTube

| Métrica | Definição |
|---|---|
| **Impressão** | Miniatura aparece na tela ou anúncio in-stream começa a carregar. |
| **Visualização TrueView** | Conta quando o usuário assiste **30 segundos** (ou o vídeo completo, se menor) **OU** interage com o anúncio. |
| **Anúncios in-feed** | A visualização só é registrada se a miniatura permanecer visível por **mais de 1 segundo** e com **pelo menos 50%** dela na tela. |
| **Conclusão** | No Google/YouTube, **Visualização exige engajamento comprovado**. Números mais rigorosos e representam melhor a atenção real. |

### ⚖️ Comparativo Resumido

| Métrica | Meta (Instagram) | Google (YouTube) |
|---|---|---|
| **Impressão** | Entrega do anúncio | Entrega/carregamento |
| **Visualização** | Exibição (1 ms) | 30s assistidos ou interação |
| **Rigor** | Baixo | Alto |
| **Representa atenção?** | Não necessariamente | Sim, com mais precisão |

### 🏷️ Termos Específicos por Tipo

**Impressão:**
- Impressão (geral)
- Impressão Visível
- Impressão Mensurável
- Impressões In-stream (YouTube)
- Impressões In-feed (YouTube)

**Visualização:**
- Visualizações (Meta/Instagram)
- Visualização TrueView (Google/YouTube)
- Visualização de Vídeo (Meta, histórica: 3 segundos)
- Taxa de Transferência de Visualização (geral)

---

## 📌 Notas Finais

- Este documento é um guia de referência e não substitui a documentação oficial de cada plataforma.
- Definições de métricas podem mudar com o tempo (ex.: Meta unificou "Visualizações" em 2025).
- Sempre valide as definições atuais no **Gerenciador de Anúncios** e na **central de ajuda** de cada plataforma.

---

**Licença:** MIT — use, adapte e compartilhe livremente.
**Contribuições:** Envios de melhorias são bem-vindos.

---

## 🇪🇸 Español ES

<a id="espanol-es"></a>

[↩ Voltar à seleção de idioma](#selecao-de-idioma)

# 📊 Métricas de Rendimiento en Marketing y Medios Programáticos

> Guía completa con siglas, conceptos, fórmulas e interpretación práctica.
> Ideal para consulta rápida, estudios y documentación de proyectos.

---

## 📑 Índice

1. [Conceptos básicos](#espanol-es-secao-1)
2. [Métricas de Coste](#espanol-es-secao-2)
3. [Métricas de Entrega y Audiencia](#espanol-es-secao-3)
4. [Métricas de Interacción y Conversión](#espanol-es-secao-4)
5. [Métricas de Retorno](#espanol-es-secao-5)
6. [Métricas de Medios Programáticos](#espanol-es-secao-6)
7. [Ejemplo Numérico](#espanol-es-secao-7)
8. [Qué Métrica Usar según el Objetivo](#espanol-es-secao-8)
9. [Precauciones Importantes](#espanol-es-secao-9)
10. [Apéndice: Impresión frente a Visualización por Plataforma](#espanol-es-secao-10)

---

<a id="espanol-es-secao-1"></a>
## 1. Conceptos básicos

| Concepto | Definición |
|---|---|
| **Impresión** | Anuncio mostrado/entregado una vez. Métrica de **entrega**, no de atención. |
| **Clic** | El usuario hizo clic en el anuncio. |
| **Sesión/Visita** | El usuario llegó al sitio o la aplicación. |
| **Conversión** | Acción deseada: compra, lead, registro, instalación, etc. |
| **Ingresos** | Valor generado por las conversiones. |
| **Inversión/Coste** | Cuánto se gastó en medios. |
| **Margen** | Parte de los ingresos que queda después de los costes. Esencial para calcular el ROI real. |

### 🔍 Observación detallada: ¿qué es una Impresión?

**Impresión = el anuncio fue entregado/cargado por el navegador o la aplicación y el sistema contabilizó esa visualización.**

Es como dejar un folleto en la puerta de una persona: fue entregado, pero es posible que ni siquiera lo mire.

**¿Por qué no significa que haya sido visto?**

La impresión puede haberse producido cuando el anuncio estaba:
- Debajo del pliegue, fuera de la pantalla;
- En otra pestaña/minimizado;
- Precargado, sin aparecer realmente;
- En un espacio invisible;
- Generado por un bot/tráfico no válido.

**Para contabilizarlo como visto, se utiliza la visibilidad (`viewability`):**
- **Display:** 50 % de los píxeles visibles durante al menos **1 segundo**.
- **Vídeo:** 50 % visible durante al menos **2 segundos**.

Esto genera la **Impresión Visible**, métrica utilizada por el **vCPM**.

> ⚠️ **Atención:** «una vez» significa una visualización del anuncio, no una persona única.
> - **Alcance** = personas únicas.
> - **Frecuencia** = cuántas veces, en promedio, vio el anuncio cada persona.

### ✅ Resumen

| Término | Significado |
|---|---|
| **Impresión** | Anuncio entregado |
| **Visualización** | Anuncio realmente visto (criterio mínimo) |
| **CPM** | Paga por la entrega |
| **vCPM** | Paga por la entrega visible |

---

<a id="espanol-es-secao-2"></a>
## 2. Métricas de Coste

| Sigla | Nombre | Fórmula | Observación |
|---|---|---|---|
| **CPM** | Coste por Mil Impresiones | `(Inversión ÷ Impresiones) × 1.000` | Métrica clásica de reconocimiento. |
| **vCPM** | CPM Visible | `(Inversión ÷ Impresiones visibles) × 1.000` | Más justo para las campañas de marca. |
| **CPC** | Coste por Clic | `Inversión ÷ Clics` | Utilizado en búsquedas, redes sociales y display. |
| **eCPC** | CPC Efectivo/Medio | `Inversión ÷ Clics` | CPC medio real. |
| **CPA** | Coste por Acción/Adquisición | `Inversión ÷ Conversiones` | Compra, lead, registro, etc. |
| **eCPA** | CPA Efectivo | `Inversión ÷ Conversiones` | CPA realizado en la práctica. |
| **CPL** | Coste por Lead | `Inversión ÷ Leads` | Generación de leads. |
| **CPQL** | Coste por Lead Cualificado | `Inversión ÷ Leads cualificados` | Lead validado por el CRM o el equipo de ventas. |
| **CPI** | Coste por Instalación | `Inversión ÷ Instalaciones` | Muy utilizado en aplicaciones. |
| **CPV** | Coste por Visualización | `Inversión ÷ Visualizaciones` | Puede ser una visualización de vídeo o una visita. |
| **CPCV** | Coste por Visualización Completa | `Inversión ÷ Visualizaciones completas` | Vídeo visto hasta el final. |
| **CPO** | Coste por Pedido | `Inversión ÷ Pedidos` | Comercio electrónico. |
| **CPS** | Coste por Venta | `Inversión ÷ Ventas` | Similar al CPA para ventas. |

---

<a id="espanol-es-secao-3"></a>
## 3. Métricas de Entrega y Audiencia

| Sigla | Nombre | Fórmula | Observación |
|---|---|---|---|
| **Impresiones** | — | — | Volumen total de visualizaciones. |
| **Alcance** | Alcance | — | Personas únicas impactadas. |
| **Frecuencia** | Frecuencia | `Impresiones ÷ Alcance` | Cuántas veces vio el anuncio la misma persona. |
| **SOV** | Cuota de Voz | `Tu participación ÷ total del mercado` | Espacio publicitario ocupado. |
| **Visibilidad** | Visibilidad | `(Impresiones visibles ÷ Impresiones) × 100` | Estándar IAB: display 50 %/1 s; vídeo 50 %/2 s. |
| **TCC** | Tasa de Finalización de Vídeo | `(Visualizaciones completas ÷ Inicios) × 100` | Tasa de finalización del vídeo. |
| **TTV** | Tasa de Transferencia de Visualización | `(Visualizaciones ÷ Impresiones) × 100` | Tasa de visualización en vídeo. |
| **Cuartiles** | Q1, Q2, Q3, Q4 | `25 %, 50 %, 75 %, 100 %` | Hasta dónde vio el vídeo el usuario. |
| **TIV** | Tráfico No Válido | — | Tráfico no válido: bots, fraude, etc. |

---

<a id="espanol-es-secao-4"></a>
## 4. Métricas de Interacción y Conversión

| Sigla | Nombre | Fórmula | Observación |
|---|---|---|---|
| **TCC** | Tasa de Clics | `(Clics ÷ Impresiones) × 100` | Atractivo del anuncio. |
| **TCV** | Tasa de Conversión | `(Conversiones ÷ Clics o Sesiones) × 100` | Comprueba siempre la base: clic o sesión. |
| **Tasa de Interacción** | Tasa de Interacción | `(Interacciones ÷ Impresiones) × 100` | Me gusta, comentarios, compartidos, etc. |
| **Tasa de Rebote** | Tasa de Rebote | `(Sesiones sin interacción ÷ Total de sesiones) × 100` | La página no retuvo al usuario. |
| **Tiempo en la Página** | — | — | Cuánto tiempo permaneció el usuario. |
| **CVV** | Conversión por Visualización | Conversión después de ver el anuncio, sin hacer clic | Importante en display/vídeo. |
| **CVC** | Conversión por Clic | Conversión después de hacer clic en el anuncio | Atribución directa. |

---

<a id="espanol-es-secao-5"></a>
## 5. Métricas de Retorno

| Sigla | Nombre | Fórmula | Observación |
|---|---|---|---|
| **ROAS** | Retorno sobre el Gasto Publicitario | `(Retorno de los anuncios pagados ÷ Costes de los anuncios pagados) × 100 (por ciento)` | Ej.: ROAS 5 = 5 R$ de ingresos por cada 1 R$ gastado. Ignora el margen. |
| **ROI** | Retorno sobre la Inversión | `(Ganancia − Coste) ÷ Coste × 100` | Si se utiliza el beneficio: `(Beneficio ÷ Inversión) × 100`. |
| **LTV** | Valor Vitalicio del Cliente | Ingresos totales esperados del cliente | Puede calcularse sobre los ingresos o el margen. |
| **CAC** | Coste de Adquisición de Clientes | `Inversión total en adquisición ÷ Nuevos clientes` | Cuánto cuesta captar un cliente. |
| **AOV** | Valor Medio del Pedido | `Ingresos ÷ Pedidos` | Valor medio por pedido. |
| **ACOS** | Coste de Publicidad sobre Ventas | `(Coste de publicidad ÷ Ingresos por ventas) × 100` | Muy utilizado en Amazon. |
| **TACOS** | Coste Total de Publicidad sobre Ventas | `(Coste total de publicidad ÷ Ingresos totales) × 100` | Incluye medios y otros costes. |
| **Payback** | Recuperación de la Inversión | Tiempo para recuperar el CAC | Cuánto tiempo tarda el cliente en generar el retorno de su coste. |

### ⚖️ ROAS frente a ROI

| Métrica | Qué mide | Fórmula |
|---|---|---|
| **ROAS** | Retorno sobre el gasto en medios | `Ingresos ÷ Inversión en medios` |
| **ROI** | Retorno sobre la inversión total | `Beneficio ÷ Inversión` |

> 💡 Un ROAS alto puede ocultar pérdidas si el margen es bajo.

---

<a id="espanol-es-secao-6"></a>
## 6. Métricas de Medios Programáticos

| Término | Significado |
|---|---|
| **RTB** | Compra en Tiempo Real: subasta en tiempo real. |
| **DSP** | Plataforma del Lado de la Demanda: plataforma de compra de medios. |
| **SSP** | Plataforma del Lado de la Oferta: plataforma de venta de medios. |
| **Bolsa de Anuncios** | Mercado donde negocian las DSP y las SSP. |
| **Solicitud de Puja** | Solicitud de puja enviada a la DSP. |
| **Respuesta a la Puja** | Respuesta de la DSP con la puja y el creativo. |
| **Tasa de Victoria** | `(Subastas ganadas ÷ Pujas enviadas) × 100` |
| **Precio Mínimo** | Precio mínimo aceptado por el soporte. |
| **Precio de Cierre** | Precio final pagado en la subasta. |
| **Tasa de Relleno** | `(Anuncios entregados ÷ Solicitudes) × 100` |
| **eCPM** | Ingresos o coste por mil impresiones. |
| **Subasta Abierta** | Subasta abierta. |
| **Mercado Privado** | Subasta privada. |
| **Acuerdo Preferente** | Acuerdo preferente, precio fijo sin garantía total. |
| **Programática Garantizada** | Compra programática garantizada. |
| **CVV** | Conversión por Visualización. |
| **Atribución** | Último clic, primer clic, lineal, basada en datos, etc. |
| **Incrementalidad/Efecto** | Mide el impacto causal real de la campaña. |
| **Límite de Frecuencia** | Límite de impresiones por usuario. |
| **Optimización de la Ruta de Compra** | Optimización de la ruta de compra. |
| **Seguridad de Marca** | Evitar contenido inadecuado. |

---

<a id="espanol-es-secao-7"></a>
## 7. Ejemplo Numérico

**Campaña:**
- Inversión: `5.000 R$`
- Impresiones: `1.000.000`
- Clics: `5.000`
- Ventas: `100`
- Ingresos: `25.000 R$`

**Cálculos:**

| Métrica | Cálculo | Resultado |
|---|---|---|
| **CPM** | `5.000 ÷ 1.000.000 × 1.000` | **5 R$** |
| **TCC** | `5.000 ÷ 1.000.000 × 100` | **0,5 %** |
| **CPC** | `5.000 ÷ 5.000` | **1 R$** |
| **TCV** | `100 ÷ 5.000 × 100` | **2 %** |
| **CPA** | `5.000 ÷ 100` | **50 R$** |
| **ROAS** | `25.000 ÷ 5.000` | **5** |
| **ROI** (margen del 40 %) | Beneficio bruto = 10.000 R$ → `(10.000 − 5.000) ÷ 5.000 × 100` | **100 %** |

---

<a id="espanol-es-secao-8"></a>
## 8. Qué Métrica Usar según el Objetivo

| Objetivo | Métricas recomendadas |
|---|---|
| **Reconocimiento** | CPM, vCPM, alcance, frecuencia, visibilidad, TCC |
| **Consideración** | TCC, CPC, CPV, tiempo de atención, interacción |
| **Conversión** | CPA, CPL, TCV, ROAS, ROI, CAC |
| **Retención/Relación** | LTV, CAC, tasa de cancelación, payback |

---

<a id="espanol-es-secao-9"></a>
## 9. Precauciones Importantes

1. **El ROAS no es beneficio.** Sin margen, puedes escalar una campaña que genera pérdidas.
2. **La atribución lo cambia todo.** El último clic sobrevalora la parte baja del embudo.
3. **Métrica de vanidad frente a métrica accionable.** Las impresiones y los clics no son suficientes.
4. **El CPV puede significar cosas diferentes.** Confirma si se refiere a una visualización de vídeo o a una visita.
5. **Las referencias de mercado varían** según el sector, el canal, el país y el formato.
6. **La privacidad y las cookies** afectan a la medición. La incrementalidad y el MMM están ganando espacio.

---

<a id="espanol-es-secao-10"></a>
## 10. Apéndice: Impresión frente a Visualización por Plataforma

### 📱 Meta (Instagram)

| Métrica | Definición |
|---|---|
| **Impresión** | Anuncio entregado/cargado en el feed. |
| **Visualización** | Desde abril de 2025, Meta unificó las métricas. «Visualizaciones» sustituyó a Impresiones, Reproducciones y Visualizaciones de Vídeo en el panel orgánico. |
| **Criterio técnico** | El vídeo debe reproducirse durante al menos **1 milisegundo**. En la práctica, cualquier desplazamiento rápido por el vídeo en el feed ya cuenta como visualización. |
| **Conclusión** | En Instagram, **Visualización = exposición**, no atención real. Los números tienden a estar inflados. |

### 🔍 Google / YouTube

| Métrica | Definición |
|---|---|
| **Impresión** | La miniatura aparece en pantalla o el anuncio in-stream empieza a cargarse. |
| **Visualización TrueView** | Se contabiliza cuando el usuario ve **30 segundos** (o el vídeo completo, si dura menos) **O** interactúa con el anuncio. |
| **Anuncios in-feed** | La visualización solo se registra si la miniatura permanece visible durante **más de 1 segundo** y ocupa **al menos el 50 %** de la pantalla. |
| **Conclusión** | En Google/YouTube, la **Visualización exige una interacción comprobada**. Los números son más rigurosos y representan mejor la atención real. |

### ⚖️ Comparativa Resumida

| Métrica | Meta (Instagram) | Google (YouTube) |
|---|---|---|
| **Impresión** | Entrega del anuncio | Entrega/carga |
| **Visualización** | Exposición (1 ms) | 30 s vistos o interacción |
| **Rigor** | Bajo | Alto |
| **¿Representa atención?** | No necesariamente | Sí, con mayor precisión |

### 🏷️ Términos Específicos por Tipo

**Impresión:**
- Impresión (general)
- Impresión Visible
- Impresión Medible
- Impresiones In-stream (YouTube)
- Impresiones In-feed (YouTube)

**Visualización:**
- Visualizaciones (Meta/Instagram)
- Visualización TrueView (Google/YouTube)
- Visualización de Vídeo (Meta, histórica: 3 segundos)
- Tasa de Transferencia de Visualización (general)

---

## 📌 Notas Finales

- Este documento es una guía de referencia y no sustituye la documentación oficial de cada plataforma.
- Las definiciones de las métricas pueden cambiar con el tiempo (por ejemplo, Meta unificó «Visualizaciones» en 2025).
- Valida siempre las definiciones actuales en el **Administrador de Anuncios** y en el **centro de ayuda** de cada plataforma.

---

**Licencia:** MIT — úsalo, adáptalo y compártelo libremente.
**Contribuciones:** Las propuestas de mejora son bienvenidas.

