**Sort**
in-place:l.sort()
create a new list: la=sorted(l)

**drop a outlier**
clean = merged.loc[merged["AAPL"] >= -0.4]

**Pandas**
merged = pd.merge(left_table,
        right_table,
        left_index = True,
        right_index = True,
        how = inner/outer/left/right)
merged.dropna (inpace = True) #drop the missing value in the merged table 

