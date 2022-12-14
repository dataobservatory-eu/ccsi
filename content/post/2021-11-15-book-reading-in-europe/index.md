---
title: "Percentage of Regional Population Who Reads Books"
subtitle: "A regional statistical indicator about book reading habits in Europe."
date: 2021-11-15T19:00:00+01:00
lastmod: 2021-11-15T19:00:00+01:00
draft: false

authors: ["daniel_antal"]

tags: ["Books", "Reading", "Regional data", "Cultural & Creative Sectors and Industries Observatory"]

summary: "The indicator is created from the Eurobarometer 79.2 survey’s [GESIS datafile](https://search.gesis.org/research_data/ZA5688) using regional subsamples."

project: ""

links:
- icon: twitter
  icon_pack: fab
  name: "@CultDataObs"
  url: https://twitter.com/CultDataObs
- icon: linkedin
  icon_pack: fab
  name: CCSI Observatory
  url: https://www.linkedin.com/company/80644612/
- icon: youtube
  icon_pack: fab
  name: 2-minute introduction
  url: https://www.youtube.com/watch?v=bgp-n55TKCk"
- icon: database
  icon_pack: fas
  name: Dataset
  url: https://zenodo.org/record/5703222#.YZKp8GDMLIV

# Featured image
image:
  caption: "Photo: [Filip Mishevski](https://unsplash.com/@filipthedesigner/)"
  focal_point: "Center"
  preview_only: false

---

The indicator is created from the Eurobarometer 79.2 survey’s [GESIS datafile](https://search.gesis.org/research_data/ZA5688) using regional subsamples. The regional subsamples were recoded to the NUTS 2016 regional boundary definitions with the [regions](https://regions.dataobservatory.eu/) R package. In the larger countries, where only NUTS1 level information was present (for example, in Germany and the United Kingdom), we imputed the NUTS1 territorial average values to the constituent NUTS2 regions.

<td style="text-align: center;">{{< figure src="/img/indicators/eurobarometer_79_2_is_read_book_plot.png" caption="We placed the [authoritative copy with metadata](https://zenodo.org/record/5703222#.YZKp8GDMLIV) on the Zenodo open repository." numbered="false" >}}</td>

A ‘dirty averaging’ was used to create regional averages, with scale national post-stratification weights to an expected value of 1. Al respondents who read at least one book in the previous 12 months were coded to have read a book.

This indicator was used in the 		
Balázs Bodó, Dániel Antal, Zoltán Puha: [Can scholarly pirate libraries bridge the knowledge access gap?](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0242509) An empirical study on the structural conditions of book piracy in global and European academia, in Plos ONE (Published: December 3, 2020.)

{{% callout note %}}
Engage with us on {{< staticref "https://www.linkedin.com/company/80644612/" "newtab" >}}{{< icon name="linkedin" pack="fab" >}}LinkedIn{{< /staticref >}} {{< staticref "https://twitter.com/CultDataObs/" "newtab" >}}{{< icon name="twitter" pack="fab" >}}@CultDataObs{{< /staticref >}} or check out our {{< staticref "https://zenodo.org/communities/ccsi/" "newtab" >}}{{< icon name="database" pack="fas" >}}open data{{< /staticref >}} and {{< staticref "https://github.com/dataobservatory-eu/" "newtab" >}} {{< icon name="code" pack="fas" >}} open repositories, code, tutorials{{< /staticref >}}{{% /callout %}}
