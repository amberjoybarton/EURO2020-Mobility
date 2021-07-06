Changes in UK mobility on EURO 2020 match days
================
Amber Barton
06/07/2021

## Rationale

To find the extent to which concerns that crowds of fans celebrating
EURO 2020 will facilitate spread of the SARS-CoV-2 variant are founded.

## Results

**Retail and recreation**

Mobility for retail and recreation was markedly increased in certain
areas of Scotland and Northern Ireland, and as would be expected, in
Brent, the London Borough containing Wembley.

![](Changes-in-mobility-on-Euro-2020-Match-Days_files/figure-gfm/unnamed-chunk-1-1.png)<!-- -->

**Transit stations**

Mobility through transit stations was increased in certain areas of
Scotland, in Brent and in Wrexham.

![](Changes-in-mobility-on-Euro-2020-Match-Days_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

**Work place**

While England saw an increase in mobility to the work place, this was
less the case in Scotland.

![](Changes-in-mobility-on-Euro-2020-Match-Days_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->

## Method

    ## PhantomJS not found. You can install it with webshot::install_phantomjs(). If it is installed, please make sure the phantomjs executable can be found via the PATH variable.

<div id="htmlwidget-59fce8b57999e0b33b20" style="width:384px;height:288px;" class="grViz html-widget"></div>
<script type="application/json" data-for="htmlwidget-59fce8b57999e0b33b20">{"x":{"diagram":"digraph flowchart {\n      # node definitions with substituted label text\n      node [fontname = Helvetica, shape = rectangle]        \n      tab1 [label = \"Downloaded Google Community Mobility Reports up to June\"]\n      tab2 [label = \"Identified UK-based Euro Match Days\"]\n      tab3 [label = \"Normalised each to mobility on the previous 4 days of the same weekday\"]\n      tab4 [label = \"Took the mean of the normalised change in mobility for the match days\"]\n      tab5 [label = \"Merged with county boundary data from Open Geography Portal\"]\n\n      # edge definitions with the node IDs\n      tab1 -> tab2 -> tab3 -> tab4 -> tab5;\n      }","config":{"engine":"dot","options":null}},"evals":[],"jsHooks":[]}</script>

## Caveats

-   Data is not available for July, where any effects would be more
    marked due to semi-finals and finals in Wembley

-   Data provided was in the format of “percentage change from
    baseline”, without providing baseline mobility figures

-   Counties with lower populations could be more subject to random
    fluctuations in mobility
