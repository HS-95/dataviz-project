# dataviz-project
# The largest heading
## Les taxons parents (cetaceamorphea) de la baleine bleue 
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
