Flexbox Tutorial

https://www.youtube.com/watch?v=FTlczfR82mQ&list=PLDyQo7g0_nsUjf046cCHKJ16U1SoXrElZ&index=6


    DISPLAY: FLEX (ON THE PARENT)
    
    - flex-direction
        - row: standalone
        - column: like not using flex at all. (But it allows you to use flex features)
    - justify-content
        - flex-start: standalone
        - center
        - flex-end
        - space-between: without MARGINs
        - space-around: with MARGINs
        - space-evenly: with MARGINs that are equal to the space in between the items.
    - align-items: Same as justify-content but using the "cross axis" as reference.
        - flex-start: standalone
        - center
        - flex-end
        - stretch: it stretches the items, unless their width/height is defined.
        - baseline: the items are moved so that the text they contain is aligned.
    - flex-wrap
        - nowrap: standalone
        - wrap: the items that don't fit will jump to the next line
    - align-content: used with flex-wrap, removing the spaces in between the lines. 
    (It works as justify-content)
    - flex-flow: direction + wrapping
        (e.g. |-> "flex-flow: column wrap;" )
        
        
    (ON THE CHILD)
    
    - order: each child would have an order assigned and the parent will list them accordingly.
    - flex-grow: freaking confusing. (1 = takes the available space)
    - flex-shrink: freaking confusing. (1 = standalone)
    - flex-basis: freaking confusing. (it's like saying width. If used with a wrap parent, 
    it won't let it go below that width)
    - flex: extremely confusing as it combines the 3 above.
    - align-self: like align-items, but for each child.
