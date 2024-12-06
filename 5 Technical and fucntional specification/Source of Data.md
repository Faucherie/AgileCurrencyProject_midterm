# Source of Data

<!-- TOC tocDepth:2..3 chapterDepth:2..6 -->

- [1. Public APIs or Web Services](#1-public-apis-or-web-services)
- [2. Web Scraping](#2-web-scraping)
   - [2.1. Consolidated Bank List](#21-consolidated-bank-list)
   - [2.2. limited liability companies (llc)](#22-limited-liability-companies-llc)
- [3. FTP Servers or Feeds](#3-ftp-servers-or-feeds)
- [4. Data Aggregators](#4-data-aggregators)
   - [4.1. banks.az](#41-banksaz)
   - [4.2. infobank.az](#42-infobankaz)
- [5. Direct Partnerships](#5-direct-partnerships)

<!-- /TOC -->

## 1. Public APIs or Web Services
Many banks provide publicly accessible APIs or web services that share real-time data, such as exchange rates. These APIs allow external platforms to retrieve up-to-date currency information in a structured format (e.g., JSON or XML).
- Cant find any examples
- Finding an API is probably the best case scenario

## 2. Web Scraping
If APIs are not available, the site might use web scraping techniques to extract data directly from the exchange rate pages of bank websites. This involves automated scripts that fetch and parse HTML content to extract relevant data fields.

### 2.1. Consolidated Bank List 

From [azn.day.az](https://azn.day.az/en/) and [azn.az](https://azn.az/)

| Bank | Link | Scrape? | From Which Site |
| --- | --- | --- | --- |
| Access Bank | [link](https://www.accessbank.az/az/) | Easy to scrape, scroll down from home page | both |
| AFB Bank | [link](https://afb.az/) | Easy to scrape, scroll down from home page | both |
| Azerpost | [link](https://www.azerpost.az/) | Easy to scrape, scroll down from home page | azn.day.az |
| International Bank of Azerbaijan | [link]() | | both |
| Azerbaijan Industry Bank | [link]() | | azn.day.az (listed as ASB Azerbaijan Industry Bank) |
| Bank of the Republic |  [link]()| | azn.day.az (listed as Bank Respublika) |
| Premium Bank | [link]() | | both |
| VTB Bank (Azerbaijan) | [link]() | | azn.az |
| Kapital Bank | [link]() | | azn.az |
| Pasha Bank | [link]() | | azn.az |
| Rabita Bank | [link]() | | azn.az (listed as Rabitəbank on azn.day.az) |
| TuranBank | [link]() | | both |
| Unibank | [link]() | | both |
| Yapi Kredi Bank Azerbaijan | [link]() | | both |
| Bank Melli Iran | [link]()| | azn.day.az |
| Yelo Bank | [link]() | | azn.day.az |
| Azer Turk Bank | [link]() | | azn.day.az |
| Express Bank | [link]() | | azn.day.az |
| Bank BTB | [link]() | | azn.day.az |
| Ziraat Bank | [link]() | | azn.day.az |

### 2.2. limited liability companies (llc)

Last night I saw many mmc's (llc) listed on the site but now its only banks so Im not sure what changed. But the best rates were from zuhur mmc but now according to yandex which I think is like yelp here in the states now says its permamently closed. [zuhur mmc review](https://yandex.com/maps/org/136685285119/?ll=49.862877%2C40.386233&z=17)
 

## 3. FTP Servers or Feeds

Some banks may offer currency rate data via FTP servers or syndicated feeds (like RSS or XML). These are periodically updated by the banks.
- Im not sure how this would work, is it a lower tech api?
- This would work if we can find a bank that offers this service. 
   

## 4. Data Aggregators
Instead of direct integration with each bank, azn.day.az might use third-party aggregators that collect and consolidate exchange rate data from multiple banks, providing it through a single API or feed.

### 4.1. banks.az
[banks.az](https://banks.az/servisler/valyuta-mezenneleri)

Seems like a very good product might even make our project irrelvant, however the map is not quite right. but we can ellaborate more in market research. more/branches shows a map 
- only shows 
   - Access Bank   
   - Afb bank
   - atb Azer-Turk Bank
   - kapital bank (capital bank)
   - premium bank
   - Turanbank
   - Unibank
   - Yapi Kredi Bank
  
   

[affiliacete program](https://banks.az/affiliate-program)

      
### 4.2. infobank.az
- The website dose not load for me. not sure what it does. 
   - Cliking on the logo at the bottom of the banks who use infobank.az takes you to the infobank.az website.
- [linkedin](https://www.linkedin.com/company/infobank-az/)
- Used by 
    1. Access Bank
    2. Afb bank
    3. Azerpost

## 5. Direct Partnerships
In some cases, sites like azn.day.az might have direct partnerships with banks, giving them access to proprietary or internal systems that publish exchange rate data.
- I think this is probably the worst case senario if this is how sites like azn.day.az pulls their data at regular intervals. This is becuase it would require a relationship with the bank and they would have to be able to access the banks internal systems.