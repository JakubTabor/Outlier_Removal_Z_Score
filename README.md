# Outlier_Removal_Z_Score
# I use my previous calculations from std. excercise
# I create new column "zscore" and calculate it from pattern """(df2.price-df2.price.mean())/df2.price.std()"""
# Now i can get outliers with this formula """df2[(df2.zscore < -4)| (df2.zscore > 4)]"""
# Then i save my outliers to new df4. """df2[(df2.zscore > -4) & (df2.zscore < 4)]"""
