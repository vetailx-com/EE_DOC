Entity Extraction
=======

/getkeywords
-----


**Input**

The /getkeywords endpoint takes one and only one of these parameters.

`url=`  a valid URL containing a text/article.

`text=` a string containing the text that's to be analyzed.


Example:

`/getkeywords?url=http://www.clipkit.de`

`/getkeywords?text=The quick brown fox jumps over the lazy dog`



**Output**

The results are returned as a JSON file containing the entity's base form, type and weight.

Example:

```
{
    "url": "http://www.vetail-x.com/apiservices/getXml?id=fUplVGNab3pecwMDHGMEWk91XH9LDlINAVtyBGxID1FEQkEFXkoCQW1wAXBTRHl6D1cDTn5MWAgDbkxtAlRZYFoOdXpaUQN7QltXbQM",
    "weightedKeywords": [
        {
            "name": "Default (finance)",
            "type": "Keyword",
            "weight": "1.14255167498"
        },
        {
            "name": "Secrecy",
            "type": "TopicalConcept",
            "weight": "5.28510334996"
        },
        {
            "name": "Status quo",
            "type": "Keyword",
            "weight": "2.57127583749"
        },
        {
            "name": "Open-source software",
            "type": "Keyword",
            "weight": "2.64255167498"
        },
        {
            "name": "Key (lock)",
            "type": "Keyword",
            "weight": "2.57127583749"
        },
        {
            "name": "Fine (penalty)",
            "type": "Keyword",
            "weight": "1.07127583749"
        },
        {
            "name": "Action game",
            "type": "TopicalConcept",
            "weight": "8.99679258732"
        },
        {
            "name": "YouTube",
            "type": "TopicalConcept",
            "weight": "2.14255167498"
        },
        {
            "name": "EBay",
            "type": "TopicalConcept",
            "weight": "2.57127583749"
        }
    ]
}
```
