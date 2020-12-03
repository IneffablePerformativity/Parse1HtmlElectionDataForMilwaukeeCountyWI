# Parse1HtmlElectionDataForMilwaukeeCountyWI

CONCLUSIONS:
1. THE BLACK X'S (SORTED TO THE RIGHT) MARK 223 BIGGEST SPOTS OF THEFT OVER 2% WORTH 18426 VOTES. SEE LOG FOR LOCALITY NAMES.
2. FOR FAIRNESS, ANY WHITE X'S (SORTED TO THE LEFT) MARK 42 OPPOSITE BONUSES OVER 2% FAVORING TRUMP WORTH 827 VOTES.
3. BIDEN BONUS = PLUS 2.77%, StdDev 2.22; TRUMP BONUS = PLUS 0.02%, StdDev 2.76


/*
 * Parse1HtmlElectionDataForMilwaukeeCountyWI.cs
 *
 * which code and results I will archive at:
 * https://github.com/IneffablePerformativity
 * https://github.com/IneffablePerformativity/Parse1HtmlElectionDataForMilwaukeeCountyWI
 * 
 * "To the extent possible under law, Ineffable Performativity has waived all copyright and related or neighboring rights to
 * The C# program Parse1HtmlElectionDataForMilwaukeeCountyWI.cs and resultant outputs.
 * This work is published from: United States."
 * 
 * This work is offered as per license: http://creativecommons.org/publicdomain/zero/1.0/
 * 
 * 
 * Goal: to demonstrate any inverse republicanism::trump relationship
 * as was described for Milwaukee County Wisconsin in an article at:
 * https://www.thegatewaypundit.com/2020/11/caught-part-3-impossible-ballot-ratio-found-milwaukee-results-change-wisconsin-election-30000-votes-switched-president-trump-biden/
 * 
 * to wit, visually:
 * https://www.thegatewaypundit.com/wp-content/uploads/2020-Milwaukee-Hockey-Stick-Chart.jpg
 * 
 * Or rather now, a systematic "BONUS TO BIDEN" and "THEFT FROM TRUMP"
 * by comparing RED and BLUE % for POTUS vs. SENUS and/or REPUS races.
 * 
 * 
 * possibleConclusionText BIDEN BONUS = PLUS 2.77%, StdDev 2.22; TRUMP BONUS = PLUS 0.02%, StdDev 2.76
 * 
 * finalConclusion = THE BLACK X'S (SORTED TO THE RIGHT) MARK 223 BIGGEST SPOTS OF THEFT OVER 2% WORTH 18426 VOTES. SEE LOG FOR LOCALITY NAMES.
 * 
 * flipsideConclusion = FOR FAIRNESS, ANY WHITE X'S (SORTED TO THE LEFT) MARK 42 OPPOSITE BONUSES OVER 2% FAVORING TRUMP WORTH 827 VOTES.
 * 
 * 
 * Parsing the HTML page from:
 * https://county.milwaukee.gov/EN/County-Clerk/Off-Nav/Election-Results/Election-Results-Fall-2020
 * 
 * 
 * There is a series of similar programs building upon one another,
 * named similarly, with XML inputs, HTML inputs, PDF-as-TXT input,
 * and some ugly earlier versions, all to be found at GitHub, here:
 * https://github.com/IneffablePerformativity
 * 
 * 
 * I am now pouring back the ~7th generation code (South Carolina)
 * to revise my 1st generation (Milwaukee County WI) task attempt.
 * 
That original project is also still on GitHub, here:
https://github.com/IneffablePerformativity/VISIBLE-PROOF-OF-POTUS-2020-ELECTION-FRAUD
 * 
 * also note, I manually compress final image at tinypng.com
 */
