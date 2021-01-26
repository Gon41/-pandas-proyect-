# -Pandas- Shark proyect

![](https://www.australiangeographic.com.au/wp-content/uploads/2018/06/great-white-shark.jpg)

--------
## 1. Objetive

Given a database of shark attacks, we had to draw a hypothesis and then proceed to debug the database.

Database: https://www.kaggle.com/teajay/global-shark-attacks

--------

## 2. Hypothesis

### Men suffer more shark attacks because they engage in riskier behaviors.
----

## 3. Development

Forbes magazine states "Unlike testosterone, the female hormone, oxytocin, acts largely responsible for female emotional stability but in a calming way and would explain, according to the AFS Finance study, why in the midst of the financial crisis female investors fared much better than their male counterparts."

It should be added that the male sex is indeed very prone to risk-taking, this is because men acquire greater social status by taking on this type of behavior. Also risk-taking and violent behavior, especially in young adulthood, is related to the establishment of hierarchical orders among their competitors.

*Source: Are men more prone to risk-taking than women?*:  https://forbes.es/empresas/43241/son-los-hombres-mas-proclives-a-asumir-riesgos-que-las-mujeres/

---

## 4. Analysis

For data analysis and cleaning, given that the BB.DD. shows 25,723 rows and 24 columns, I have decided to focus on only 6 columns that will either allow me to get the data I need or help me to find out erroneous, inaccurate or NaN data from other columns.

I have removed all duplicate data, and converted the NaN data in the 'Years' column to 'floats' and then converted the whole column to 'int'.


Then I remove the NaN and all those values lower than 1,970, in order to obtain the data grouped by decades.

I modify the name of the column 'Sex' to leave all the names under the same pattern and I finish cleaning those data that within the sex column do not refer to male or female, helping me with the variable name in many of them.

## 5. Conclusions

The result is a graph that shows not only that shark attacks on men are much higher than on women, but also that both in global computation and divided by quota, attacks on both sexes have increased dramatically.
