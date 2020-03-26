# Curated Datasets
  
Community curated datasets for specific countries.


# Community curated live JSON data feed

An hourly-updated feed of every country, state, and region in the world, including the complete history of Confirmed, Recovered, and Death cases as well as best-fit function coefficients that accurately model the outbreak, allowing for real-time (up to the second) counts of all data, and accurate near-term forecasting (days and upto a week ahead), as well as indicators like "how many days does it take to double"

Visit https://cryptinc.com/covid19/covid19_predictor.html and do "view source" to see:

> **JSON:** The URL of the JSON source data and example javscript for loading it.
> **sigmoid** The function that makes use of the paramaters in the data along with the current unix time to show up-to-the-second counts
> **arcsigmoid** The function that gives you the moment in time that matches the outbreak count number you provided - e.g. give it the current count/2 to see how many days it took to double right now.


Example(country):

       'Australia' => {
                        'paramaters' => {
                                          'Recovered' => {
                                                           'dayshift' => '-62.2386794713725',
                                                           'fixedstart' => '-0.0733719233845119',
                                                           'dayscale' => '0.73959278920283',
                                                           'magnitude' => '168.321438433629',
                                                           'confidence' => '5.39359161521267'
                                                         },
                                          'Confirmed' => {
                                                           'dayscale' => '0.266911889779252',
                                                           'magnitude' => '6433.01054627119',
                                                           'confidence' => '29.1316171122377',
                                                           'fixedstart' => '-0.00476592209742425',
                                                           'dayshift' => '-67.2524582622525'
                                                         },
                                          'Deaths' => {
                                                        'dayscale' => '0.144364331175627',
                                                        'confidence' => '0.967474876366797',
                                                        'magnitude' => '57.5165777240438',
                                                        'fixedstart' => '-0.0296929856086443',
                                                        'dayshift' => '-76.4248745116715'
                                                      }
                                        },
                        'Long' => '133',
                        'Recovered' => {
                                         '1584846800' => '88',
                                         '1580620406' => '2',
                                         '1584138117' => '23',
                                         '1581486182' => '8',
                                         '1582262583' => '11',
                                         '1581838382' => '10',
                                         '1583389386' => '21',
                                         '1584940760' => '119',
                                         '1585214055' => '172',
                                         '1584604403' => '26'
                                       },
                        'Lat' => '-25',
                        'Country_Region' => 'Australia',
                        'Last_Update' => '1585247675',
                        'Active' => '2625',
                        'Confirmed' => {
                                         '1584339212' => '377',
                                         '1583538182' => '63',
                                         '1583389386' => '58',
                                         '1583641982' => '76',
                                         '1584769382' => '1071',
                                         '1585214055' => '2806',
                                         '1584954450' => '1676',
                                         '1584192784' => '250',
                                         '1584940760' => '1562',
                                         '1582934589' => '25',
                                         '1585101453' => '2318',
                                         '1584708183' => '791',
                                         '1584523985' => '568',
                                         '1584259999' => '297',
                                         '1584846800' => '1314',
                                         '1582761181' => '23',
                                         '1583809996' => '107',
                                         '1584138117' => '200',
                                         '1582262583' => '19',
                                         '1583915582' => '128',
                                         '1580961795' => '15',
                                         '1582383786' => '22',
                                         '1583249582' => '39',
                                         '1583478185' => '60',
                                         '1580620406' => '12',
                                         '1583326989' => '42',
                                         '1584978269' => '1682',
                                         '1583119988' => '31',
                                         '1585042117' => '2044',
                                         '1580830383' => '13',
                                         '1584432802' => '452',
                                         '1583721189' => '91',
                                         '1585127674' => '2364',
                                         '1583340782' => '52',
                                         '1584604403' => '681',
                                         '1585222189' => '2810'
                                       },
                        'Deaths' => {
                                      '1583028191' => '1',
                                      '1584432802' => '5',
                                      '1583641982' => '4',
                                      '1585214055' => '13',
                                      '1585042117' => '8',
                                      '1583340782' => '2',
                                      '1584523985' => '6',
                                      '1584708183' => '7'
                                    }
                      },

Example(state):


       'Australia|South Australia' => {
                                        'paramaters' => {
                                                          'Confirmed' => {
                                                                           'dayshift' => '-64.9673047768277',
                                                                           'fixedstart' => '-0.020787289159656',
                                                                           'magnitude' => '368.744315058677',
                                                                           'confidence' => '6.01157669937733',
                                                                           'dayscale' => '0.407993820934908'
                                                                         }
                                                        },
                                        'Combined_Key' => 'South Australia, Australia',
                                        'Long' => '138.6007',
                                        'Country_Region' => 'Australia',
                                        'Recovered' => {
                                                         '1584940760' => '6',
                                                         '1584150783' => '3',
                                                         '1581927189' => '2'
                                                       },
                                        'Lat' => '-34.9285',
                                        'Last_Update' => '1585247675',
                                        'Active' => '229',
                                        'Deaths' => {},
                                        'Confirmed' => {
                                                         '1583468588' => '7',
                                                         '1582941790' => '3',
                                                         '1583325783' => '5',
                                                         '1584150783' => '16',
                                                         '1584532384' => '37',
                                                         '1584886390' => '100',
                                                         '1584796415' => '67',
                                                         '1580682787' => '2',
                                                         '1583952724' => '9',
                                                         '1584296419' => '20',
                                                         '1584738810' => '50',
                                                         '1580580769' => '1',
                                                         '1584616434' => '42',
                                                         '1585214055' => '235',
                                                         '1585042117' => '170',
                                                         '1584369526' => '29',
                                                         '1584192784' => '19',
                                                         '1584954450' => '134'
                                                       },
                                        'Province_State' => 'South Australia'
                                      },

