# **Reproducible Figures Are More Valuable Than Fancy Figures**

### Scientific figures are analytical outputs that must meet the same standards of rigor, transparency, and reproducibility as the analyses from which they are derived. Unfortunately, current scientific practice often favors visual sophistication over methodological traceability, leading to many published figures that cannot be reliably regenerated from raw data. This weakens confidence in the findings they are intended to support.

### Figures manually refined using graphical design software frequently involve undocumented steps like subjective color selection or manual axis adjustment. While these interventions may enhance appearance, they break the reproducibility chain by severing the explicit connection between the source data and the final output. Once this link is broken, figures become static artifacts, and subsequent corrections or updates often require complete, error-prone reconstruction.

### These practices contribute to broader issues of irreproducibility in science. A landmark *Nature* survey reported that over 90% of researchers believe there is a reproducibility problem, often citing poor documentation and irreproducible workflows (Baker, 2016). When figures lack documented procedures for regeneration, it becomes difficult to verify analytical decisions or confirm that visual summaries accurately reflect the full dataset. Undocumented manual steps obscure critical transformations and statistical summaries, limiting independent verification and weakening the evidentiary value of results.

### Reproducible research frameworks propose that computational results must be accompanied by the code and data necessary for regeneration. Peng (2011) formalized this, proposing reproducibility as a minimum standard in computational science. Within this framework, figures are integral components of the analytical record. A figure that cannot be reproduced from code fails to meet this minimum standard, regardless of its visual quality. Parameterized, script-driven figure generation offers a robust solution by embedding visualization directly within the analytical pipeline. In environments like R, preprocessing, statistical operations, and aesthetic choices are explicitly encoded and version-controlled. Tools such as ggplot2 provide flexibility for creating publication-quality graphics while ensuring full reproducibility (Wickham, 2016). This approach guarantees that figures can be regenerated automatically when data or parameters change, maintaining consistency and traceability.

### This workflow significantly enhances the peer review process. While traditional peer review relies heavily on visual inspection, script-driven figures, accompanied by code allow reviewers to examine data transformations, verify statistical procedures, and reproduce figures under alternative assumptions, aligning peer review more closely with rigorous methodological evaluation. The necessity of reproducible figures is even greater in regulatory and audited research. Regulatory agencies prioritize traceability, consistency, and independent verifiability over purely visual presentation. The successful use of R-based analyses in submissions to the U.S. Food and Drug Administration (FDA) confirms that script-driven workflows are actively encouraged, with transparency and reproducibility as central advantages (R Consortium R Submissions Working Group, 2022). Concerns that script-generated figures are aesthetically inferior are outdated, as modern visualization libraries have narrowed the gap between scientific rigor and visual refinement. Reproducible workflows are also highly efficient, as parameterized scripts can be reused, adapted, and extended with minimal effort (Marwick et al., 2018).

### Ultimately, a figure's scientific value is rooted in its credibility, not its appearance. A modest figure that can be verified and regenerated is more robust than a highly refined image with unclear provenance. As scientific publishing, funding agencies, and regulatory institutions increasingly prioritize transparency, parameterized, script-driven figures are becoming a baseline expectation. Prioritizing reproducibility over aesthetic polish strengthens peer review, supports regulatory compliance, and reinforces trust in scientific evidence.

### **References** 

Baker, M. (2016). *1,500 scientists lift the lid on reproducibility*. Nature, 533, 452–454.

Peng, R. D. (2011). *Reproducible research in computational science*. Science, 334(6060), 1226–1227.

Wickham, H. (2016). *ggplot2: Elegant Graphics for Data Analysis*. Springer.

Marwick, B., et al. (2018). *Packaging data analytical work reproducibly using R (and friends)*. The American Statistician, 72(1), 80–88.

R Consortium R Submissions Working Group. (2022). *R-Based Regulatory Submissions: FDA Pilot Program Results*.

