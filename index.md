# dataviz-project

```sparql
#Les taxons parents (cetaceamorphea) de la baleine bleue 
#defaultView:Graph
SELECT ?item ?itemLabel ?pic ?linkTo
WHERE
{
  wd:Q42196 wdt:P171* ?item.
  ?item wdt:P171* wd:Q24031895.
  OPTIONAL { ?item wdt:P171 ?linkTo }
  OPTIONAL { ?item wdt:P18 ?pic }
  SERVICE wikibase:label {bd:serviceParam wikibase:language "en" }
}
```

# TITRE A

Les océans

   <iframe title="Température moyenne de l'air en surface des zones océaniques ou terrestres (°C)" aria-label="Interactive line chart" id="datawrapper-chart-ocDqe" src="https://datawrapper.dwcdn.net/ocDqe/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="547" data-external="1"></iframe>
   <script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(e){if(void 0!==e.data["datawrapper-height"]){var t=document.querySelectorAll("iframe");for(var a in e.data["datawrapper-height"])for(var r=0;r<t.length;r++){if(t[r].contentWindow===e.source)t[r].style.height=e.data["datawrapper-height"][a]+"px"}}}))}();</script>
 

## Sommaire
1. [1](#a)
2. [2](#b)
3. [3](#c)
4. [4](#d)
5. [5](#e)
6. [6](#f)



## 1<a name="a"></a>
## 2<a name="b"></a>
## 3<a name="c"></a>
## 4<a name="d"></a>
## 5<a name="e"></a>
## 6<a name="f"></a>

