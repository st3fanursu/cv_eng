---
name: Stefan
surname: Ursu
position: "Student"
address: "Cluj-Napoca, Cluj, Romania"
phone: +40 745 29 39 24
email: "stefan.wrsw@gmail.com"
istagram: hi.im.steff
github: st3fanursu
linkedin: www.linkedin.com/in/ștefan-ursu-8065442b0
date: "`r format(Sys.time(), '%B %Y')`"
output: 
  vitae::latexcv:
    theme: classic
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE, warning = FALSE, message = FALSE)
library(vitae)
```

# Some stuff about me

   I recently completed studies in economics and acquired solid knowledge in R, SQL, and spreadsheet manipulation during an online course offered by Google. I am motivated to start my career in data analysis and eager to learn and develop my skills in this field. I am an organized individual with excellent problem-solving skills and a proactive attitude towards learning and development.

Other things about me, I grow up in a poor family; I was almost considering going pro in football at the age of 16, but I decided to finish my school; I don't have ny siblings.

# Education

```{r}
library(tibble)
tribble(
  ~ Degree, ~ Year, ~ Institution, ~ Where,
  "Highschool", "2015-2019", "Colegiul Nation „Calistrat Hogas”", "Piatra-Neamt, Romania",
  "Bachelor", "2019-2022", "UBB : Facultatea de Stiinte Economice si Gestiunea Afacerii", "Cluj-Napoca, Romania",
  "Master", "2022-present", "UBB : Facultatea de Stiinte Economice si Gestiunea Afacerii", "Cluj-Napoca, Romania"
) %>% 
  detailed_entries(Degree, Year, Institution, Where)
```

# Last workplaces

```{r}
tribble(
  ~Where, ~Year, ~Post, ~Location,
  "OMV-Petrom", "2020", "All rounded worker", "Piatra-Neamt, NT-Romania",
  "OMV-Petrom", "2021", "All rounded worker", "Cluj-Napoca, CJ-Romania",
  "Pink Pony", "2023", "Expo, Food-runner, Busser", "Mackinack Island, MI-USA"
) %>% 
  detailed_entries(Where, Year, Post, Location
  )
```

# Skills
```{r, results='asis', out.height="80%"}
tribble(
  ~Type, ~Where,
  "Teamwork", "OMV-Petrom, Pink Pony and during my college and in my volunteer work",
  "Tableu", "During my Google Analitics Specialization",
  "Spreadsheets", "During my Prepare Data for Explorationand and Process Data from Dirty to Clean",
  "Microsoft Excel", "During my Prepare Data for Exploration and Process Data from Dirty to Clean",
  "SQL", "During my Prepare Data for Exploration and Process Data from Dirty to Clean",
  "","",
  "R - programing", "During my Data Analysis with R Programming",
  "Economics and Finance", "From my specialization in college and master",
  "Problem solving", "During my Google Data Analytics Specialization and college"
) %>%
  detailed_entries(Type, Where
  )
```
# Volunteer

```{r}
tribble(
  ~Organization, ~What, ~When,
  "Untold", "Helped organizing a festival", "2022",
) %>%
  detailed_entries(Organization, When, What
  )
```
# Certificates
 *ALL THE BELOW ARE LINKS, OPEN IN A NEW TAB*

* [Google Data Analytics Specialization](https://www.coursera.org/account/accomplishments/specialization/U4EF8A2QLBZF)
* [Analyze data to answer questions](https://www.coursera.org/account/accomplishments/verify/MQGGAWXD3WVU)
* [Data Analysis with R programing](https://www.coursera.org/account/accomplishments/verify/YXB6UPD2J8EQ)
* [Prepare data for exploration](https://www.coursera.org/account/accomplishments/verify/SWC5D38FTK2U)
* [Process data from Dirty to Clean](https://www.coursera.org/account/accomplishments/verify/G7YWK3TFS9GT)
* [Share data through the Art of Visualization](https://www.coursera.org/account/accomplishments/verify/9JZNJ6CB5ASE)
* [Ask questions to make Data-Driven Decisions](https://www.coursera.org/account/accomplishments/verify/SYQRES9WWMU9)
* [Foundations: Data, Data, Eveywhere](https://www.coursera.org/account/accomplishments/verify/W57L9ANJYSA2)
