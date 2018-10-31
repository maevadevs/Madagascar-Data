# Structure

```
- data/instat/
  |--> demography.json
  |   |--> population.national.[year]
  |   |--> population.regional.[region].[year]
  |--> economy.json
  |   |--> import.national.caf.ariary.[year]
  |   |--> import.top_10_src.[country].caf.ariary.[year]
  |   |--> import.top_10_src.[country].net_weight.kg.[year]
  |   |--> export.national.fob.ariary.[year]
  |   |--> export.top_10_dest.[country].fob.ariary.[year]
  |   |--> export.top_10_dest.[country].net_weight.kg.[year]
  |   |--> gdp.[year].ariary.nominal
  |   |--> gdp.[year].ariary.real
  |   |--> gdp.[year].percent_rate.growth
  |   |--> gdp.[year].percent_rate.inflation
  |   |--> gdp.[year].percent_rate.sector.[primary|secondary|tertiary]
  |   |--> new_establishments.regional.[region].[year]
  |   |--> unemployment.percent_rate.regional.[region].[year]
  |   |--> poverty.percent_rate.ppp_below_usd_125.[national|urban|rural].[year]
  |   |--> poverty.percent_rate.ppp_below_usd_200.[national|urban|rural].[year]
  |--> geography.json
      |--> regions_count
      |--> regions_list
      |--> length.km
      |--> width.km
      |--> area.national.km2
      |--> area.regional.[region].km2
```
