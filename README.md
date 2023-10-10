# matplotlib-challenge
Module 5
* https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.duplicated.html
* https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.var.html
* https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.std.html
* https://pandas.pydata.org/docs/reference/api/pandas.concat.html
* https://pandas.pydata.org/docs/reference/api/pandas.Series.to_frame.html
* https://www.r-bloggers.com/2022/06/how-to-join-multiple-data-frames-in-r/#:~:text=Fortunately%2C%20the%20left%20join(),makes%20this%20simple%20to%20accomplish.&text=We%20can%20easily%20conduct%20two,combine%20all%20three%20data%20frames.&text=connect%20the%20three%20data%20frames.&text=Notably%2C%20the%20outcome%20of%20this,saved%20as%20a%20data%20frame.
* https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sem.html
* https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.html
* from AI-generated Google Search: import pandas as pd
**import matplotlib.pyplot as plt

**Create a data frame
**data = {'Year': [2017, 2018, 2019], 'Sales': [10000, 12000, 14000]}
**df = pd.DataFrame(data)

**Plot the data frame as a bar chart
**plt.bar(df['Year'], df['Sales'])
**plt.title('Annual Sales')
**plt.show()
