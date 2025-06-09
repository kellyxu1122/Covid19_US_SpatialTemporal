# Covid19_US_SpatialTemporal

## Spatial-Temporal Analysis of COVID-19 Spread Using Static County Characteristics and Dynamic Mobility-Case Correlations

This research investigates the heterogeneous spread of COVID-19 across US counties by examining the relationship between static county characteristics and the dynamic correlation patterns between Google mobility data and lagged/rolling average COVID-19 case data. The study addresses why COVID-19 impacted some areas more severely than others through a novel analytical framework.

## Core Research Focus

### Correlation Pattern Analysis
Computing time-series correlations between Google mobility indicators (transit, workplace, grocery) and lagged/rolling average COVID-19 case data for each county.

### Static-Dynamic Relationship Modeling
Investigating how static county characteristics (demographics, healthcare resources, climate, socioeconomic factors) predict the strength and direction of mobility-case correlations.

### Heterogeneity Assessment
Quantifying regional variations in COVID-19 transmission patterns and their relationship to underlying county characteristics.

## Key Research Areas

### Time-Series Correlation Analysis
- Computing rolling correlations between mobility trends and 14-day rolling average case data
- Analyzing lag structures between mobility changes and subsequent case patterns
- Identifying temporal patterns in mobility-transmission relationships

### Predictive Modeling of Correlation Patterns
- Using static county features (population density, age demographics, education levels, healthcare capacity, climate) to predict mobility-case correlation strengths
- Developing regression models to explain why certain counties show stronger mobility-transmission relationships
- Identifying which county characteristics amplify or dampen the mobility-case correlation

### Spatial Heterogeneity Analysis
- Mapping correlation patterns across geographic regions
- Investigating clustering of similar correlation behaviors among counties with shared characteristics
- Analyzing urban vs. rural differences in mobility-transmission dynamics

## Methodological Innovation

### Two-Stage Analysis
First computing county-specific correlations between mobility and case data, then using these correlations as dependent variables predicted by static county characteristics.

### Temporal Dynamics
Incorporating various lag structures (1-day, 14-day) to capture realistic transmission delays.

### Multi-Modal Integration
Combining epidemiological time series, behavioral mobility data, and socio-demographic static variables.

## Visualization

![image](https://github.com/user-attachments/assets/09270540-2b4a-482d-a103-bb70a2fe2a95)
![image](https://github.com/user-attachments/assets/2a163ce9-64b1-4413-876f-832eaff51da4)
![image](https://github.com/user-attachments/assets/d2109405-c35f-4c70-b7e9-df2954019892)

## Dataset Summary

We analyzed **2.7 million records** from **3,142 U.S. counties**, combining:
- COVID-19 case data
- Mobility patterns
- Demographics  
- Healthcare resources

After removing **75,457 incomplete records**, we examined relationships between community characteristics and COVID outcomes. Our regression analysis revealed significant interactions between factors, showing that COVID's impact depended on combinations of vulnerabilities, not single factors alone.

## Key Research Findings

The virus taught us that:
- **Geography doesn't determine destiny**
- **Community response matters more than individual action**
- **Inequality isn't just unfair—it's deadly**

## Why This Matters to the Real World

These key insights help us better understand how to plan for future health emergencies. COVID-19 didn't affect all counties at the same level, and that tells us a few important things:

1. We cannot use **only one factor** to decide where the risk is high (like population density)
2. Vulnerable groups, like **elderly people** need more support
3. **Healthcare and behavioral** factors need to be taken into consideration together. Even with good hospitals, the risk cannot be stopped if people keep moving
4. Policies should be made based on **real data**, not just on assumptions

## Key Lessons for Future Pandemic Preparedness

The data from America's COVID experience sends a clear message:
- **Pandemics don't create inequalities. They reveal them.**
- **They don't cause communities to fail. They show which ones were already failing.**
- **They don't discriminate. But our systems do.**

## Conclusion

This research shows that the spread of COVID-19 is influenced by many factors and no single variable can completely explain it. We need to look at how factors **work together**: mobility, age, population and healthcare.

Our conclusion is clear: In the future, we need data-driven strategies that care for vulnerable people and recognize the combined effects of behavioral and structural factors.

## Future Implications

As Singapore and Hong Kong battle new surges in 2025, as the world signs pandemic treaties, as new variants emerge—these lessons from America's COVID experience become more vital than ever.

The next pandemic is coming. When it arrives, will we remember these lessons? Will we protect our vulnerable? Will we support those who can't stay home? Will we ensure every community can detect and fight the threat?

**The data tells us what happened. What happens next is up to us.**

## Final Thought

As we write this in May 2025, Singapore battles new variants. Hong Kong implements fresh lockdowns. The WHO's Pandemic Agreement promises better preparation. But promises aren't plans, and plans aren't action.

The question isn't whether another pandemic will come. It's whether we'll apply these lessons when it does.

**Will your community be ready?**

---

*This research provides crucial insights for data-driven pandemic preparedness and understanding the complex interactions between community characteristics and disease transmission patterns.*
