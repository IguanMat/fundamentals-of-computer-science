## Project 
• Using the downloadable file from:   
https://dati.istruzione.it/opendata/opendata/catalogo/elements1/ALUCORSOINDCLASTA20192020200831.json  
• Build functions for:  
  • Given a school code, provide the number of boys and girls  
    ▪ Syntax: genere_scuola(dataset, cod_scuola) → (M, F)  
  • Given a school order, provide the number of boys and girls  
    ▪ Syntax: genere_ordine(dataset, ord_scuola) → (M, F)  
  • Calculate the number of different schools in Italy (using the school code)  
    ▪ Syntax: conta_scuole(dataset)  
  • Given a school order and a class course year return the total number of students:  
    ▪ Syntax: conta_studenti_classe(dataset, ordine, anno)  
  • Graph the distribution of students for the 3 school orders  
    ▪ Syntax: tortaordini(dataset)  
  • Calculate the number of all students by gender  
    ▪ Syntax: conta_studenti(dataset) → (M, F)  
  • Save all data to a file in csv format  
  
  -I added an optional menu at the end just to call up all the functions more easily-
