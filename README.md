# ⚽ Football Player Market Value Analysis

This short project explores the market values of professional football players by scraping data from [Transfermarkt](https://www.transfermarkt.com/) and analyzing it using Python (Pandas, Matplotlib).

The goal is to extract and analyze player attributes such as age, nationality, position, club, and estimated market value — and to identify trends among top-valued players.

---

## 🛠️ What This Project Includes

- Web scraping using `requests` and `BeautifulSoup`
- Data preprocessing and cleanup with `pandas`
- CSV exports of player value data (`transfermarkt25.csv`, `transfermarkt50.csv`)
- Basic data analysis and visualization (top positions, team distributions, nationality trends)

---

## 📊 Example Result

| # | Name             | Position           | Age | Nation  | Team               | Value    |
|---|------------------|--------------------|-----|---------|--------------------|----------|
| 1 | Erling Haaland   | Centre-Forward     | 23  | Norway  | Manchester City    | €180.00m |
| 2 | Kylian Mbappé    | Left Winger        | 24  | France  | Paris Saint-Germain| €180.00m |
| 3 | Jude Bellingham  | Attacking Midfield | 20  | England | Real Madrid        | €150.00m |
| ... | ...            | ...                | ... | ...     | ...                | ...      |
