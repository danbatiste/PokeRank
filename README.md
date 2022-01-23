# PokeRank
Ranks all Pokémon. To see the sorted rankings, open any of the .csv files under /rank_data_(gen)
Includes Pokémon from generations 1-7.

# Pokémon are ranked by:
How many Pokémon they are strong attackers against (att_pros)
How many Pokémon they are poor attackers against (att_cons)
How many Pokémon they tie in an attack (att_draws)

How many Pokémon they are strong defenders against (def_pros)
How many Pokémon they are poor defenders against (def_cons)
How many Pokémon they tie in defense (def_draws)




# Current issues:
If the type of a pokemon has changed in new generations, the program mixes the old and new types. Example: Sandshrew - ground, ice

Uses type strengths/weaknesses of gen 8, despite the gen chosen by the user.

Compares the Pokémon to itself (though this makes sense, Pokémon will fight against themselves sometimes)

