![Vera Institute of Justice Logo](https://github.com/vera-institute/jail-population-data/blob/master/vera-logo.png?raw=true)

# Jail Population Data
Public release of jurisdiction-level jail population data (January 1, 2020-present)

## Project History
In response to the novel coronavirus, Vera researchers in the In Our Backyards Project have been publishing jail populations. The most recent available data for each jail jurisdiction is presented in a simple table at the Vera Institute of Justice [website](https://www.vera.org/projects/covid-19-criminal-justice-responses/covid-19-data) along with information on COVID-19 cases. This page provides access to the complete set of jail data since January 1, 2020.

For more information about this data, please see a blog by Chris Henrichson and Oliver Hinds,
[Use this Data to Hold Your Local Jail Accountable During the Pandemic](https://www.vera.org/blog/covid-19-1/use-this-data-to-hold-your-local-jail-accountable-during-the-pandemic).

For more information on In Our Backyards, see http://www.vera.org/backyards.

## Data

This data is automatically collected and pushed out to this file daily at 8pm Eastern Time. The data is updated on the Vera [website](https://www.vera.org/projects/covid-19-criminal-justice-responses/covid-19-data) the following morning.   Historical data may change as better information is collected. While Vera researchers conduct data quality assurance, users should seek to verify of any dramatic single day change they observe in data.  (Please also send information regarding potential errors to jkangbrown@vera.org)

The data file is available in [CSV](https://github.com/vera-institute/jail-population-data/blob/master/jail_population.csv) format.

For historical jail populations (1970-2018), see Vera’s [incarceration trends dataset](https://github.com/vera-institute/incarceration_trends).

## Documentation

The variables included in this data are
* `fips`: county-level fips code
* `date`: date of jail population
* `jail_population`: number of people incarcerated in the jail
* `county`: county, city or parish name
* `state`: state name
* `urbanicity`: urbanicity of county (urban county, suburban county in large metro area, county in small to mid-sized metro area, or rural county)
* `reporting_jurisdictions`: name of the reporting jail jurisdictions
* `resident_population`: all ages resident population of county for July 1, 2019
* `jail_incarceration_rate_per_100k`: rate of jail incarceration per 100,000 residents

## Sourcing

This data is collected from multiple sources. The
[sourcing CSV file](https://github.com/vera-institute/jail-population-data/blob/master/jail_data_sources.csv)
indicates the source(s) for each county. A key to the values in that
file follows:
* `auto`: Collected automatically directly from jail jurisdictions.
* `jdi`: Collected by the [NYU Public Safety Lab](https://publicsafetylab.org/).
* `state`: Collected automatically from a central source at the state-level.
* `manual`: Collected manually by one of the researchers in the list below.

Collecting manual data involved the efforts of
Darby Aono,
Collin Blinder,
Jasmine Heiss,
Christian Henrichson,
Oliver Hinds,
Indiana Public Defender Council,
Jacob Kang-Brown,
Sarah Minion,
Clay Mosher,
Jack Norton,
Michelle Parris,
Eital Schattner-Elmaleh,
Maurice Smith, and
James Wallace-Lee.

## License

By downloading the data, you hereby agree to all of the terms specified in this [license](https://github.com/vera-institute/jail-population-data/blob/master/License.md).


## Endmatter

If you have questions, please contact Jacob Kang-Brown at <jkangbrown@vera.org>.

The Vera Institute of Justice works to build and create justice systems that ensure fairness, promote safety, and strengthen communities.

The development of the public-use county- and jurisdiction-level incarceration dataset is funded through the In Our Backyards project by Google.org as part of its Inclusion and Racial Justice work. In Our Backyards is a Vera's research and communications agenda to inform the public dialogue, advance research, and guide change to justice policy and practice on mass incarceration.
