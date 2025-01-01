# Currency Convertion Project Report

**A Currency Convertion Visualization Tool for Baku, Azerbaijan**

## 1. Table of Contents
<!-- TOC tocDepth:2..5 chapterDepth:2..7 -->

- [1. Table of Contents](#1-table-of-contents)
- [2. Concept](#2-concept)
- [3. Aims and Objectives](#3-aims-and-objectives)
- [4. Stakeholders](#4-stakeholders)
- [5. Product Research](#5-product-research)
    - [5.1. Reason for the project](#51-reason-for-the-project)
    - [5.2. SWOT Analysis](#52-swot-analysis)
        - [5.2.1. Strengths](#521-strengths)
        - [5.2.2. Weaknesses](#522-weaknesses)
        - [5.2.3. Opportunities](#523-opportunities)
        - [5.2.4. Threats](#524-threats)
    - [5.3. PESTEL Analysis](#53-pestel-analysis)
        - [5.3.1. Political Factors](#531-political-factors)
        - [5.3.2. Economic Factors](#532-economic-factors)
            - [5.3.2.1. Introduction to Manat](#5321-introduction-to-manat)
            - [5.3.2.2. Economic Theory on Defending Currency Peg](#5322-economic-theory-on-defending-currency-peg)
            - [5.3.2.3. Azeri Light Crude Oil Price Impact on Manat](#5323-azeri-light-crude-oil-price-impact-on-manat)
            - [5.3.2.4. First Crisis: February 2015](#5324-first-crisis-february-2015)
            - [5.3.2.5. Second Crisis: December 2015](#5325-second-crisis-december-2015)
            - [5.3.2.6. Return to De Facto Pegging](#5326-return-to-de-facto-pegging)
            - [5.3.2.7. Implications](#5327-implications)
        - [5.3.3. Social Factors](#533-social-factors)
            - [5.3.3.1. Implications](#5331-implications)
- [6. References](#6-references)

<!-- /TOC -->

## 2. Concept

The proposed project is an application designed to help users quickly find the best currency exchange rates and the closest bank branches in Azerbaijan, with an initial focus on the city of Baku. The app targets both locals seeking favorable exchange rates and tourists unfamiliar with the local banking landscape. Unlike online banking platforms, this application does not facilitate financial transactions but serves as a convenient tool to compare rates and locate bank branches.

The app’s core functionality relies on data from Azerbaijani banks, which are required to report their exchange rates to the Central Bank. This information, available on platforms such as infobank.az, will be integrated into the app to provide accurate and real-time updates. Additionally, geolocation features will allow users to filter results by proximity, making it easier to find branches nearby offering competitive rates.

This tool aims to address a common challenge faced by users in navigating varying exchange rates and branch locations, particularly in a busy urban setting like Baku. By streamlining access to this information, the application enhances financial decision-making and convenience. The project has significant potential to benefit both locals and tourists while promoting transparency in currency exchange services.

## 3. Aims and Objectives

**Aim:**  
Our primary aim is to develop a web-based application tha allows both locals and tourists, to easily identify the best currency exchange rates and locate nearby bank branches in Azerbaijan. By providing real-time, accessible, and accurate information, the application seeks to enhance financial decision-making and convenience in the Baku market.

**Objectives:**  
1. Conduct research to validate the necessity and feasibility of the proposed application, using data from `infobank.az` and similar platforms with redundancy plans in case of data unavailability.   
2. Perform market analysis to identify potential competitors and evaluate their strengths and limitations.  
3. Develop an initial prototype that demonstrates key functionalities, such as rate comparison and branch geolocation, with a clear explanation of design decisions.  
4. Conduct usability testing with our local team member to ensure the application meets user needs effectively.  
5. Refine the design and features based on user feedback, ensuring the application meets user needs effectively.  
6. Document the development process with a critical evaluation, addressing challenges, inaccuracies, and areas for future improvement.  
7. Ensure the application adheres to accessibility standards and is scalable for potential expansion beyond Baku in the future.  

## 4. Stakeholders

We have identified two main stakeholder groups: **locals in Baku** and **tourists**. with one other tertiary stakeholder group: **small and medium-sized enterprises (SMEs)**.

At the core are **locals in Baku**, who frequently require currency exchange services for travel, foreign purchases, or occasional financial needs. While the impact of exchange rate fluctuations on this group is moderate—given their primary use of the Azerbaijani manat—the application simplifies the process of finding favorable exchange rates and nearby bank branches. This convenience makes the tool an essential resource for locals seeking quick and reliable exchange services without extensive effort or research. Aditional as we will see later, in cases of financial emergencies, locals will be the first to use the application in hopes to find the best exchange rates and nearby bank branches as quickly as possible. Locals typically speak Azerbaijani as their primary language, with many also fluent in Russian. These two languages are widely used in everyday life, making them essential for any application targeting this demographic. The application must prioritize Azerbaijani and Russian to ensure accessibility and usability for local users seeking efficient currency exchange solutions.

Another critical stakeholder group is **tourists**, who rely heavily on currency exchange services during their visits to Azerbaijan. Tourists are significantly impacted by exchange rate fluctuations, as these directly influence their spending power. They need tools that provide accurate comparisons and convenient access to nearby branches, making this application particularly valuable. They are also targetted by merchants offering inflated exchange rates to tourists. By addressing these needs, the application enhances the travel experience and supports the growing tourism sector in Azerbaijan. Tourists visiting Azerbaijan come from diverse linguistic backgrounds, but many rely on English for communication, especially those from Western countries, as well as Russian-speaking tourists from neighboring regions.

Additionally, **small and medium-sized enterprises (SMEs)**, particularly those involved in international trade, represent another potential stakeholder group. These businesses often face significant exposure to exchange rate fluctuations [1], which can affect their profit margins. While SMEs are not the primary target audience for the application, they may find value in its ability to provide accurate rate comparisons for foreign transactions. This utility can support SMEs in optimizing their exchange strategies and minimizing financial risks.

## 5. Product Research

### 5.1. Reason for the project

This project was conceived to address critical gaps in the current methods of finding currency exchange rates in Baku, Azerbaijan. Existing platforms like [azn.day.az](https://azn.day.az/) and [azn.az](https://azn.az/) are widely used and appreciated for their functionality. These websites allow users to compare exchange rates across multiple banks, update information frequently (e.g., every 10 minutes), and support multiple languages, including Azerbaijani, Russian, and English. These features make them accessible and helpful for both locals and tourists.

However, despite their strengths, these platforms lack certain key functionalities that could significantly enhance the user experience. For instance, they do not provide geolocation features to help users find nearby exchange offices or ATMs. This limitation forces users to rely on manual research, often checking multiple websites and physically visiting offices, which can be inefficient and time-consuming. Additionally, neither platform includes detailed information on transaction limits, office hours, or safety considerations—features that would be especially beneficial for tourists navigating an unfamiliar city.

Our project aims to bridge these gaps by developing a tool that combines the best features of existing platforms with new, user-focused functionalities. By using up-to-date data from [infobank.az](https://infobank.az/) and incorporating geolocation technology, the application will allow users to find the nearest exchange points quickly and efficiently. It will also provide essential details, such as transaction limits, office hours, and safety tips, ensuring that users have all the information they need to make informed decisions.

Tourists, in particular, will benefit from these enhancements. Many avoid using credit cards due to security concerns and rely heavily on cash. Having access to real-time information on nearby exchange offices and their services will alleviate many challenges they currently face. Locals will also benefit from the tool’s ability to streamline the process of finding the best exchange rates, saving time and effort.

In summary, this project addresses an unmet need in the market by combining real-time data aggregation, geolocation, and additional user-centric features. It will not only simplify financial decision-making but also provide a safer, more convenient experience for both locals and tourists in Baku.

### 5.2. SWOT Analysis

#### 5.2.1. Strengths

The platform's strengths lie in its user-centric functionality, which combines real-time exchange rate data with geolocation services to simplify financial decisions. This dual-focused approach is highly appealing to both locals and tourists, addressing their specific needs intuitively. As a web-based application, it ensures accessibility across multiple devices without requiring installation, further enhancing convenience for users. Integration with `infobank.az` provides reliable, real-time updates based on data mandated by the Central Bank, ensuring the platform’s trustworthiness. Additionally, the inclusion of Google Maps API for geolocation and navigation sets this project apart by enabling users to locate nearby exchange offices efficiently, which is a standout feature not commonly available in similar tools.

#### 5.2.2. Weaknesses

However, the project also has notable weaknesses. The team faces challenges related to limited experience in software development, particularly in areas such as managing geolocation APIs, web hosting, and database systems. These gaps in expertise could extend development timelines and necessitate additional resources. Furthermore, the platform relies heavily on `infobank.az` for data, which introduces a dependency risk. Service interruptions, restricted access, or delayed updates could hinder the platform’s functionality. While a contingency plan involving web scraping from bank websites is in place, this fallback is less reliable and requires continuous maintenance.


#### 5.2.3. Opportunities

The project offers significant opportunities to leverage. Azerbaijan’s growing tourism sector creates a rising demand for reliable currency exchange solutions. Tourists, as a key user base, would greatly benefit from enhanced transparency and geolocation features. Small and medium-sized enterprises (SMEs) engaged in cross-border trade represent another potential audience, as the platform can streamline and optimize their currency exchange processes. Beyond Baku, the platform is scalable to other cities in Azerbaijan and potentially internationally to regions with similar needs. Collaborations with local banks, exchange offices, and tourism agencies also provide opportunities to increase visibility and generate revenue through sponsorships or premium listings. 

#### 5.2.4. Threats

Despite its strengths and opportunities, the platform must address several threats. The competitive landscape includes large financial institutions or tech companies with substantial resources that could develop competing tools with broader features. Economic volatility, including fluctuations in exchange rates or unexpected political or economic crises, may impact the relevance and reliability of the platform’s data, especially for international users. Additionally, the collection and management of user location data present privacy risks. Any mishandling of this data could damage user trust and invite regulatory scrutiny, particularly under stringent global data protection standards. 

### 5.3. PESTEL Analysis

#### 5.3.1. Political Factors

Azerbaijan’s declining media freedom presents significant risks for platforms engaging in editorial or public-facing content. Freedom House, a U.S.-based organization monitoring global freedom, reports widespread arrests of journalists and activists in Azerbaijan, leading to self-censorship and restricted expression [2]. 

**Implication:**  
To mitigate our exposure to risks, our platform should avoid social or editorial features and focus on neutral data visualization, ensuring compliance with local regulations while maintaining user trust and operational safety.

#### 5.3.2. Economic Factors

![Manat azn to usd](./img/AZN%20to%20usd%20max.png)
> Google search for "Manat azn to usd max"

##### 5.3.2.1. Introduction to Manat

The Azerbaijani Manat emerged following the country's independence from the Soviet Union, replacing the Soviet ruble as the national currency. [3] In its early years, the Manat maintained remarkable stability, pegged at approximately 0.78 to the US dollar for several years. [4] During this period, President Aliyev proudly declared it "one of the most stable currencies in the world." [5]

##### 5.3.2.2. Economic Theory on Defending Currency Peg

The Manat's peg to the US dollar proved unsustainable due to Azerbaijan's heavy reliance on the oil market. When oil prices collapse, the Manat's fixed exchange rate prevents the Central Bank of Azerbaijan from effectively intervening in the foreign exchange market to stabilize the currency. This dependency on oil means that fluctuations in oil prices directly impact the Manat's value. To maintain the peg, the Central Bank is forced to purchase foreign currency, which rapidly depleted its foreign reserves. If the crisis contiues long enough, the Central Bank will not have enough foreign currency to maintain the peg, and the currency will devalue, which will result in inflation, a crisis in confidance will result, causing holders of azn to panic and sell their azn, causing the currency to drop even more called a flight to quality. [6]

##### 5.3.2.3. Azeri Light Crude Oil Price Impact on Manat

![Oil price for Azeri Light brand from Jan, 2015 to Jan, 2016 (Source: author's chart, Excel). In general, a rash decrease in oil prices negatively affected the economy of Azerbaijan in 2015-2016. The situation was conditioned by the uncertainty in the economic and political environment. This had a critical impact on the activities of the oil companies both in the world and in Azerbaijan Republic during this period in the form of cost savings and cost reduction. When the reserves of the State Oil Fund of the Republic of Azerbaijan (SOFAZ) reached a critical point, the government resorted to a devaluation.](./img/Oil-price-for-Azeri-Light-brand-from-Jan-2015-to-Jan-2016-Source-authors-chart.png)
> Analysis of the Price Change of the Azerbaijani Oil of Azeri Light, using the Monte-Carlo Method in the Conditions of Uncertainty - Scientific Figure on ResearchGate

##### 5.3.2.4. First Crisis: February 2015

The first occurred in February when the currency lost more than a third of its value against the dollar, causing what banking expert Akram Hasanov described as "serious damage to people and entrepreneurs." [5]

In feburary 2015, the Central Bank of Azerbaijan abandoned the currency peg to the US dollar.  [4]

##### 5.3.2.5. Second Crisis: December 2015

The second crisis hit in December when the central bank ceased protecting the Manat's value, resulting in a dramatic 32% drop in a single day. This led to widespread panic, with people rushing to exchange their Manats for dollars, shops closing their doors, and banks imposing strict exchange limits while exchange offices ran out of dollars entirely.

###### 5.3.2.5.1. Floating Exchange Rate

In the context of currency exchange, a "corridor" refers to a predetermined range within which a central bank aims to keep the exchange rate of a currency, essentially setting a ceiling and floor for how much the currency can fluctuate against other currencies; so, "dropping the exchange rate corridor" means the central bank is no longer actively intervening to keep the currency value within that specific range, allowing it to freely fluctuate based on market forces, which is called a "floating" exchange rate. [6]

##### 5.3.2.6. Return to De Facto Pegging

By 2017, the government implemented significant reforms, dropping the exchange rate corridor and allowing the Manat to float freely. This included removing the 4% trading range restriction and setting a new official rate at 1.7867, the weakest in its history. The reforms also saw an increase in currency conversion limits from $200 to $5,000 per person. 

The overall decline was stark: from 2014 to 2017, the Manat lost approximately 53% of its value, primarily due to the collapse in oil prices, Azerbaijan's main export. This pattern was not unique to Azerbaijan, as similar trends were observed in other oil-dependent economies like Russia and Kazakhstan.


##### 5.3.2.7. Implications

With the Azerbaijani Manat currently operating under a soft peg to the US dollar at a fixed rate of 1.7, there remains an uncertainty surrounding its stability. This system, while currenctly providing stability, in 2023 S&P Anlaysis assumed that the peg will remain until 2026. [9]

> "Nevertheless, in our view, should hydrocarbon prices drop sharply and remain low for a prolonged period, the authorities could consider adjusting the exchange rate. This would help avoid a substantial loss of foreign-currency buffers, similar to the central bank's actions in 2015"
>
> S&P Analysis qouted in “Azerbaijani Manat’s Peg to the US Dollar to Stay Firm until 2026.” by Trend.Az 

In October 2024, the Azerbaijani Ministry of Finance's forecast predicts that the manat's exchange rate will stay at its current level through 2028. [10] Despite this, there is still an uncertainty surrounding the long-term sustainability of the peg.

In a plausible future scenario where oil prices significantly decline, there would likely be another loss of confidence in the Manat. This could lead to another rush by individuals and businesses to exchange their Manats for US dollars, up to the maximum amount allowed by the Central Bank of Azerbaijan (CBA). Such behavior would reflect a flight to safety as people seek to safeguard their wealth against potential currency devaluation. 

This senarios provides a tangible use case for or project to aid in an efficeint and fast way to locate a bank or exchange office to convert azn to usd.

#### 5.3.3. Social Factors

Azerbaijan's demographic landscape and technological adoption present both opportunities and challenges for the implementation of a currency exchange platform. The country boasts a high literacy rate, with approximately 99.78% of individuals aged 15 and above being able to read and write [11]. Internet penetration is also significant, standing at 88% as of 2022 [12].
Additionally, smartphone penetration exceeds 70%, surpassing many European nations [13].
Despite these encouraging statistics, financial literacy remains a concern. Studies indicate that the overall level of financial literacy among students is around 48%, with male students exhibiting higher financial literacy than their female counterparts [14]. This gap suggests a need for educational initiatives to enhance financial understanding across all demographics. Moreover, while urban areas enjoy widespread internet access, rural regions may experience disparities in connectivity and digital literacy. This urban-rural divide could affect the equitable adoption of digital financial services.

##### 5.3.3.1. Implications

The high literacy rate and substantial internet and smartphone penetration in Azerbaijan provide a solid foundation for the adoption of digital platforms like the proposed currency exchange application.
However, the relatively low financial literacy levels necessitate the inclusion of user-friendly features and educational components within the app to assist users in making informed decisions.
Additionally, efforts should be made to ensure that the platform is accessible and functional for users in both urban and rural settings, taking into account potential differences in internet connectivity and digital proficiency.

#### 5.3.4. Technological Factors

Azerbaijan's commitment to digital transformation is evident in initiatives like the Digital Trade Hub, which promotes electronic payments and digital commerce [15]. This shift towards a cashless society aligns with the app's goals of simplifying and streamlining financial processes.
The Azerbaijan's mobile internet infrastructure has grown rapidly, with 4G coverage now available to 94% of the population, and 5G rollout plans in progress [16]. The increasing adoption of 5G technology is expected to enhance mobile internet speeds and reduce latency, offering better user experiences for mobile applications.
The Azerbaijani government has invested significantly in IT education, launching coding programs and tech hubs to nurture local talent [17]. This is fostering an ecosystem that could support the development and maintenance of tech solutions like the currency exchange app.
Additionally, cybersecurity threats, such as phishing attacks and data breaches, are increasing globally and could pose risks to user trust and data protection [18]. Geolocation data is particularly sensitive. Mismanagement of such information can expose users to privacy risks, such as location tracking or profiling by malicious actors. Implementing anonymized geolocation queries (e.g., by rounding location coordinates to a certain range) can reduce the precision of stored data while preserving the app's functionality [19]. 

##### 5.3.4.1. Implications

The widespread mobile internet and smartphone penetration in Azerbaijan provide a strong foundation for the adoption of the currency exchange application. The ongoing digital transformation and government support for tech initiatives create an enabling environment for the app's development and integration. However, rural connectivity challenges and cybersecurity risks must be addressed to ensure equitable access and user trust. Implementing strong geolocation data protection measures could mitigate these concerns.
References



## 6. References

1. The Trade Finance Guide, U.S. Department of Commerce, www.trade.gov/sites/default/files/2022-07/Trade_Finance_Guide_2022.pdf. Accessed 5 Dec. 2024. 
2. “Azerbaijan: Freedom on the Net 2024 Country Report.” Freedom House, freedomhouse.org/country/azerbaijan/freedom-net/2024. Accessed 23 Dec. 2024.
3. Azerbaijani Manat. (2024, November 12). In Wikipedia. https://en.wikipedia.org/wiki/Azerbaijani_Manat
4. Bagirova, Nailia. “Azeri Central Bank Abandons Currency Peg to U.S. Dollar | Reuters.” Azeri Central Bank Abandons Currency Peg to U.S. Dollar, Reuters, 16 Feb. 2015, www.reuters.com/article/markets/azeri-central-bank-abandons-currency-peg-to-us-dollar-idUSL5N0VQ2KA/. 
5. Viner, Katharine. “Azerbaijan in Crisis as Currency Plummets.” The Guardian, Guardian News and Media, 22 Dec. 2015, www.theguardian.com/world/2015/dec/22/azerbaijan-currency-plummets-oil-price#:~:text=Azerbaijan’s%20currency%20has%20plummeted%20after,face%20of%20falling%20oil%20prices. 
6. Ganti, Akhilesh. “Currency Pegging: Overview and Pros and Cons.” Investopedia, Investopedia, www.investopedia.com/terms/p/pegging.asp. Accessed 4 Dec. 2024. 
7. “Forex Trading Glossary: Forex Terms: Fibo Group: Corridor.” What Is “Corridor” | Definition and Meaning of the Term | Forex Trading Glossary, www.fibogroup.com/products/clients/glossary/corridor/#:~:text=Definition%20and%20Properties:%20A%20corridor%20is%20defined,stability%20while%20limiting%20movements%20on%20the%20market. Accessed 4 Dec. 2024. 2
8. Analysis of the Price Change of the Azerbaijani Oil of Azeri Light, using the Monte-Carlo Method in the Conditions of Uncertainty - Scientific Figure on ResearchGate. Available from: https://www.researchgate.net/figure/Oil-price-for-Azeri-Light-brand-from-Jan-2015-to-Jan-2016-Source-authors-chart_fig1_355364238 [accessed 5 Dec 2024]
9. Gasimov, Kamran. “Azerbaijani Manat’s Peg to the US Dollar to Stay Firm until 2026.” Trend.Az, 10 June 2023, en.trend.az/business/3760007.html. 
10. Gasimov, Kamran. “Azerbaijani Manat to Maintain Constant Value versus US Dollar till 2028.” Trend.Az, 18 Oct. 2024, en.trend.az/business/finance/3958753.html. 
11. "Literacy rate in Azerbaijan 2023." Statista, www.statista.com/statistics/572577/literacy-rate-in-azerbaijan/. Accessed 28 Dec. 2024.
12. "Individuals using the Internet (% of population) - Azerbaijan." World Bank, data.worldbank.org/indicator/IT.NET.USER.ZS?locations=AZ. Accessed 28 Dec. 2024.
13. "Azerbaijan overtakes many European countries in smartphone penetration." Report News Agency, report.az/en/finance/mastercard-azerbaijan-overtakes-many-european-countries-in-smartphone-penetration/. Accessed 28 Dec. 2024.
14. "Demographic Analysis of Financial Literacy Level in Azerbaijan." Universal Journal of Accounting and Finance, www.hrpub.org/download/20210530/UJAF5-12217266.pdf. Accessed 28 Dec. 2024.
15. "Digital Trade Hub of Azerbaijan." E-Government Azerbaijan, www.e-gov.az/en. Accessed 28 Dec. 2024.
16. "Azercell 5G" Azercell, https://www.azercell.com/en/personal/plans-and-services/5g.html. Accessed 28 Dec. 2024.
17. "Cybercrime To Cost The World $10.5 Trillion Annually By 2025." Cybersecurity Ventures, cybersecurityventures.com/hackerpocalypse-cybercrime-report-2016/. Accessed 28 Dec. 2024.
18. "Protecting Privacy in Location-Based Services." IEEE, https://ieeexplore.ieee.org/document/9133462. Accessed 28 Dec. 2024.