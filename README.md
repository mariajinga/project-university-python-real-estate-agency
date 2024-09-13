# **Real Estate Company Database Management Project / Proiect de Gestionare a Bazei de Date pentru o Companie Imobiliară**

*******************************************************
### *IMPORTANT*
*This project was developed by me during my time at university and was created using online resources and domain-specific books as sources of inspiration. The goal of this project was to explore and learn through practical examples, combining various information and techniques found in these resources to bring it to completion. I would like to mention that the source code of this project is posted on GitHub, but it is set to private to avoid any form of plagiarism, as it is the result of my own personal work.*

*Acest proiect a fost realizat de mine în timpul facultății și a fost creat folosind resurse de pe internet și cărți de specialitate drept surse de inspirație. Scopul acestui proiect a fost să explorez și să învăț prin intermediul unor exemple practice, combinând diverse informații și tehnici găsite în aceste resurse pentru a-l aduce la bun sfârșit. Menționez că codul sursă al acestui proiect este postat pe GitHub, dar este setat pe privat pentru a evita orice formă de plagiat, deoarece este rezultatul muncii mele personale.*
*******************************************************

This project aims to efficiently manage a real estate company's database, facilitating real estate transactions between clients and owners through agents across the country. The main goal is to provide a centralized and easily accessible solution for all parties involved in real estate transactions, thereby improving customer experience and agent efficiency.                     
Acest proiect își propune să gestioneze eficient baza de date a unei companii imobiliare, facilitând tranzacțiile imobiliare între clienți și proprietari prin agenți din toată țara. Scopul principal este de a oferi o soluție centralizată și ușor accesibilă pentru toate părțile implicate în tranzacțiile imobiliare, îmbunătățind astfel experiența clienților și eficiența agenților.

## **Descrierea Tabelelor / Table Descriptions**

1. **Tabela Agenți / Agents Table**  
   Conține informații despre agenții companiei imobiliare, inclusiv nume, prenume, rang, procentul de comision, data angajării și alte detalii relevante. Scopul utilizării acestui fișier în codul meu este de a gestiona și analiza performanța agenților în ceea ce privește numărul de tranzacții finalizate și veniturile generate.  
   Contains information about the company's real estate agents, including name, surname, rank, commission percentage, hiring date, and other relevant details. This table is used in my code to manage and analyze the performance of agents in terms of the number of completed transactions and the revenues generated.

2. **Tabela Clienți / Clients Table**  
   Conține detalii despre clienții care doresc să achiziționeze sau să vândă proprietăți prin intermediul companiei imobiliare. Informațiile includ nume, prenume, adresa, numărul de telefon și alte detalii relevante. Codul meu utilizează acest fișier pentru a gestiona și analiza preferințele și cererile clienților, precum și pentru a identifica tendințele în comportamentul acestora.  
   Contains details about clients who wish to buy or sell properties through the real estate company. Information includes name, surname, address, phone number, and other relevant details. My code uses this table to manage and analyze client preferences and requests, as well as to identify trends in their behavior.

3. **Tabela Proprietari / Owners Table**  
   Conține informații despre proprietarii de imobile care au încredințat companiei imobiliare gestionarea și promovarea proprietăților lor. Detaliile includ numele proprietarului, adresa, informații de contact și alte detalii relevante. Utilizarea acestui tabel permite monitorizarea și gestionarea eficientă a relațiilor cu proprietarii și a portofoliului de proprietăți administrate de companie.  
   Contains information about property owners who have entrusted the real estate company with managing and promoting their properties. Details include the owner's name, address, contact information, and other relevant details. This table is used to monitor and efficiently manage relationships with owners and the portfolio of properties managed by the company.

4. **Tabela Contracte / Contracts Table**  
   Conține informații despre contractele încheiate între clienți și proprietari, intermediat de agenții companiei imobiliare. Detaliile contractelor, cum ar fi valoarea contractului, data încheierii și alte informații relevante, sunt utilizate pentru analiza performanței agenților și pentru evaluarea eficacității companiei în încheierea tranzacțiilor.  
   Contains information about contracts signed between clients and owners, mediated by the company's agents. Contract details, such as contract value, signing date, and other relevant information, are used to analyze agent performance and assess the company's effectiveness in closing transactions.

5. **Tabela Imobile / Properties Table**  
   Conține detalii despre proprietățile disponibile pentru vânzare sau închiriere, inclusiv adresa, suprafața, prețul, data construirii și alte informații relevante. Aceste date sunt utilizate pentru a identifica tendințele în piața imobiliară și pentru a oferi clienților informații actualizate despre proprietățile disponibile.  
   Contains details about properties available for sale or rent, including address, area, price, construction date, and other relevant information. These data are used to identify trends in the real estate market and provide clients with up-to-date information about available properties.

