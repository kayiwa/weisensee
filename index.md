```mermaid
---
flowchart TD
    Mary["Mary Weisensee"] --- Lloyd["Lloyd Weisensee"]
    Lloyd --- Lloyd_Jr["Lloyd Jr."] & Emily["Emily"] & Robert["Robert\nDied age 2-3"] & John["John"] & Marjorie["Marjorie\nDied age 18"] & Andrea["Andrea\nUnknown # of children"]
    Lloyd_Jr --- Sara["Sara\nUnknown # of children"] & Jerry["Jerry"] & Fred["Fred\n0 children"] & Matt["Matt"]
    John --- Twins["Twins\n2 children"]
    Jerry --- Sheila["Sheila"] & Edward["Edward"] & Isabella_Ann["Isabella Ann"] & Mark_J["Mark"]
    Matt --- Jeff["Jeff\nUnknown # of children"] & David["David"] & Tom["Tom"] & Joe["Joe"]
    Sheila --- Sheila_Child1["Child 1"] & Sheila_Child2["Child 2"] & Sheila_Child3["Child 3"] & Sheila_Child4["Child 4"] & Sheila_Child5["Child 5"] & Sheila_Child6["Child 6"]
    Edward --- Edward_Child1["Child 1"] & Edward_Child2["Child 2"]
    Isabella_Ann --- Isabella_Son1["Son 1"] & Isabella_Son2["Son 2"] & Isabella_Son3["Son 3"] & Isabella_Son4["Son 4"]
    Mark_J --- Mark_Child["Child"]
    Tom --- Tom_Child1["Mark"] & Tom_Child2["Jeff"] & Tom_Child3["Unknown\nAdopted"] & Tom_Child4["Unknown\nAdopted"]
    Joe --- Joe_Child1["Child 1"] & Joe_Child2["Child 2"] & Joe_Child3["Child 3"] & Joe_Child4["Child 4"] & Joe_Child5["Child 5"] & Joe_Child6["Child 6"]
     Robert:::deceased
     Marjorie:::deceased
    classDef deceased fill:#f9f9f9,stroke:#999,stroke-dasharray: 5 5

```
