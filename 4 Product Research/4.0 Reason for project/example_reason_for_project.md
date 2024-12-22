# Example of Reason for the project

The reasoning behind choosing financial news topics and sentiment analysis as a basis is
simple. Based on the main idea of the field called behavioural finance [1], we say that most
market trends are partially driven by psychological aspects of investors, and most of these
investors rely on news [2] that are fundamental to the analysis of market trends as was pointed
out by a special advisor at Norges Bank Leif Anders Thorsrud. “The more a newspaper writes
about a topic, the more likely it is that this topic reflects something of importance for the
economy’s current and future needs and developments.” - it was the main hypothesis for him to
explore in his presentation “The value of news”. Thorsrud then looked at various Norwegian
financial newspapers, breaking down its content into broad categories such as startups or
monetary policy. He then explained: “When the news content is properly classified, explaining
and tracking business cycle fluctuations can be done at no cost”. Thorsrud further added: “Our
results suggest that news can be used to ... forecast GDP growth quite well.”
Besides topic modelling, however, it is as important to perform financial sentiment analysis on
news articles. As noted in this blogpost [3] Financial Market Analysts make predictions on the
stock market based on opinions and happenings in the news. And, as can be inferred,
sentiment analysis is synonymous to “opinion mining” and is perfectly suitable for such a task.
However, as noted here [4], for investors and professional traders it is also essential to read
between the lines and anticipate the news. It is mostly done by reading economic reports,
technical indicators and company news to figure out how the industry is shaping and what price
trends are more likely to follow. Although figuring out the current stage in the business cycle is

usually done in practice by looking at various economic indexes, we will only focus on reading
financial news, since that information, as noted above, can be inferred from just that.
In financial analysis there is also a great concern regarding the non-deterministic nature of
event-stock dependencies. For example, as noted here [5], the positiveness of news sometimes
strongly relates to the current stage of the economic cycle, which makes the model’s predictions
less “confident”. It is also difficult to determine which events correlate with which price trends,
since in some cases there is a lag between an event and a price trend as can be seen in this
blog post [6], which discusses effects of rise in the interest rates on the stock market. The stock
prices become affected only after a lag period, which is almost a year long. That is why we will
focus on short-term dependencies, which will make it a little bit easier to implement our
program