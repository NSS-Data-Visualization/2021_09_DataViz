## Data Visualization Challenge, September 2021

This month you will be working with a dataset containing information about every Scooby-Doo episode, movie and special.

This dataset was obtained from [Kaggle](https://www.kaggle.com/williamschooleman/scoobydoo-complete).


|variable                 |class     |description              |
|:------------------------|:---------|:------------------------|
|index                    |double    | Official ordering of episodes and movie on Scoobypedia, not perfectly chronological|
|series_name              |character |Name of the series in which the episode takes place or in movies' cases the Scoobypedia's grouping classification |
|network                  |character |Network the TV series takes place in, if it is a movie will use similar grouping as series.name variable |
|season                   |character |Season of TV Series, if not TV Series will default to the format                   |
|title                    |character |Title of Episode/Movie                    |
|imdb                     |character | Score on IMDB (NULL if recently aired) |
|engagement               |character | Number of reviews on IMDB (NULL if very recently aired) |
|date_aired               |double    |Dated aired in US               |
|run_time                 |double    | Run time in min                 |
|format                   |character | Type of media                    |
|monster_name             |character |Name of monster              |
|monster_gender           |character |Binary monster gender            |
|monster_type             |character |Monster type              |
|monster_subtype          |character | Monster subtype           |
|monster_species          |character |Monster species          |
|monster_real             |character | Was monster real             |
|monster_amount           |double    | Monster amount            |
|caught_fred              |character |Monster(s) caught by Fred              |
|caught_daphnie           |character |Monster(s) caught by Daphnie           |
|caught_velma             |character |Monster(s) caught by Velma             |
|caught_shaggy            |character |Monster(s) caught by Shaggy            |
|caught_scooby            |character |Monster(s) caught by Scooby            |
|captured_fred            |character |Fred caught by the monster(s)            |
|captured_daphnie         |character |Daphnie caught by the monster(s)        |
|captured_velma           |character |Velma caught by the monster(s)           |
|captured_shaggy          |character |Shaggy caught by the monster(s)          |
|captured_scooby          |character |Scooby caught by the monster(s)          |
|unmask_fred              |character |unmask by fred              |
|unmask_daphnie           |character |unmask by Daphnie           |
|unmask_velma             |character |unmask by Velma             |
|unmask_shaggy            |character |unmask by Shaggy            |
|unmask_scooby            |character |unmask by Scooby            |
|snack_fred               |character |Fred offers someone a scooby-snack               |
|snack_daphnie            |character |Daphnie offers someone a scooby-snack             |
|snack_velma              |character |Velma offers someone a scooby-snack              |
|snack_shaggy             |character |Shaggy offers someone a scooby-snack              |
|snack_scooby             |character |Scooby offers someone a scooby-snack              |
|unmask_other             |logical   |Someone not in the gang unmasks the monster(s)             |
|caught_other             |logical   |Someone not in the gang catches the monster(s)             |
|caught_not               |logical   | The monster is not caught               |
|trap_work_first          |character | The traps works first time as intended          |
|setting_terrain          |character | Setting type of terrain          |
|setting_country_state    |character |setting country state    |
|suspects_amount          |double    |The number of characters not part of the gang that have significant dialogue          |
|non_suspect              |character |The culprit is not part of the original suspects             |
|arrested                 |character |At least one culprit arrested (assumed to be arrested unless shown otherwise)                 |
|culprit_name             |character |culprit name             |
|culprit_gender           |character |culprit binary gender           |
|culprit_amount           |double    |culprit amount           |
|motive                   |character |motive                   |
|if_it_wasnt_for          |character | First group blamed by culprit(s)          |
|and_that                 |character |Second group blamed by culprit(s)                 |
|door_gag                 |logical   |Scene of the gang being chased by monster down corridor running in and out of doors in a comedic manner                 |
|number_of_snacks         |character |Number of snacks eaten by members of the gang in total (approximated)         |
|split_up                 |character |Number of times Fred says something akin to "Lets split up and look for clues"                 |
|another_mystery          |character |Number of times Fred says something akin to "It looks like we have another mystery on our hands"          |
|set_a_trap               |character |Number of times Fred says something akin to "Set a trap"              |
|jeepers                  |character |Number of times Daphne says exactly "Jeepers"                  |
|jinkies                  |character |Number of times Velma says "Jinkies"                 |
|my_glasses               |character |Number of times Velma loses and complains about her glasses             |
|just_about_wrapped_up    |character |Number of times Velma says something akin to "I have this mystery just about wrapped up"    |
|zoinks                   |character |Number of times Shaggy says exactly "Zoinks"  |
|groovy                   |character |Number of times Shaggy says exactly "Groovy"                  |
|scooby_doo_where_are_you |character |Number of times Shaggy says exactly "Scooby-Doo where are you!" |
|rooby_rooby_roo          |character |Number of times Scooby says something akin to "Rooby Rooby Roo"          |
|batman                   |logical   |batman in episode                   |
|scooby_dum               |logical   | scooby_dum in episode               |
|scrappy_doo              |logical   |scrappy_doo in episode              |
|hex_girls                |logical   |hex_girls in episode                 |
|blue_falcon              |logical   |blue_falcon in episode              |
|fred_va                  |character |Fred voice actor                  |
|daphnie_va               |character |Daphnie voice actor               |
|velma_va                 |character |velma voice actor                 |
|shaggy_va                |character |shaggy  voice actor                |
|scooby_va                |character |scooby  voice actor                |