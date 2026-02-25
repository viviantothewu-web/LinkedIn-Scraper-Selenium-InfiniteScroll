# LinkedIn Jobs Scraper (Selenium & Automation)

This project utilizes **Selenium WebDriver** to navigate LinkedIn's dynamic, JavaScript-heavy interface. It demonstrates the ability to automate browser interactions, bypass authentication, and extract high-volume data from infinite-scrolling pages.

## 🚀 Advanced Automation Features
* **Browser Orchestration:** Integrated `ChromeDriver` with Selenium to simulate human browsing behavior.
* **Infinite Scrolling:** Implemented a recursive scroll function to trigger JavaScript lazy-loading and capture up to 40+ job entries.
* **Session Management:** Developed a secure login script for authenticated scraping.
* **Regex Extraction:** Leveraged Regular Expressions (RE) to identify specific technical requirements (e.g., "AWS") within job descriptions.

## 📊 Data Insights & Analysis
* **Automated Data Pipeline:** Cleaned and structured raw scraped data into specialized CSV reports.
* **Visualization:** Analyzed the correlation between company size (number of employees) and follower counts/salary ranges.
* **Skills Identification:** Isolated job titles requiring specific cloud competencies (AWS).

## 📂 Project Structure
* `Infinite_Scrolling.csv`: Raw data captured during automated scroll.
* `Data_Scientist_Jobs.csv`: Targeted dataset for Data Science roles.
* `Jobs_AWS_Skills.csv`: Filtered technical skills report.
