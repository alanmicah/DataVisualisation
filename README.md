# Data Visualisation

Coding exercises and practices of data visualisation

## Chart Types

<!-- prettier-ignore -->
* __Trends__ - a trend is a pattern of change
  * `sns.lineplot` - a line chart, used to show trends over an amount of time. Multiple lines can be used to show multiple trends

* __Relationships__ - to show relationship between variables in data
  * `sns.barplot` - Bar charts useful for comparing quantities corresponding to each group
  * `sns.heatmap` - Heatmaps colour-coded patterns and intensities in tables of numbers
  * `sns.scatterplot` - Scatter plots shows relationship between two different continuous variables. If there is a colour-code then a third catergorical variable can be shown.
  * `sns.regplot` - Includes a Regression line in the scatter plot. This can make it easier to see any linear relationship between two variables.
  * `sns.lmplot` - Used to draw mutiple Regression lines in a scatter plot that contains multiple colour-coded groups
  * `sns.swarmplot` - Categorical scatter plots display the relationship between continuous variable and categorical variable.
  
* __Distribution__ - visualised to see possible values that we expect to see along with how they actually are
  * `sns.histplot` - Histograms show the distribution for each numerical variable.
  * `sns.kdeplot` - KDE plots or kernel density estimate plots (2D kde plots) show an estimated, smooth distribution of single or two numerical variable.
  * `sns.joinplt` - Shows the 2D KDE plot with corresponding KDE plot for each variable.
