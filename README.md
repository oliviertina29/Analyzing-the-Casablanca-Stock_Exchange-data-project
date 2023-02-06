# Python_project : Analyzing the Casablanca Stock Exchange data project

A brief description of the project goes here. This could include what the project does, who it's intended for, etc.

## Getting Started

 First of all, we downloaded financial data from Casa Stock Exchange for these Banks: 
 
    - Attijariwafa Bank 
    - Bank Of Africa
    - BCP : Banque Centrale Populaire
    - BMCI :  Banque Marocaine pour le Commerce et l'Industrie
    - CIH BANK 
    
    
    
For all these banks we converted the data to .csv file using the function "fichier_csv"(More details are provided bellow).



In the "Bourse_Casablanca.ipynb" file you can see all the code. It contains :
- A function named "fichier_csv" that take a .aspx file and provide a .csv file
- A class named "Stock" in which we have the following methods :
    - visualization() : it provides a graphic representation of columns 'closing' named 'price' and 'volume' for the used-dataset.
    - max_value() : it provides the highest value of the 'closing' column.
    - min_value() : it provides the lowest value of the 'closing' column.
    - max_volume() : it provides the highest value of the 'volume' column.
    - max_quantity() : it provides the highest value of the 'quantity' column.
    - momentum(N) : it provides a vector of momentum value of the 'closing' column given a vector N.
    - simple_moving_average(k) : it provides the moving average of the 'closing' column given k(which is the number of neighbour points we want to take) 
    - visualization2() : it provide the same graphics like method visualization but it add the representation of the momentum and the moving average.



After that we call all the methods using the data Bank of Africa dataset.
Everything works well but the graphics are not available on github. 

To run correctly the code, you can clone the repository and open the .ipynb file in jupyter notebook (the .aspx file and the .ipynb 
should be in the same folder else you should change the path in the function).

