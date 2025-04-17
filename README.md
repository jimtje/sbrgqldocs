# sbrgqldocs
SBR GQL Docs

Sportsbookreview/SBROdds GraphQL endpoint docs

Actual documentation of the whole thing is deployed at https://jimtje.github.io/sbrgqldocs/



Feel free to use the discussion section if for questions, suggestions, remarks, or whatever. All materials put out by SBR has been ISC licensed as far as I can tell. All works released publicly by me should be considered to be in the public domain.



Quick reference for certain id numbers to get started:

Sports (spid):

| nam          | spid |
| ------------ | ---- |
| rugby        | 22   |
| cricket      | 21   |
| E-SPORTS     | 11   |
| golf         | 10   |
| fighting     | 9    |
| tennis       | 8    |
| basketball   | 5    |
| football     | 4    |
| baseball     | 3    |
| horse racing | 23   |
| hockey       | 6    |
| politics     | 25   |
| soccer       | 2    |

Sportsbooks (Offshore, sitid 5)

| nam                  | paid | pre                                        | sbid |
| -------------------- | ---- | ------------------------------------------ | ---- |
| 5Dimes               | 3    | http://www.5dimes.eu/?                     | 19   |
| ABCislands           | 4    | http://www.abcislands.ag/?                 | 23   |
| Bet365               | 5    | http://www.bet365.com/betslip/instantbet/? | 43   |
| betcris              | 10   | http://www.betcris.com/?                   | 118  |
| BetMania             | 83   |                                            | 1252 |
| BetOnline            | 8    | http://www.betonline.com/?                 | 1096 |
| BetPhoenix           | 28   | http://www.betphoenix.ag/register?         | 1389 |
| Bookmaker            | 10   | http://www.bookmaker.eu/?                  | 93   |
| Bovada               | 9    | https://www.bovada.lv/?                    | 1618 |
| GTbets               | 65   | http://www.gtbets.eu/?                     | 1602 |
| Heritage Sports      | 44   | http://www.heritagesports.eu/?             | 169  |
| Intertops            | 29   | http://www.intertops.eu/?                  | 180  |
| IslandCasino         | 3    | http://www.islandcasino.com/?              | 442  |
| JazzSports           | 15   | http://www.jazzsports.ag/?                 | 186  |
| JustBet              | 16   | http://www.justbet.cx/?                    | 1275 |
| LooseLines           | 15   | http://www.looselines.ag/?                 | 423  |
| Matchbook            | 18   | https://www.matchbook.com/?                | 626  |
| MyBookie             | 82   | http://mybookie.ag/?                       | 1680 |
| Pinnacle             | 20   | http://www.pinnaclesports.com/Lines.aspx?  | 238  |
| Skybook              | 84   |                                            | 274  |
| Sportbet             | 3    | http://www.sportsbet.com.au/?              | 279  |
| SportsBetting        | 8    | https://www.sportsbetting.ag/?             | 289  |
| SportsInteraction    | 35   | http://www.sportsinteraction.com/?         | 300  |
| The Greek Sportsbook | 22   | http://www.thegreek.com/?                  | 227  |
| WagerWeb             | 54   | http://wagerweb.ag/?                       | 414  |
| YouWager             | 38   | http://www.youwager.eu/welcome/?           | 139  |

Regions (rid), in theory every possible locale is represented but not in alphabetical order:

| nam                  | rid  | sn   |
| -------------------- | ---- | ---- |
| USA                  | 1    | US   |
| England              | 2    | ENG  |
| Europe               | 3    | EUR  |
| France               | 4    | FR   |
| Italy                | 5    | IT   |
| Germany              | 6    | DE   |
| San Marino           | 30   | SM   |
| Tunisia              | 29   | TN   |
| Andorra              | 28   | AD   |
| El Salvador          | 27   | SV   |
| Vietnam              | 26   | VN   |
| Qatar                | 25   | QA   |
| Iran                 | 24   | IR   |
| Moldova              | 23   | MD   |
| Kazakhstan           | 22   | KZ   |
| Albania              | 21   | AL   |
| Faroe Islands        | 20   | FO   |
| Luxembourg           | 19   | LU   |
| Bosnia & Herzegovina | 18   | BA   |
| New Zealand          | 17   | NZ   |
| Scotland             | 15   | SCT  |
| Portugal             | 14   | PT   |
| Netherlands          | 13   | NL   |
| Mexico               | 12   | MX   |
| Brazil               | 11   | BR   |
| Argentina            | 10   | AR   |
| World                | 9    | WLD  |
| Canada               | 8    | CA   |

