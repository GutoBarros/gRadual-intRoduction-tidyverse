## Tasks We Do using the Tidyverse

+ Recode Data (stringr/forcats)
    - fct_recode()/fct_collapse()/fct_relevel()
+ Load Data
+ Transform Strings (stringr)
    + Replace text with other text
        - stringr::str_replace_all(), mutate()
+ Merge two tables on a common ID (inner_join, left_join, right_join, full_join)
+ Format Dates (lubridate)
+ Work with Factors/Categorical Data (forcats)
+ Sort Data (arrange)
+ Reorder Bar Plots with Factors (forcats)
  - fct_infreq(), fct_reorder()
+ Walk through tidying data and then tweaking a plot to improve it
    - Ex:  http://varianceexplained.org/r/improving-pie-chart/
+ Create a summarized table and plot it
    - group_by(), summarize(), geom_col()
+ Chain a bunch of operations (%>%)
+ Error bars on a plot?
+ Group variables together (tidyr::gather())
+ Separate a variable into separate variables: tidyr::separate()
+ Lump together levels into "other": forcats::fct_lump()