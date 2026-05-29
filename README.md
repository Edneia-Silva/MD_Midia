3. Baixe os datasets nos links acima e salve na pasta `dados/`
4. Execute os notebooks na ordem: **01 → 02 → 03 → 04 → 05**

---

## 🔑 Parâmetros dos Algoritmos
| Algoritmo | Parâmetro | Valor | Justificativa |
|---|---|---|---|
| K-Means | k (clusters) | 4 | Método do Cotovelo |
| K-Means | Silhouette Score | 0,294 | Validação da qualidade |
| Apriori | Suporte mínimo | 10% | Frequência mínima nos domicílios |
| Apriori | Confiança mínima | 60% | P(B\|A) mínima aceitável |
| Apriori | Lift mínimo | > 1,2 | Associação acima do acaso |
| Hierárquico | Critério | Ward | Compatível com K-Means |
| Hierárquico | Concordância | 97,9% | Validação dos clusters |