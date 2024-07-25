# WSP Rapid Status Assessments

The WSP rapid status assessment approach uses an algorithm (i.e., a decision tree implemented as computer code) developed from the four sets of previously completed integrated status assessments. 

The algorithm is a set of consecutive decision rules that were commonly used by experts to assess WSP statuses. The algorithm was built using Classification and Regression Tree (CART) analyses, in combination with common rationale or rules extracted from the CU-specific status narratives from previous WSP integrated status processes. 

The resulting algorithm thus approximates the expert decision-making process to assess WSP statuses. Decision rules are sequentially applied to the [WSP metric values](./WSP Indicators and Benchmarks.md) calculated for each CU being assessed. The algorithm pathway taken by each CU in the year being assessed depends on which metrics are available and how their values compare to the thresholds implemented by the algorithm. At the end of each pathway, the algorithm assigns a Red, Amber, or Green status, with High, Medium or Low confidence.

Confidence is determined based on the metrics used assess status, and their values. Statuses determined using abundance-based metrics (relative abudnance and absolute abundance) are generally associated with higher confidence than those that are assigned using only trend-based metrics (long-term trend and percent change).

The WSP rapid status assessment approach requires expert input to prepare data, determine how metrics are calculated, and review resulting statuses. However, metric calculation, and the labour-intensive process of integrating metrics into statuses are automated, significanltly streamlining the overall process. 


#![WSP Rapid Status Algorithm](./assets/images/Rapid status algorithm infographic (full algorithm).png)
<img src="./assets/images/Rapid status algorithm infographic (full algorithm).png" width="1200" />

*WSP rapid status Learning Tree 3 algorithm. To assess a CU, metric values are compared to thresholds presented at each decision point. Yes or No answers split each path of the decision tree, terminating at WSP rapid status assignments. The different splits are identified as nodes: 1 to 65. Pathway 1 is taken when the CU has no absolute abundance metric values, or these values exist, but the recent generational average is above the upper threshold of 10,000. Pathway 2 is taken when the CU 
has absolute abundance metric values and the recent generational average falls under the upper benchmark of 10,000. AbsAbd: absolute abundance; AbsLBM: absolute abundance lower threshold (1,000 benchmark plus 500 buffer); AbsUBM: absolute abundance upper threshold; Rel LBM: relative abundance lower threshold; Rel UBM: relative abundance upper threshold, which is the upper benchmark for this metric + 10%; LongTrend: is long term trend metric; %Change: percent change metric. High, Medium, or Low confidence ratings are identified for each node.*


<br>

## Three Core Principles of the WSP Rapid Status Approach

1. Methods to identify Conservation Units and assess rapid statuses comply with conservation biology principles ([Mace and Lande 1991; Mace et al. 1992, 2008; Caughley 1994; National 
Research Council (US) Committee on Scientific Issues in the Endangered Species Act 1998; McElhany et al. 2000; Rodrigues et al. 2006](./References.md)), and are aligned with scientific 
peer-reviewed publications ([Holtby and Ciruna 2007; Holt 2009; Holt et al. 2009; Holt 2010; Grant et al. 2011; Grant and Pestal 2012; DFO 2015, 2016; Brown et al. 2019; 
Grant et al. 2020](./References.md)). This ensures that Pacific salmon statuses are scientifically objective, consistent, and comparable across CUs. 

2. Data are vetted and WSP rapid statuses are evaluated by CU experts. DFO stock assessment leads work in collaboration with Indigenous groups, consultants, and others that support or lead salmon stock assessment programs to fine tune the CU data used (determining appropriate escapement sites, years, data treatment, etc.), select applicable [WSP metrics](./WSP Indicators and Benchmarks.md), and determine specifications for metric calculations.

3. The algorithm is continually refined as new information becomes available. This means that data sets and status metrics for each CU will be regularly reviewed and updated, and the rapid status algorithm will be reviewed through on-going work with CU experts. Experts can identify where decision rules may require revision, or where additional decision rules may be needed as new CUs are assessed. In any such case, algorithm performance will be tested for overall improvements.

<br>

## Benefits
The WSP rapid status approach has the ability to provide more complete coverage of WSP statuses across CUs, and can be more frequently updated. Expanding the number of assessed CUs will require input from 
stock assessment experts to prepare input data and review/verify the results. However, overall the time commitment required to assess WSP statuses has been greatly reduced through implementation 
of this algorithm and the data processes that surround it.

WSP Rapid Statuses are uploaded into [DFO's Pacific Salmon Status Scanner](./The Scanner.md) once fully reviewed. The Scanner is an interactive data visualization tool specifically designed for experts to support their work on Pacific salmon. 

