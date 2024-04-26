Title:
Oscars vs Goyas - Directors -Sex

Description:
Is about taking data from two different web scraping made from Wikepedia and gathering info about Directors sex using Gender Guesser library

Structure:
1 - Oscars_Gian_Romano.ipynb - Web scraping to take data from Oscar's best movie award -Directors from Wikipedia
2 - Goyas_Gian_Romano.ipynb - Web scraping to take data from Goya's best movie award -Directors from Wikipedia
3 - Gender_Guesser_Gian_Romano.ipynb - Using Python library Gender Guesser to retieve the director's sex

Execution Flow:
First, I web-scraped both Wikipedia pages, one for the Oscars and one for the Goyas. These tables list the best movies for all the different editions.



![Image](https://github.com/users/gianromano/projects/1/assets/166392007/eb0f0bf8-4369-41b2-a0f9-55dd75aacd72)



![Image](https://github.com/users/gianromano/projects/1/assets/166392007/72f19ee9-227f-4754-bcbc-c9b8edd8673c)



After populating dataframes and csv files with the data obtained, we pass all director names through the gender guesser function.



![Image](https://github.com/users/gianromano/projects/1/assets/166392007/cc3e5f86-3b4f-4ab6-96d5-dadcce9dc645)


After gathering information from the Gender Guesser function, I perform the needed actions to calculate percentaje.

Then I show the results in the slide presentation.
