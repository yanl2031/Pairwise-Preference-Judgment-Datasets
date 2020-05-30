Originally provided by IMDb. (See: http://www.imdb.com/interfaces)
Reproduced by Yan Li in 2017.

-1- DATA CONTENT

Movie.csv contains 1225 rows, each representing a distinct movie. Each row starts with an integer, indicating the total number of user ratings received for the movie. The integer is then followed by a vector of 10 integers, which is a coded 10-bin histogram representing the distribution of the ratings. Specifically, the i-th code being c means that 10c% ~ (10c+9)% of the ratings to this movie are i (i=1,2,...,10).

-2- LICENSE

Freely available for research use when acknowledged with the following reference:
      Crowdsourced top-k queries by confidence-aware pairwise judgments,
      Ngai Meng Kou, Yan Li, Hao Wang, Leong Hou U, and Zhiguo Gong, 
      SIGMOD, 2017.
