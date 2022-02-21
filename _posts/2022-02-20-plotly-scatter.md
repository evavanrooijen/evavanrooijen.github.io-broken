---
title: "Welcome to plotly-scatter!"
date: 2022-02-20
categories:
  - Blog
tags:
  - Research
  - Tutorial
---

Hello World, it's not only a map it's also a scatter!

# Scatters are useful for correlation

<div>                        <script type="text/javascript">window.PlotlyConfig = {MathJaxConfig: 'local'};</script>
        <script src="https://cdn.plot.ly/plotly-2.8.3.min.js"></script>                <div id="8492110d-c9ef-46a7-bf38-d141546bd351" class="plotly-graph-div" style="height:100%; width:100%;"></div>            <script type="text/javascript">                                    window.PLOTLYENV=window.PLOTLYENV || {};                                    if (document.getElementById("8492110d-c9ef-46a7-bf38-d141546bd351")) {                    Plotly.newPlot(                        "8492110d-c9ef-46a7-bf38-d141546bd351",                        [{"hovertemplate":"Region=Asia<br>Score=%{x}<br>GDP per capita=%{y}<extra></extra>","legendgroup":"Asia","marker":{"color":"#636efa","symbol":"circle"},"mode":"markers","name":"Asia","orientation":"v","showlegend":true,"x":[3.2030000000000003,4.456,5.082,4.7,5.191,5.43,4.015,5.192,5.886,4.796,5.339,5.285,4.36,4.913,5.653,5.631,6.2620000000000005,5.895,4.3660000000000005,6.4460000000000015,6.007999999999999,5.175],"xaxis":"x","y":[0.1669847328244274,0.2681297709923664,0.3878816793893129,0.273854961832061,0.4909351145038167,0.6860687022900764,0.3602099236641221,0.4441793893129771,0.6331106870229007,0.3645038167938931,0.5825381679389313,0.4522900763358778,0.3387404580152671,0.2127862595419847,0.3229961832061069,0.3850190839694656,0.7499999999999999,0.620706106870229,0.452767175572519,0.6526717557251909,0.5009541984732825,0.353530534351145],"yaxis":"y","type":"scatter"},{"hovertemplate":"Region=Europe & Oceania<br>Score=%{x}<br>GDP per capita=%{y}<extra></extra>","legendgroup":"Europe & Oceania","marker":{"color":"#EF553B","symbol":"circle"},"mode":"markers","name":"Europe & Oceania","orientation":"v","showlegend":true,"x":[4.718999999999999,4.559,7.228,7.246,5.207999999999998,5.323,6.922999999999999,5.386,5.011,5.432,6.046,6.852,7.6,5.893,7.769,6.5920000000000005,4.519,6.985,5.287000000000001,5.757999999999999,7.494,7.021,6.223,5.809,6.1,5.261,5.94,6.149,7.09,6.726,5.529,5.523,7.487999999999999,7.307,5.274,5.718,7.5539999999999985,6.182,5.693,6.07,5.648,5.603,6.198,6.117999999999999,6.354,7.343,7.48,5.4670000000000005,5.247000000000001,4.332,7.053999999999999,6.174],"xaxis":"x","y":[0.4518129770992366,0.4055343511450381,0.6545801526717557,0.6564885496183205,0.4976145038167938,0.5090648854961831,0.6469465648854962,0.4508587786259541,0.5209923664122138,0.5510496183206107,0.6025763358778625,0.6054389312977099,0.6598282442748091,0.5901717557251909,0.6393129770992366,0.6316793893129771,0.4227099236641221,0.655057251908397,0.5634541984732825,0.5729961832061068,0.6583969465648855,0.7151717557251909,0.6173664122137404,0.5596374045801527,0.4208015267175572,0.262881679389313,0.5663167938931297,0.5906488549618321,0.7676526717557252,0.6202290076335878,0.3268129770992367,0.5014312977099236,0.666030534351145,0.6216603053435115,0.4689885496183206,0.6025763358778625,0.7099236641221375,0.575381679389313,0.5825381679389313,0.5543893129770991,0.5644083969465649,0.4790076335877862,0.5944656488549618,0.6001908396946565,0.6135496183206107,0.6617366412213739,0.6927480916030534,0.2352099236641221,0.5019083969465649,0.3912213740458015,0.6359732824427482,0.3554389312977099],"yaxis":"y","type":"scatter"},{"hovertemplate":"Region=Africa & Middle East<br>Score=%{x}<br>GDP per capita=%{y}<extra></extra>","legendgroup":"Africa & Middle East","marker":{"color":"#00cc96","symbol":"circle"},"mode":"markers","name":"Africa & Middle East","orientation":"v","showlegend":true,"x":[5.211,6.199,4.883,3.488,4.587,3.775,5.044,3.083,4.35,3.973,4.812,4.418,4.166,4.2860000000000005,4.799,4.516,4.996,4.534,4.548,4.437,7.138999999999999,4.944,4.9060000000000015,4.509,6.021,5.197,3.802,3.975,5.525,3.933,3.41,4.39,4.49,5.888,5.207999999999998,4.466,4.638999999999999,4.628,5.265,4.6960000000000015,6.374,3.334,6.375,4.681,4.374,4.668,4.722,2.853,4.212,3.462,3.2310000000000003,4.085,4.461,5.372999999999998,4.189,6.825,3.38,4.107,3.663],"xaxis":"x","y":[0.4780534351145038,0.6498091603053435,0.1875,0.4966603053435114,0.1579198473282442,0.0219465648854961,0.2619274809160304,0.0124045801526717,0.1669847328244274,0.1307251908396946,0.3210877862595419,0.0448473282442748,0.4355916030534351,0.1603053435114504,0.5042938931297709,0.1469465648854961,0.2915076335877862,0.1812977099236641,0.5248091603053435,0.4976145038167938,0.6087786259541984,0.2714694656488549,0.3993320610687023,0.2442748091603053,0.7156488549618321,0.4708969465648854,0.2333015267175572,0.0348282442748091,0.4980916030534351,0.1307251908396946,0.0911259541984732,0.1836832061068702,0.2719465648854961,0.5343511450381679,0.3821564885496182,0.0973282442748091,0.4193702290076336,0.0658396946564885,0.33206106870229,0.3134541984732824,0.8034351145038169,0.1712786259541984,0.6693702290076335,0.2146946564885496,0.1278625954198473,0.0,0.4580152671755725,0.1459923664122137,0.3869274809160304,0.295324427480916,0.2270992366412213,0.1312022900763358,0.4394083969465648,0.5644083969465649,0.1583969465648855,0.7170801526717556,0.1369274809160305,0.2757633587786259,0.174618320610687],"yaxis":"y","type":"scatter"},{"hovertemplate":"Region=America<br>Score=%{x}<br>GDP per capita=%{y}<extra></extra>","legendgroup":"America","marker":{"color":"#ab63fa","symbol":"circle"},"mode":"markers","name":"America","orientation":"v","showlegend":true,"x":[6.086,5.779,6.3,7.278,6.444,6.125,7.167000000000002,5.425,6.028,6.252999999999999,6.436,3.597,5.86,5.89,6.595,6.105,6.3210000000000015,5.742999999999999,5.697,6.192,6.892,6.292999999999998,4.707],"xaxis":"x","y":[0.5209923664122138,0.3702290076335877,0.4790076335877862,0.6512404580152672,0.5529580152671756,0.469942748091603,0.4933206106870229,0.4842557251908396,0.4351145038167939,0.3788167938931298,0.3816793893129771,0.1541030534351144,0.3062977099236641,0.3964694656488549,0.5104961832061069,0.3311068702290076,0.5481870229007634,0.4079198473282442,0.4580152671755725,0.5873091603053435,0.6836832061068703,0.5362595419847328,0.4580152671755725],"yaxis":"y","type":"scatter"}],                        {"template":{"data":{"bar":[{"error_x":{"color":"#2a3f5f"},"error_y":{"color":"#2a3f5f"},"marker":{"line":{"color":"#E5ECF6","width":0.5},"pattern":{"fillmode":"overlay","size":10,"solidity":0.2}},"type":"bar"}],"barpolar":[{"marker":{"line":{"color":"#E5ECF6","width":0.5},"pattern":{"fillmode":"overlay","size":10,"solidity":0.2}},"type":"barpolar"}],"carpet":[{"aaxis":{"endlinecolor":"#2a3f5f","gridcolor":"white","linecolor":"white","minorgridcolor":"white","startlinecolor":"#2a3f5f"},"baxis":{"endlinecolor":"#2a3f5f","gridcolor":"white","linecolor":"white","minorgridcolor":"white","startlinecolor":"#2a3f5f"},"type":"carpet"}],"choropleth":[{"colorbar":{"outlinewidth":0,"ticks":""},"type":"choropleth"}],"contour":[{"colorbar":{"outlinewidth":0,"ticks":""},"colorscale":[[0.0,"#0d0887"],[0.1111111111111111,"#46039f"],[0.2222222222222222,"#7201a8"],[0.3333333333333333,"#9c179e"],[0.4444444444444444,"#bd3786"],[0.5555555555555556,"#d8576b"],[0.6666666666666666,"#ed7953"],[0.7777777777777778,"#fb9f3a"],[0.8888888888888888,"#fdca26"],[1.0,"#f0f921"]],"type":"contour"}],"contourcarpet":[{"colorbar":{"outlinewidth":0,"ticks":""},"type":"contourcarpet"}],"heatmap":[{"colorbar":{"outlinewidth":0,"ticks":""},"colorscale":[[0.0,"#0d0887"],[0.1111111111111111,"#46039f"],[0.2222222222222222,"#7201a8"],[0.3333333333333333,"#9c179e"],[0.4444444444444444,"#bd3786"],[0.5555555555555556,"#d8576b"],[0.6666666666666666,"#ed7953"],[0.7777777777777778,"#fb9f3a"],[0.8888888888888888,"#fdca26"],[1.0,"#f0f921"]],"type":"heatmap"}],"heatmapgl":[{"colorbar":{"outlinewidth":0,"ticks":""},"colorscale":[[0.0,"#0d0887"],[0.1111111111111111,"#46039f"],[0.2222222222222222,"#7201a8"],[0.3333333333333333,"#9c179e"],[0.4444444444444444,"#bd3786"],[0.5555555555555556,"#d8576b"],[0.6666666666666666,"#ed7953"],[0.7777777777777778,"#fb9f3a"],[0.8888888888888888,"#fdca26"],[1.0,"#f0f921"]],"type":"heatmapgl"}],"histogram":[{"marker":{"pattern":{"fillmode":"overlay","size":10,"solidity":0.2}},"type":"histogram"}],"histogram2d":[{"colorbar":{"outlinewidth":0,"ticks":""},"colorscale":[[0.0,"#0d0887"],[0.1111111111111111,"#46039f"],[0.2222222222222222,"#7201a8"],[0.3333333333333333,"#9c179e"],[0.4444444444444444,"#bd3786"],[0.5555555555555556,"#d8576b"],[0.6666666666666666,"#ed7953"],[0.7777777777777778,"#fb9f3a"],[0.8888888888888888,"#fdca26"],[1.0,"#f0f921"]],"type":"histogram2d"}],"histogram2dcontour":[{"colorbar":{"outlinewidth":0,"ticks":""},"colorscale":[[0.0,"#0d0887"],[0.1111111111111111,"#46039f"],[0.2222222222222222,"#7201a8"],[0.3333333333333333,"#9c179e"],[0.4444444444444444,"#bd3786"],[0.5555555555555556,"#d8576b"],[0.6666666666666666,"#ed7953"],[0.7777777777777778,"#fb9f3a"],[0.8888888888888888,"#fdca26"],[1.0,"#f0f921"]],"type":"histogram2dcontour"}],"mesh3d":[{"colorbar":{"outlinewidth":0,"ticks":""},"type":"mesh3d"}],"parcoords":[{"line":{"colorbar":{"outlinewidth":0,"ticks":""}},"type":"parcoords"}],"pie":[{"automargin":true,"type":"pie"}],"scatter":[{"marker":{"colorbar":{"outlinewidth":0,"ticks":""}},"type":"scatter"}],"scatter3d":[{"line":{"colorbar":{"outlinewidth":0,"ticks":""}},"marker":{"colorbar":{"outlinewidth":0,"ticks":""}},"type":"scatter3d"}],"scattercarpet":[{"marker":{"colorbar":{"outlinewidth":0,"ticks":""}},"type":"scattercarpet"}],"scattergeo":[{"marker":{"colorbar":{"outlinewidth":0,"ticks":""}},"type":"scattergeo"}],"scattergl":[{"marker":{"colorbar":{"outlinewidth":0,"ticks":""}},"type":"scattergl"}],"scattermapbox":[{"marker":{"colorbar":{"outlinewidth":0,"ticks":""}},"type":"scattermapbox"}],"scatterpolar":[{"marker":{"colorbar":{"outlinewidth":0,"ticks":""}},"type":"scatterpolar"}],"scatterpolargl":[{"marker":{"colorbar":{"outlinewidth":0,"ticks":""}},"type":"scatterpolargl"}],"scatterternary":[{"marker":{"colorbar":{"outlinewidth":0,"ticks":""}},"type":"scatterternary"}],"surface":[{"colorbar":{"outlinewidth":0,"ticks":""},"colorscale":[[0.0,"#0d0887"],[0.1111111111111111,"#46039f"],[0.2222222222222222,"#7201a8"],[0.3333333333333333,"#9c179e"],[0.4444444444444444,"#bd3786"],[0.5555555555555556,"#d8576b"],[0.6666666666666666,"#ed7953"],[0.7777777777777778,"#fb9f3a"],[0.8888888888888888,"#fdca26"],[1.0,"#f0f921"]],"type":"surface"}],"table":[{"cells":{"fill":{"color":"#EBF0F8"},"line":{"color":"white"}},"header":{"fill":{"color":"#C8D4E3"},"line":{"color":"white"}},"type":"table"}]},"layout":{"annotationdefaults":{"arrowcolor":"#2a3f5f","arrowhead":0,"arrowwidth":1},"autotypenumbers":"strict","coloraxis":{"colorbar":{"outlinewidth":0,"ticks":""}},"colorscale":{"diverging":[[0,"#8e0152"],[0.1,"#c51b7d"],[0.2,"#de77ae"],[0.3,"#f1b6da"],[0.4,"#fde0ef"],[0.5,"#f7f7f7"],[0.6,"#e6f5d0"],[0.7,"#b8e186"],[0.8,"#7fbc41"],[0.9,"#4d9221"],[1,"#276419"]],"sequential":[[0.0,"#0d0887"],[0.1111111111111111,"#46039f"],[0.2222222222222222,"#7201a8"],[0.3333333333333333,"#9c179e"],[0.4444444444444444,"#bd3786"],[0.5555555555555556,"#d8576b"],[0.6666666666666666,"#ed7953"],[0.7777777777777778,"#fb9f3a"],[0.8888888888888888,"#fdca26"],[1.0,"#f0f921"]],"sequentialminus":[[0.0,"#0d0887"],[0.1111111111111111,"#46039f"],[0.2222222222222222,"#7201a8"],[0.3333333333333333,"#9c179e"],[0.4444444444444444,"#bd3786"],[0.5555555555555556,"#d8576b"],[0.6666666666666666,"#ed7953"],[0.7777777777777778,"#fb9f3a"],[0.8888888888888888,"#fdca26"],[1.0,"#f0f921"]]},"colorway":["#636efa","#EF553B","#00cc96","#ab63fa","#FFA15A","#19d3f3","#FF6692","#B6E880","#FF97FF","#FECB52"],"font":{"color":"#2a3f5f"},"geo":{"bgcolor":"white","lakecolor":"white","landcolor":"#E5ECF6","showlakes":true,"showland":true,"subunitcolor":"white"},"hoverlabel":{"align":"left"},"hovermode":"closest","mapbox":{"style":"light"},"paper_bgcolor":"white","plot_bgcolor":"#E5ECF6","polar":{"angularaxis":{"gridcolor":"white","linecolor":"white","ticks":""},"bgcolor":"#E5ECF6","radialaxis":{"gridcolor":"white","linecolor":"white","ticks":""}},"scene":{"xaxis":{"backgroundcolor":"#E5ECF6","gridcolor":"white","gridwidth":2,"linecolor":"white","showbackground":true,"ticks":"","zerolinecolor":"white"},"yaxis":{"backgroundcolor":"#E5ECF6","gridcolor":"white","gridwidth":2,"linecolor":"white","showbackground":true,"ticks":"","zerolinecolor":"white"},"zaxis":{"backgroundcolor":"#E5ECF6","gridcolor":"white","gridwidth":2,"linecolor":"white","showbackground":true,"ticks":"","zerolinecolor":"white"}},"shapedefaults":{"line":{"color":"#2a3f5f"}},"ternary":{"aaxis":{"gridcolor":"white","linecolor":"white","ticks":""},"baxis":{"gridcolor":"white","linecolor":"white","ticks":""},"bgcolor":"#E5ECF6","caxis":{"gridcolor":"white","linecolor":"white","ticks":""}},"title":{"x":0.05},"xaxis":{"automargin":true,"gridcolor":"white","linecolor":"white","ticks":"","title":{"standoff":15},"zerolinecolor":"white","zerolinewidth":2},"yaxis":{"automargin":true,"gridcolor":"white","linecolor":"white","ticks":"","title":{"standoff":15},"zerolinecolor":"white","zerolinewidth":2}}},"xaxis":{"anchor":"y","domain":[0.0,1.0],"title":{"text":"Score"}},"yaxis":{"anchor":"x","domain":[0.0,1.0],"title":{"text":"GDP per capita"}},"legend":{"title":{"text":"Region"},"tracegroupgap":0},"title":{"text":"Happines Scores per Region in 2019"}},                        {"responsive": true}                    )                };                            </script>        </div>