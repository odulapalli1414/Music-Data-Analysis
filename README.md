# 🎶 Music Database Analysis Project

Welcome to my **Music Database Analysis Project**! This project delves into customer spending, artist popularity, top genres, and various insights from a dataset using **SQL**. 

Through complex queries involving **Joins**, **Window Functions**, **Subqueries**, and **Aggregate Functions**, I've explored customer behavior, artist trends, and genre preferences, providing business insights for music-related decision-making.

---

## 📊 Key Insights

### 1. **Top Customers & Best Cities for Revenue** 💸
- **Best Customer:** Identified the customer who spent the most.
- **Top City for a Music Festival:** Analyzed total invoice amounts to reveal the city with the highest revenue potential.

### 2. **Most Popular Artists & Tracks** 🎤
- **Top 10 Rock Artists:** Revealed the leading rock bands based on track count.
- **Longest Tracks:** Identified tracks longer than the average song length, sorted by duration.

### 3. **Genre & Country Preferences** 🌍
- **Top Genre by Country:** Uncovered the most popular music genres for each country based on sales.
- **Most Profitable Countries:** Found the countries generating the highest invoice counts.

### 4. **Customer-Artist Spending** 🎧
- **Amount Spent on Artists:** Tracked how much each customer spent on their favorite artists.
- **Top-Selling Artists:** Pinpointed the highest-earning artists from customer purchases.

---

## ❓ Questions Answered in This Project

**Note:** Before attempting to answer the questions outlined in this project, please ensure that you have successfully imported the `Music_Store_database.sql` file from this repository. This SQL file contains all the necessary tables and data required to execute the queries and obtain the desired results.

### Question Set 1 - Easy

1. **Who is the senior-most employee based on job title?**
2. **Which countries have the most invoices?**
3. **What are the top 3 values of total invoice amounts?**
4. **Which city has the best customers?** We plan to throw a promotional Music Festival in the city where we made the most money. Query returns the city with the highest sum of invoice totals.
5. **Who is the best customer?** The customer who has spent the most money will be declared the best customer.

### Question Set 2 - Moderate

1. **Email, First Name, Last Name & Genre of all Rock Music Listeners** - List ordered alphabetically by email.
2. **Top 10 Rock Bands** - Query returns the artist name and total track count of the most prolific rock artists.
3. **Tracks Longer than Average Song Length** - List of tracks with song lengths greater than the average, ordered by duration.

### Question Set 3 - Advanced

1. **Amount Spent by Each Customer on Artists** - Query returns customer name, artist name, and total amount spent.
2. **Amount Spent by Each Customer on Top-Selling Artists** - Query returns customer name, artist name, and total spent on the highest-selling artists.
3. **Most Popular Genre by Country** - Query returns the genre with the highest purchases in each country.
4. **Top-Spending Customer by Country** - Query returns the top customer and amount spent for each country, with ties accounted for.

---

## 💻 SQL Features Utilized

- **Complex Joins:** Leveraged multi-table joins to connect customers, invoices, tracks, albums, and genres.
- **Window Functions:** Used for ranking, partitioning data by country, and identifying top customers and genres.
- **Subqueries & CTEs:** Structured complex logic with **Common Table Expressions (CTEs)** for better readability and efficiency.
- **Aggregate Functions:** Summed up purchases, invoices, and track lengths to derive meaningful insights.

---

## 📚 Project Structure

- **Queries:** A collection of well-structured SQL queries answering business-critical questions.
- **Insights:** Key findings related to customer behavior, artist popularity, and genre trends.
  
**Database Schema**

![Schema](https://github.com/user-attachments/assets/7a894252-2b6b-44b4-8d45-d56165ec2f5b)


---

## 🛠️ Technologies Used

- **SQL**: For crafting the queries.
- **PostgreSQL**: Database platform used.
- **GitHub**: Project hosting.

---

## 🤝 Connect with Me

- 💼 [LinkedIn](https://www.linkedin.com/in/odulapalli-hitesh/)
- 📝 [Portfolio](https://odulapalli1414.github.io/hitesh/)

Thank you for visiting! Feel free to explore the queries and reach out if you have any questions!
