# Levantamento das instalações e operações da Petrobras

**Data-base da consolidação:** 20/07/2026  
**Situação:** levantamento público oficial consolidado  
**Entregável principal:** `outputs/019f8144-5158-7810-afe0-52b865d8fb00/levantamento_completo_operacoes_petrobras_2026-07-20.xlsx`

## Resultado executivo

O inventário mestre contém **152 registros individualizados**, com localização, relação societária ou operacional, situação, capacidade nominal ou instalada, indicador de produção/carga quando divulgado, unidade de medida, data-base e fonte.

| Grupo | Escopo consolidado | Capacidade ou indicador |
|---|---:|---:|
| Refinarias próprias e operadas | 10 | 1,813 milhão bbl/d no Form 20-F 2025 |
| Plataformas marítimas operadas pela Petrobras | 49 | 6.882.102 bbl/d de capacidade nominal de óleo nas 45 unidades que divulgam esse campo |
| Terminais próprios da Transpetro | 35 | 9.412.682 m³ de armazenamento; Mucuripe não possui tanque |
| Processamento de gás no Brasil | 10 linhas individualizadas, incluindo unidades sem processamento e uma hibernada | 108 milhões m³/d no agregado divulgado pelo Form 20-F |
| Regaseificação de GNL | 2 | 40 milhões m³/d |
| Termelétricas sob gestão | 13 | 4.910,3 MW |
| Biodiesel | 3 | 609 mil m³/ano instalados; 500 mil m³/ano nas duas unidades operacionais |
| Fertilizantes | 4 | capacidades mantidas por produto e unidade, sem soma indevida |

## Escopo e critério de completude

A planilha inclui instalações industriais, marítimas, logísticas e energéticas individualizáveis em fontes públicas oficiais da Petrobras, ANP e Transpetro. Mantém separadas:

- capacidade nominal ou instalada;
- produção, carga ou processamento efetivo de 2025;
- ativos próprios, operados, participações minoritárias e operações internacionais;
- ativos operacionais, hibernados, arrendados, em construção ou ainda em exploração.

Não foram tratados como instalações produtivas os escritórios, laboratórios, armazéns genéricos, poços individuais, postos de serviço e blocos exploratórios sem instalação de produção. Lacunas públicas ficaram em branco; não foram preenchidas por inferência.

## Divergências e ressalvas principais

1. A página corporativa de refino informa atualmente **10 refinarias e 1,851 milhão bbl/d**. O Form 20-F 2025 informa **10 refinarias e 1,813 milhão bbl/d**; a soma das linhas arredondadas do próprio relatório resulta em 1,814 milhão bbl/d. O inventário preserva o total auditado reportado, sem distribuir a diferença entre unidades.
2. A ANP relaciona **49 unidades marítimas operadas pela Petrobras** em 02/07/2026. O Form 20-F registra 52 sistemas definitivos, testes de longa duração ou produção antecipada em 31/12/2025. As datas e definições não são idênticas.
3. A base ANP registra **150.000 mil m³/d** de capacidade de gás para a PMXL-1, um valor atípico. O dado foi preservado e marcado para validação antes de qualquer agregação.
4. Algumas fontes corporativas apresentam capacidades autorizadas atuais diferentes da fotografia do Form 20-F. A planilha registra a data-base e a fonte de cada número.
5. Capacidades com unidades diferentes não devem ser somadas.

## Estrutura da planilha

- **Resumo:** totais auditáveis, gráfico e alertas.
- **Inventário:** todas as 152 linhas em formato filtrável.
- **Refinarias:** capacidade, carga média de 2025 e complexidade.
- **Plataformas:** localização geográfica, bacia, campos, lâmina d’água, capacidade de óleo e gás.
- **Gás e energia:** processamento, regaseificação e geração.
- **Logística:** terminais, dutos e frota.
- **Fertilizantes e bio:** nitrogenados, biodiesel e participações petroquímicas.
- **Internacional:** ativos, participações, produção divulgada e estágio.
- **Fontes e critérios:** IDs F-018 a F-029 e regras de leitura.

## Evidências

As fontes públicas foram registradas no catálogo do projeto sob os IDs **F-018 a F-029**. As principais bases são o Form 20-F 2025 da Petrobras, os dados abertos de plataformas da ANP atualizados em 02/07/2026 e o Anuário Estatístico ANP 2026.
