# Web Scraping Tutorial

## Course Objectives

By the end of this course, you will be able to:

1. **Set Up a Python Environment:**Learn how to create and manage a virtual environment using [`venv`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22external%22%3A%22file%3A%2F%2F%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22path%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A11%2C%22character%22%3A63%7D%7D%5D%2C%225d58ec3e-218b-457c-a78e-c027ad5abc83%22%5D "Go to definition"), ensuring that your web scraping projects are isolated and dependencies are handled efficiently.
2. **Scrape Websites Efficiently:**Master the essential techniques for web scraping using Python libraries such as [`requests`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22external%22%3A%22file%3A%2F%2F%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22path%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A14%2C%22character%22%3A84%7D%7D%5D%2C%225d58ec3e-218b-457c-a78e-c027ad5abc83%22%5D "Go to definition") and [`BeautifulSoup`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22external%22%3A%22file%3A%2F%2F%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22path%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A14%2C%22character%22%3A99%7D%7D%5D%2C%225d58ec3e-218b-457c-a78e-c027ad5abc83%22%5D "Go to definition").
3. **Inspect and Analyze Web Pages:**Develop skills in inspecting web pages using tools like SelectorGadget to identify the correct HTML elements and CSS selectors for scraping.
4. **Automate Web Scraping Tasks:**Automate the scraping process by setting up a GitHub repository and creating a GitHub Action with a CRON job.
5. **Build Dynamic Web Applications:**
   Use Streamlit to create interactive web applications that display your scraped data in a user-friendly format.

## Course Structure

The course is divided into six chapters, each focusing on different aspects of web scraping and related technologies:

### Chapter 01: Introduction and Purpose

- Overview of the course
- Setting up the Python environment
- Introduction to web scraping

### Chapter 02: Basic Web Scraping

- Using [`requests`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22external%22%3A%22file%3A%2F%2F%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22path%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A14%2C%22character%22%3A84%7D%7D%5D%2C%225d58ec3e-218b-457c-a78e-c027ad5abc83%22%5D "Go to definition") to fetch web pages
- Parsing HTML with [`BeautifulSoup`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22external%22%3A%22file%3A%2F%2F%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22path%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2F01-intro.qmd%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A14%2C%22character%22%3A99%7D%7D%5D%2C%225d58ec3e-218b-457c-a78e-c027ad5abc83%22%5D "Go to definition")
- Extracting data from simple websites

### Chapter 03: Advanced Web Scraping Techniques

- Handling complex websites
- Extracting structured data from tables
- Dealing with pagination and dynamic content

### Chapter 04: Inspecting and Analyzing Web Pages

- Using browser developer tools
- Identifying HTML elements and CSS selectors
- Tools like SelectorGadget

### Chapter 05: Automating Web Scraping

- Setting up a GitHub repository
- Creating GitHub Actions
- Scheduling tasks with CRON jobs

### Chapter 06: Building Interactive Web Applications

- Introduction to Streamlit
- Creating dynamic web apps
- Displaying scraped data interactively

## Getting Started

To get started with the course, clone this repository and follow the instructions in each chapter's README file.

```bash
git clone https://github.com/yourusername/web-scraping-course.git
cd web-scraping-course
```

## Prerequisites

- Basic knowledge of Python
- Familiarity with HTML and CSS
- Git and GitHub account

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a pull request.

## License

This project is licensed under the MIT License. See the [`LICENSE`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FUsers%2Fjonathanjayes%2FDocuments%2FDataScience%2Fwebscraping-tutorial%2FLICENSE%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%225d58ec3e-218b-457c-a78e-c027ad5abc83%22%5D "/Users/jonathanjayes/Documents/DataScience/webscraping-tutorial/LICENSE") file for details.

---

Feel free to adjust the content as needed.
