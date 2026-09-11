# cine-python
##  Cinema Ticketing System V1

### Match-case checks
This program uses a basic match-case to check the chosen movie, it's rate and price, all inside the main function with the separate function called ´busca-filme´(search-movie), that uses the match-case way.

### How it works
It asks you to input the movie's name, and right after calls the busca-filme function.

If the function doesn't return anything, it prints "Filme não encontrado" (Movie not found). Else, it unpacks the price and rate from the function and checks whether the user age matches the movie rate, if so, then it checks if you are a student or not, if you're student, you get 50% off, else you pay full price. Now if your age doesn't match the minimum rate for the movie, the program print "Acesso negado. Idade insuficiente para assistir o filme" (Access denied. Age insufficient to watch the movie)


