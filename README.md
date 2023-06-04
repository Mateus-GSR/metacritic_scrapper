 <h1>Project README</h1>
  <h2>Movie Data Scraping from Metacritic</h2>
  <p>This project is focused on scraping movie data from Metacritic using Python. The code provided demonstrates the process of scraping movie information such as title, director, genres, ratings, runtime, cast, distributor, release date, summary, metascore, userscore, and related ratings.</p>
  <h3>Prerequisites</h3>
  <p>To run this code, you need to have the following dependencies installed:</p>
  <ul>
    <li>Python 3.x</li>
    <li>Beautiful Soup (`bs4`)</li>
    <li>pandas</li>
    <li>requests</li>
  </ul>
  <p>You can install these dependencies using pip by running the following command:</p>
<code>pip install beautifulsoup4 pandas requests</code>

  <h3>Usage</h3>
  <p>The code consists of two main parts:</p>
  <ol>
    <li>
      <strong>Scraping movie URLs:</strong>
      <ul>
        <li>The first part of the code scrapes the URLs of movies from multiple pages on Metacritic. It utilizes the <code>requests</code> library to send GET requests to the website and <code>BeautifulSoup</code> to parse the HTML content.</li>
        <li>The movie names and corresponding hrefs are extracted and stored in separate lists.</li>
        <li>The extracted data is then saved to a CSV file named "movies_href.csv".</li>
      </ul>
    </li>
    <li>
      <strong>Scraping movie metadata:</strong>
      <ul>
        <li>The second part of the code iterates over each movie URL and extracts various metadata using the functions provided.</li>
        <li>The extracted data is stored in a list of dictionaries, where each dictionary represents the metadata of a single movie.</li>
        <li>Finally, the obtained data is saved to a CSV file named "movies_metadata_metacritic.csv".</li>
      </ul>
    </li>
  </ol>
  <p>To use this code, follow these steps:</p>
  <ol>
    <li>Ensure that the required dependencies are installed.</li>
    <li>Copy the provided code into a Python script or Jupyter Notebook.</li>
    <li>Run the code.</li>
    <li>Once completed, you will have two CSV files: "movies_href.csv" containing the scraped movie URLs and "movies_metadata_metacritic.csv" containing the scraped movie metadata.</li>
  </ol>
  <p>Please note that scraping websites may be subject to legal restrictions, and you should ensure that you comply with the website's terms of service and relevant laws and regulations.</p>
</body>
</html>
