# How has the number of infant deaths evolved relative to the number of under-five deaths in Fiji between 1960 and 2020?

## Abstract

Using World Bank World Development Indicators (WDI) data, this study examines how infant deaths have evolved relative to under-five deaths in Fiji between 1960 and 2020. These indicators capture the country’s progress in child health, healthcare access, and overall development outcomes. Over the period, both infant and under-five deaths decreased significantly, ending in 2020 at roughly one-third of their 1960 levels. Notably, under-five deaths declined slightly faster than infant deaths, leading to a modest convergence between the two measures by 2020. This pattern reflects overall improvements in child survival, with targeted interventions and health system strengthening reducing mortality more substantially among older children while still maintaining progress for infants.

## 1. Question

How has the number of infant deaths evolved relative to the number of under-five deaths in Fiji between 1960 and 2020?

- **Infant deaths proxy**: Number of infant deaths
- **Under-five deaths proxy**: Number of under-five deaths

## 2. Data

- **Source**: World Bank World Development Indicators (WDI)
- **Indicators**:
  - Number of infant deaths
  - Number of under-five deaths
- **Coverage**: Fiji, 1960–2020
- **Notes**: National-level data only

## 3. Method

1. Filtered the dataset for Fiji and selected the two child mortality indicators.
2. **Extracted relevant columns**: Year, Indicator Name, and Value.
3. Pivoted the dataset to create a chronological comparison of infant and under-five deaths.
4. Produced a dual-line time series plot to visualize the magnitude, trend, and relative convergence of the two indicators over time.

(Analysis is descriptive; no causal inference applied.)

## 4. Results

- **Infant deaths**: Decreased steadily from 1960 to 2020, ending at roughly one-third of the 1960 value.
- **Under-five deaths**: Also declined significantly, slightly faster than infant deaths, leading to modest convergence between the two by 2020.
- **Comparison**: While both measures fell substantially, the faster reduction in under-five deaths indicates relatively greater improvements in survival beyond the first year of life.

(Figure 1. Fiji: Number of Infant vs. Under-Five Deaths, 1960–2020)

(Table 1. Pivoted dataset summary)

## 5. Interpretation

- The decline in both infant and under-five deaths reflects sustained improvements in child health services, immunization coverage, nutrition, and access to clean water and sanitation.
- Faster reductions in under-five deaths suggest that interventions targeting post-infancy child survival — including vaccination programs, nutrition initiatives, and disease control measures — have been particularly effective.
- The modest convergence by 2020 highlights narrowing differences between infant and overall under-five mortality, indicating progress across all early childhood age groups.
- These trends provide evidence of Fiji’s sustained commitment to child health and its progress toward global child survival targets.

## 6. Limitations

- Mortality data are based on national estimates and may be affected by reporting accuracy and historical data gaps.
- The analysis does not account for regional or socioeconomic disparities within Fiji.
- Descriptive trends do not identify causal factors, such as specific health policies, environmental changes, or economic developments.

## 7. Next Steps / Extensions

- Investigate the contribution of specific health interventions — such as vaccination campaigns, maternal health programs, and nutrition initiatives — to observed mortality reductions.
- Disaggregate mortality trends by sex, region, and socioeconomic status to identify equity patterns.
- Compare Fiji’s child mortality trajectory with other Pacific Island nations to contextualize regional health progress.
- Explore correlations between child mortality trends and broader development indicators, such as GDP per capita, education, and access to safe water, to understand drivers of improved survival.
