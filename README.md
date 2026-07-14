LocalFlag = 
IF(
    ISBLANK('DeineTabelle'[Column44]),
    0,
    IF(CONTAINSSTRING('DeineTabelle'[Column44], "LOCAL"), 1, 0)
)
