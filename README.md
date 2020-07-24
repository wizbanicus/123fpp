# 123 fpp

This project is aimed at subverting the flawed First Past the Post voting system by implementing RCV (Ranked Choice Voting).

Here is how it works
- Admin creates a page for an FPP election.
  - page includes:
    - election - who is being elected for what?
    - where is the election
    - links to officicial election details
    - names of all candidates
    - cutoff date and time for the election (before beginning of election)
    - threshold to win
    
- people can visit the page and confirm they are eligible to vote in the election
  - voters then enter their email address and recieve a confirmation email including one time link
  - after clicking the link they are taken to the election page.
  - user then ranks choices (only 3 options) They are advised to list only 3 options who they would be willing to vote for in an FPP election.
  
- at the end of the time (just before actual election), votes close
  - all participants are emailed a link of the results.
  - participants can view results in each round of the RCV vote.
  - if any candidate passes the threshold to win, voters are advised that if they included this candidate as one of the 3, 
  they should probably vote for them in the FPP election

## will it work?
- I dunno, it might be that there are not enough voters who are interested however it may be especially valuable in FPP elections with very low turnout (eg council elections) as the people that do vote may be more interested.
