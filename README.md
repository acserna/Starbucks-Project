# Starbucks-Project

"Starbucks Corporation is an American coffee company and coffeehouse chain. Starbucks was founded in Seattle, Washington in 1971. As of early 2019, the company operates over 30,000 locations worldwide.

Starbucks is considered the main representative of "second wave coffee", initially distinguishing itself from other coffee-serving venues in the US by taste, quality, and customer experience while popularizing darkly roasted coffee.Since the 2000s, third wave coffee makers have targeted quality-minded coffee drinkers with hand-made coffee based on lighter roasts, while Starbucks nowadays uses automated espresso machines for efficiency and safety reasons." [https://en.wikipedia.org/wiki/Starbucks]

One important goal is to attract clients using several types of offers and the idea is that hey gonna buy the Starbucks products, in this way the business will get more revenue. A relevant fact is to analyze the behavior of the offers with the clients and understand the way that they buy the Starbucks products along the time.

Based on the above I wanna:
1. Build a machine learning model that predicts how much someone will spend based on demographics and offer type
2. Understand the importance of each variable in the model.

### Instructions:
1. Install python the version 3 [https://www.python.org/]
2. Run the following command to install all the dependencies of the project.
    - `pip install -r requirements.txt`
3. Run the following commands to use jupyter notebook in the project folder.
	- `jupyter notebook`


### File Description
portfolio.json
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

profile.json
* age (int) - age of the customer
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

transcript.json
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

### Results
All the results are presented in the following post on "Medium": https://medium.com/@andres.c.serna/data-science-process-in-simulated-starbucks-data-to-predict-the-spend-of-money-of-the-clients-74e2e608c8ce