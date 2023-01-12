## Data analysis and visualization of greenhouse gas emissions of parties of climate change convention

The United Nations Framework Convention on Climate Change (UNFCCC) is a crucial international treaty aimed at mitigating the effects of greenhouse gas emissions on the global climate. In this project, I have leveraged cutting-edge data wrangling techniques in R to analyze and present a comprehensive overview of emissions from countries that are parties to the UNFCCC.

The initial state of the data presented several challenges, as it was limited to just four columns containing basic information on the serial number, country, year, and pollutant category. I have employed a range of advanced data-wrangling techniques to effectively transform this raw data into a form that is suitable for further analysis.

I have leveraged the powerful dplyr package, utilizing functions such as mutate, recode, pivoting, grouping, and subset selection, to manipulate and reorganize the data. The mutate function, in particular, has been used in conjunction with recode to rename the category variables according to the gas name, thereby simplifying the pollutant categories.

In addition to these data wrangling techniques, I have also performed a thorough data cleaning process to eliminate any "NA" values that may have crept in during the conversion of the data type. The gsub function was used to remove any commas between numbers that could have caused issues with improperly formatted values.

Finally, I have used the ggplot2 library to create stunning visualizations of the filtered data, providing key insights into the emissions trends of UNFCCC member countries. This sophisticated approach to data analysis has allowed me to present a clear and concise overview of the current state of emissions and will be an invaluable resource for decision-makers and stakeholders working towards the reduction of greenhouse gas emissions.
