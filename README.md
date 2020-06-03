# NBAPlayoffExcitement
## Quinn Johnson's exploration of the most exciting (plausible) NBA Playoffs Format

Throughout recent years, many leagues have altered their postseason systems (e.g. MLB Wild Card Game, NFL increasing postseason to 14 teams), and while the NBA has made some changes over the last couple decades regarding division and seeding, the same basic format has persisted. In this system, each conference sends its top eight teams to play in a bracket-style tournament consisting of three best-of-seven rounds in order to crown a conference champion. Then, the conference champions face off in a seven game series to name an NBA Champion. This format is simulated in the "current.format.sim.R" script.

However, there have been alternate playoff formats proposed to make them more exciting and fair. The first of these formats sends, again, each conference's top eight teams into a 16 team bracket tournament where the #1 overall seed faces the #16 overall seed, #2 faces #15, etc. in the first round. This strays from the current format as there are no "conference champions" crowned (in the postseason at least, it is likely each conference's #1 seed would assume this title after the regular season), rather east and west teams can play eachother prior to the NBA Finals. This would allow for the #1 seed to play the team that truly was the last to earn playoff berth, as opposed to maybe the #13 or 14 overall seed if the other conference had a weaker season. This format is simulated in the "8west8east.format.sim.R" script. The third and final format simulated in this repository is on that doesn't always differ from the format that was previously described, but is widely considered one that should be employed. In the "16team.format.sim.R" scipt, the top 16 teams in the NBA regardless of conference are given playoff berths. This means that the west could have nine or team ten teams in the postseason, while the east would only have seven or six, respectively. The last time this scenario arose was in the 2017/18 season in which the Denver Nuggets where in ninth place in the west after regular season play – and therefore didn't make the playoffs – while the team had a better record than three eastern conference teams that were the sixth (Miami Heat), seventh (Milwaukee Bucks), and eighth (Washington Wizards) seeds in the east. Under this new proposed format, the Nuggets would have been the 14th overall seed in the postseason and the Wizards would've missed the postseason by one game. This format ensures that the leagues best 16 teams earn the right to compete in the playoffs, rather than the berths be equally divided between conferences. While there would disputes around the merit/point of having conferences and divisions if this system were employed, it provides the best teams with what they deserve, regardless of if their conference opponents also have strong seasons or not.

Script run order:
1. get.scores.R
2. create.model.R
3. current.format.sim.R
4. 8west8east.format.sim.R
5. 16team.format.sim.R
