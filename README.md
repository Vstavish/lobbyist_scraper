# lobbyist_scraper

This web scraper pulls information from the 2022-23 lobbying registration session from this website: 

https://lobby-ethics.maryland.gov/public_access?filters%5Bar_date_end%5D=&filters%5Bar_date_start%5D=&filters%5Bar_lobbying_year%5D=2022&filters%5Bc_date_end%5D=&filters%5Bc_date_start%5D=&filters%5Bc_lobbying_year%5D=&filters%5Bdate_selection%5D=Lobbying+Year&filters%5Bemployer_name%5D=&filters%5Blar_date_end%5D=&filters%5Blar_date_start%5D=&filters%5Blar_lobbying_year%5D=&filters%5Blobbying_year%5D=2022&filters%5Breport_type%5D=Activity+Reports&filters%5Breports_containing%5D=&filters%5Bsearch_query%5D=&page=1

I first loop through and grab each link on each page. Then I scrape all the links I grabbed for the exact information I want. I primarily wanted to see who was employing lobbysist, the specific bills mentioned and the specific topics and descriptions used in these registrations. 