6. **Tabela Rang / Rank Table**  
   Conține detalii despre diferitele ranguri ale agenților din cadrul companiei imobiliare, cum ar fi rangul, comisionul standard asociat fiecărui rang și alte detalii relevante. Utilizarea acestui tabel permite analiza și evaluarea performanței agenților în funcție de rangul lor, precum și ajustarea strategiilor de comisionare pentru a maximiza eficiența și profitabilitatea companiei.  
   Contains details about the different ranks of agents within the real estate company, such as rank, standard commission associated with each rank, and other relevant details. This table is used to analyze and evaluate agent performance according to their rank, as well as to adjust commission strategies to maximize efficiency and profitability.

## **Elemente Utilizate în Cod / Elements Used in Code**

- **Utilizarea Pachetului Pandas / Use of Pandas Package**  
  Folosesc biblioteca pandas pentru a încărca și manipula fișierele CSV, realizând diverse operații de prelucrare a datelor, cum ar fi gruparea, agregarea și filtrarea.  
  I use the Pandas library to load and manipulate CSV files, performing various data processing operations such as grouping, aggregation, and filtering.

- **Analiza Datelor / Data Analysis**  
  Prin intermediul codului, realizez analiza datelor pentru a identifica tendințele și modelele în comportamentul clienților, performanța agenților și în piața imobiliară în general.  
  Through the code, I perform data analysis to identify trends and patterns in customer behavior, agent performance, and the real estate market in general.

- **Clusterizare / Clustering**  
  Folosind algoritmi de clusterizare, cum ar fi K-means, am încercat identificarea grupurilor sau segmentelor de clienți sau proprietăți, pentru a oferi recomandări personalizate și a îmbunătăți strategiile de marketing și vânzare.  
  Using clustering algorithms like K-means, I attempt to identify groups or segments of clients or properties to offer personalized recommendations and improve marketing and sales strategies.

- **Regresie Multiplă / Multiple Regression**  
  Prin regresia multiplă, am identificat relații și corelații între diferite variabile (cum ar fi prețul unei proprietăți și caracteristicile sale), pentru a înțelege mai bine factorii care influențează prețurile și pentru a face previziuni mai precise.  
  Through multiple regression, I identify relationships and correlations between different variables (such as property price and its characteristics) to better understand the factors that influence prices and make more accurate predictions.

By combining data from these CSV files and using algorithms and methods from the Pandas, scikit-learn, and statsmodels packages, my project for the "software packages" course aims to provide a deeper and more accurate understanding of the real estate market and improve property trading and management processes.

## **Programare PYTHON / Python Programming Overview**

- **Utilizarea listelor și a dicționarelor, incluzând metode specifice acestora / Usage of Lists and Dictionaries, including their specific methods**
- **Utilizarea seturilor și a tuplurilor, incluzând metode specifice acestora / Usage of Sets and Tuples, including their specific methods**
- **Definirea și apelarea unor funcții / Defining and Calling Functions**
- **Utilizarea structurilor condiționale / Using Conditional Structures**
- **Utilizarea structurilor repetitive / Using Repetitive Structures**
- **Importul unei fișiere CSV sau JSON în pachetul pandas / Importing a CSV or JSON file into the Pandas Package**
- **Accesarea datelor cu `.loc` și `.iloc` / Accessing Data with `.loc` and `.iloc`**
- **Modificarea datelor în pachetul pandas / Modifying Data in the Pandas Package**
- **Utilizarea funcțiilor de grup / Using Group Functions**
- **Tratarea valorilor lipsă / Handling Missing Values**
- **Ștergerea de coloane și înregistrări / Deleting Columns and Records**
- **Prelucrări statistice, gruparea și agregarea datelor în pachetul pandas / Statistical Processing, Grouping, and Aggregation of Data in the Pandas Package**
- **Prelucrarea seturilor de date cu merge / join / Processing Datasets with Merge / Join**
- **Reprezentare grafică a datelor cu pachetul matplotlib / Graphical Representation of Data with the Matplotlib Package**
- **Utilizarea pachetului scikit-learn (clusterizare, regresie logistică) / Using the Scikit-Learn Package (Clustering, Logistic Regression)**
- **Utilizarea pachetului statmodels (regresie multiplă) / Using the Statsmodels Package (Multiple Regression)**

![14](https://github.com/user-attachments/assets/4924cde1-91c6-482a-aa2b-b11ee5170823)
*******************************************************
<center>
![15](https://github.com/user-attachments/assets/b4d7ee3d-a56a-406c-9973-fd0f27d4f98a)
</center>

---
