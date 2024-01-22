# nosql-challenge
:

### Database and Jupyter Notebook Set Up
The "establishments.json" file was imported into the MongoDb database named "uk_food" with a collection named "establishments". Then a new document halal restaurant document, "Penang Flavours," was added to the database. A query to update the BussinesTypeID was carried out and all establishments in Dover were removed.

### Part 3: Exploratory Analysis
1. **Hygiene Score of 20:**
   - Found establishments with a hygiene score of 20.
   - Displayed the first document, converted the result to a Pandas DataFrame, and displayed the first 10 rows.

2. **London Establishments with RatingValue >= 4:**
   - Found establishments in London with a RatingValue greater than or equal to 4.
   - Displayed the first document.

3. **Top 5 Establishments with RatingValue of 5, Sorted by Hygiene Score Near "Penang Flavours":**
   - Searched for establishments with a RatingValue of 5 within a certain distance of the new restaurant.
   - Sorted the results by hygiene score.
   - Displayed the first 5 documents, converted the result to a Pandas DataFrame, and displayed the first 10 rows.

### Data Cleaning and Type Conversion
- Converted latitude and longitude values to decimal numbers using `update_many`.
- Set non-numeric Rating Values to null.
- Converted RatingValues and Hygiene scores to integer numbers.

