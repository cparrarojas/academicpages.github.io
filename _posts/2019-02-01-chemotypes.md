---
title: 'Geographical chemotypes'
date: 2019-02-01
permalink: /blog/2019/02/geographical-chemotypes/
excerpt: Visualisations of clustered bacterial metabolite data from the paper [*Focused natural product elucidation by prioritizing high-throughput metabolomic studies with machine learning*](https://www.biorxiv.org/content/10.1101/535781v1).
tags:
  - metabolomics
  - dataviz
---

# Geographical chemotypes

In our paper [*Focused natural product elucidation by prioritizing high-throughput metabolomic studies with machine learning*](https://www.biorxiv.org/content/10.1101/535781v1), we train a gradient boosting model to classify bacterial metabolite data obtained from soil samples into corresponding to *Photorhabdus* or *Xenorhabdus*, and discuss the role played by the host nematodes in providing a living environment to the bacteria, in comparison to abiotic factors.

The interactive visualisations below show the clustered metabolites at different values of the correlation threshold &rho; across samples. For each threshold, one metabolite of each cluster was selected as a feature for the model, while the others were discarded. After identified the best predictor of bacterial genus, we looked into the individual members of its cluster at the lowest correlation threshold. One of these compounds was isolated and its chemical structure determined.

**Note:** Only clusters with 250 or fewer members are displayed.

The full code for the paper can be found [here](https://github.com/cparrarojas/geographical-chemotypes/).

<div>
    <a href="https://plot.ly/~cparrarojas/43/?share_key=CpMIBNzja1Y31bh9roOZst" target="_blank" title="plot from API (6)" style="display: block; text-align: center;"><img src="https://plot.ly/~cparrarojas/43.png?share_key=CpMIBNzja1Y31bh9roOZst" alt="clustered metabolites for intensity data" style="max-width: 100%;width: 800px;"  width="800" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="cparrarojas:43" sharekey-plotly="CpMIBNzja1Y31bh9roOZst" src="https://plot.ly/embed.js" async></script>
</div>

<div>
    <a href="https://plot.ly/~cparrarojas/39/?share_key=VCqtbl7PSO7NwJwiSpN9W0" target="_blank" title="plot from API (4)" style="display: block; text-align: center;"><img src="https://plot.ly/~cparrarojas/39.png?share_key=VCqtbl7PSO7NwJwiSpN9W0" alt="clustered metabolites for AUC data" style="max-width: 100%;width: 800px;"  width="800" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="cparrarojas:39" sharekey-plotly="VCqtbl7PSO7NwJwiSpN9W0" src="https://plot.ly/embed.js" async></script>
</div>

<div>
    <a href="https://plot.ly/~cparrarojas/41/?share_key=XMXq2XC1qKYfCae2nDbFNS" target="_blank" title="plot from API (5)" style="display: block; text-align: center;"><img src="https://plot.ly/~cparrarojas/41.png?share_key=XMXq2XC1qKYfCae2nDbFNS" alt="clustered metabolites for zeroed AUC data" style="max-width: 100%;width: 800px;"  width="800" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="cparrarojas:41" sharekey-plotly="XMXq2XC1qKYfCae2nDbFNS" src="https://plot.ly/embed.js" async></script>
</div>
