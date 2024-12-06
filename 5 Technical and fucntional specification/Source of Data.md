When **azn.day.az** updates its database with exchange rates "from the servers of banks," this likely involves the following technical processes:

1. **Public APIs or Web Services**:  
   Many banks provide publicly accessible APIs or web services that share real-time data, such as exchange rates. These APIs allow external platforms like azn.day.az to request and retrieve up-to-date currency information in a structured format (e.g., JSON or XML).

2. **Web Scraping**:  
   If APIs are not available, the site might use web scraping techniques to extract data directly from the exchange rate pages of bank websites. This involves automated scripts that fetch and parse HTML content to extract relevant data fields.

3. **FTP Servers or Feeds**:  
   Some banks may offer currency rate data via FTP servers or syndicated feeds (like RSS or XML). These are periodically updated by the banks, and azn.day.az may pull this data at regular intervals.

4. **Data Aggregators**:  
   Instead of direct integration with each bank, azn.day.az might use third-party aggregators that collect and consolidate exchange rate data from multiple banks, providing it through a single API or feed.

5. **Direct Partnerships**:  
   In some cases, azn.day.az might have direct partnerships with banks, giving them access to proprietary or internal systems that publish exchange rate data.

6. **Database Storage and Synchronization**:  
   The retrieved data is stored in a database on azn.day.az's servers. This database is synchronized and updated at intervals (e.g., every 10 minutes) to ensure the data reflects the latest rates.

### Key Considerations:
- **Source of Data**: The specific implementation depends on whether the banks in Azerbaijan offer open APIs, proprietary tools, or require third-party solutions.
- **Accuracy and Latency**: There could be a slight delay depending on the update frequency of the banks or their systems.
- **Compliance and Permissions**: To ensure lawful operations, azn.day.az must comply with the terms of use or agreements set by the data sources (banks or aggregators).