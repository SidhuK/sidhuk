<h4 align="Center"> 👋 </h2>

```R

SidhuK <- function(Karat_Sidhu) {

        username <- 'SidhuK'
        name <-  'Karat Sidhu'
        website <- 'https://karatsidhu.com/'
        twitter <- '@karat_sidhu'
        linkedin <- "karatsidhu"
        code <- (
            'main_coding_languages' = c('R', 'Python')
            'tools' = c('TidyVerse', 'RMarkdown', 'GIT', 'GitHub', 'Seaborn', 'Pandas', 'Jupyter'),
            'frontend' = c('HTML', 'CSS', 'Bootstrap')
        )
        scientific <- (
            'research' = c('Metabolomics', 'Proteomics', 'LC/MS/MS', 'Cell_Biology','Small Molecule Analysis'),
            'academic' = c('Biotechnology', 'Analytical Chemistry')
        )
        personal <- c('Reading', 'Painting', 'Running', 'Skiing')

    Karat_Sidhu <- as.dataframe(username, name, website, twitter, linkedin, code, scientific, personal, stringsasfactors = FALSE)

    return(Karat_Sidhu)

}

```

<h4 align="center">✌️</h4>
