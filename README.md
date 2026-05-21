# Azure AI Search vs SQL Server 2025 Hyperscale

Interactive cost-crossover, feature-comparison, and migration-playbook artifact comparing **Azure AI Search** against **SQL Server 2025 Hyperscale** with native vector + semantic search.

**Live site:** https://patmeh1.github.io/sql2025vsAISearch/

## Tabs

1. **Cost  adjust your workload (partitions Crossover replicas, YoY growth, SQL vCores, reservation, one-time build cost, ongoing ops overhead) and see year-by-year cost and break-even crossover in real time.** 
2. **Feature  capability parity matrix across 18 dimensions.comparison** 
3. **Migration  what you have to build to replace AI Search with SQL 2025, including what does NOT port, eng-week estimates, and a 15-step playbook.steps** 
4. **Pricing  authoritative price tables pulled from the Azure Retail Prices API (East US, May 2026).reference** 

## PDF exports

- [Full artifact (all tabs)](./ai-search-vs-sql2025_full.pdf)
- [Cost crossover only](./ai-search-vs-sql2025_cost.pdf)
- [Feature comparison only](./ai-search-vs-sql2025_features.pdf)
- [Migration playbook only](./ai-search-vs-sql2025_migration.pdf)
- [Pricing reference only](./ai-search-vs-sql2025_pricing.pdf)

## Pricing sources

- Azure AI Search SKU prices: `https://prices.azure.com/api/retail/prices?$filter=serviceName eq 'Azure Cognitive Search' and armRegionName eq 'eastus'`
- Azure SQL Hyperscale prices: `https://prices.azure.com/api/retail/prices?$filter=serviceName eq 'SQL Database' and armRegionName eq 'eastus' and contains(productName,'Hyperscale')`

All figures are PAYG retail rates as of May 20, 2026. Reservation discounts (1-yr ~35%, 3-yr ~55%) are derived from published reserved-capacity meters in the same API.
