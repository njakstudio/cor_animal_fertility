# cor_animal_fertility
COR mod that changes that replaces the random animal birth mod

How many farmlands you have now affects animal fertility rates. 

        window.corApi.ANIMAL_FERTILITY_TIERS = window.corApi.ANIMAL_FERTILITY_TIERS || [
            { min: 50, mult: 2.2 },
            { min: 35, mult: 1.8 },
            { min: 20, mult: 1.5 },
            { min: 10, mult: 1.25 },
            { min: 5,  mult: 1.1 },
        ];

# Dependencies
cor_api
