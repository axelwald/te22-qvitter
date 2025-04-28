

Jag gjorde de mest bare minimum för att få en funktionell EDIT funktion och en DELETE funktion för alla tweets

Tweetsen sparas i en databas, och edit och delete direkt alterar databasen, vilket kan vara en säkerhetsrisk med tanke på att det finns inget emellan och det gör en direkt sql operation på databasen

Routesen fungerar genom att runna viss kod med information som blir passad vidare genom användingen av nunjucks och express och sen blir den information "pushad" till databsen så att webbsidan läser in tweetsen 

Tyckte det gick bra, men blev lite förvirrande ibland