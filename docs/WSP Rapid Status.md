# WSP Rapid Status Assessments

The WSP rapid status assessment process relies on an algorithm (i.e., a decision tree implemented 
as computer code), based on the four sets of previously completed integrated status assessments. The algorithm was developed using Classification and Regression Tree (CART) analyses, in combination with common rationale 
or rules extracted from the CU-specific status narratives developed during the WSP integrated status assessments. The resulting algorithm approximates the expert decision-making process used in the integrated status 
assessments. The WSP rapid status assessment approach still requires expert input to prepare data, determine how metrics are calculated, and review resulting statuses, but it automates metric calculation and the 
labour-intensive process of integrating metrics into statuses. We refer to algorithm-derived statuses as WSP Rapid Statuses to differentiate these from WSP Integrated Statuses determined through expert-driven processes.


The WSP Rapid Status approach approximates the expert decision-making processes used in more formal Integrated WSP Status assessments through use of an algorithm (computer-coded decision tree). This algorithm is a set of 
consecutive decision rules that are applied to the WSP metric values available for the CU being assessed. WSP rapid statuses are determined by the specific combination of metrics applied to the CU data, and 
the values of those metrics compared to benchmarks. The WSP Rapid Status Assessment approach can assign a Red, Amber, or Green status, with High, Medium or Low confidence to salmon conservation units (CUs) with applicable data.

To develop and select the WSP rapid status algorithm, we first identified a suite of candidate algorithms based on past WSP integrated assessments. For this we used Classification and Regression Tree (CART) analyses, 
in combination with common rationale or rules extracted from the WSP integrated status assessments. We then evaluated the performance of all candidate algorithms by comparing their respective rapid status outputs to 
WSP integrated statuses assigned in past expert-driven processes. The top-performing algorithm was the Learning Tree 3.


![WSP Rapid Status Algorithm](./assets/images/Rapid status algorithm infographic (full algorithm).png)
*WSP rapid status Learning Tree 3 algorithm. To assess a CU, metric values are compared to thresholds presented at each decision point. Yes or No answers split each path of the decision tree, terminating at WSP rapid status assignments. The different splits are identified as nodes: 1 to 65. Pathway 1 is taken when the CU has no absolute abundance metric values, or these values exist, but the recent generational average is above the upper threshold of 10,000. Pathway 2 is taken when the CU 
has absolute abundance metric values and the recent generational average falls under the upper benchmark of 10,000. AbsAbd: absolute abundance; AbsLBM: absolute abundance lower threshold (1,000 benchmark plus 500 buffer); AbsUBM: absolute abundance upper threshold; Rel LBM: relative abundance lower threshold; Rel UBM: relative abundance upper threshold, which is the upper benchmark for this metric + 10%; LongTrend: is long term trend metric; %Change: percent change metric. High, Medium, or Low confidence ratings are identified for each node.*


<br>

## Three Core Principles of the WSP Rapid Status Approach

1. The first core principle is that WSP CUs were identified and rapid statuses were developed based on conservation biology principles (Mace and Lande 1991; Mace et al. 1992, 2008; Caughley 1994; National 
Research Council (US) Committee on Scientific Issues in the Endangered Species Act 1998; McElhany et al. 2000; Rodrigues et al. 2006), and are aligned with scientific 
peer-reviewed publications (Holtby and Ciruna 2007; Holt 2009; Holt et al. 2009; Holt 2010; Grant et al. 2011; Grant and Pestal 2012; DFO 2015, 2016; Brown et al. 2019; 
Grant et al. 2020). This ensures that Pacific salmon statuses are scientifically objective, consistent, and comparable across CUs. 

2. The second core principle of WSP rapid status assessment is the vetting of data and evaluation of WSP rapid statuses by CU experts. DFO stock assessment leads work in collaboration with Indigenous 
groups, consultants, and others that support or lead salmon stock assessment programs to fine tune the CU data used (determining appropriate escapement sites, years, data treatment, etc.), select 
applicable [WSP metrics](./WSP Indicators and Benchmarks.md), and determine specifications for metric calculations.

3. The final core principle of the WSP rapid status algorithm is continual learning and refinement. This means that data sets and status metrics for each CU will be regularly reviewed and updated, and 
that the rapid status algorithm will be reviewed through on-going work with CU experts. Such experts can identify where decision rules may require revisions if they are not making sense, or where 
additional decision rules may be needed as new CUs are assessed. In any such case, algorithm performance will be tested for overall improvements.

<br>

## Benefits
The WSP rapid status approach has the ability to provide more complete coverage of WSP statuses across CUs, and more frequent updates. Expanding the number of assessed CUs will require input from 
stock assessment experts to prepare input data and review/verify the results. However, overall the time commitment required to assess WSP statuses has been greatly reduced through implementation 
of this algorithm and the data processes that surround it.

WSP Rapid Statuses are uploaded into [DFO's Pacific Salmon Status Scanner](./The Scanner.md) once fully reviewed. The Scanner is an interactive data visualization tool specifically designed for experts to support their work on 
Pacific salmon. 

