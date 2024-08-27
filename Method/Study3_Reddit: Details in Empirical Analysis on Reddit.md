## Details in Empirical Analysis on Reddit

In this section, we conducted three rounds of post-classification. First, we performed an initial classification of 9,326 posts to gain an overview of online discussions related to stablecoins. Next, based on the results of the first classification, we further categorized 1,192 posts under the “Stablecoin Discussions” category to explore these discussions in greater depth. Finally, again based on the first classification results, we conducted a more detailed classification of 4,211 posts under the “Stablecoin Security Risk Discussions” category to better understand the nuances of online discussions regarding stablecoin risks.

Each round of classification followed a specific procedure:
- Initially, we randomly selected 100 posts from each category. Two researchers independently analyzed 20% of the selected posts, developed an initial coding framework, and refined it through iterative comparison until a consistent codebook was established. This finalized codebook was then applied to the remaining posts by the two researchers, followed by a final consistency check after all posts were coded.
- Subsequently, the codebook was organized into classification criteria through thematic analysis, which served as prompts for ChatGPT-4 to analyze the posts.
- In this process, ChatGPT-4 first categorized the same 100 posts that had been manually classified by the researchers. The results were compared, and if the accuracy rate reached 85%, the same standard was used to allow ChatGPT-4 to continue classifying the remaining posts.
- For posts that could not be automatically classified, the researchers conducted manual reviews. 

### 1. Initial Classification of 9,326 Posts

In our study, we randomly selected 100 posts from a total of 9,326 using a randomization function for thematic analysis. Two authors independently analyzed 20% of the selected posts, developing initial codes and refining them through iterative comparison until a consistent codebook was established. Following this, the two authors applied the finalized codebook to the remaining posts and performed a final consistency check after coding all the posts. This iterative process ensured the development of a robust and reliable coding framework. Our analysis identified three primary categories: 
1. **Introduction and Security Issues of Stablecoins** 
2. **Cryptocurrency Operational Assistance Requests** 
3. **Cryptocurrency Investment Advertisements**

To categorize all the posts, we utilized ChatGPT-4.0. We provided the manually developed coding criteria as a prompt and tested its accuracy by having it classify the 100 posts that had already been manually coded. GPT-4 classified these posts with an accuracy rate of 89%. Subsequently, we applied this standard to the remaining posts using GPT-4. The results indicated that:
- **Category 1** contained 5,403 posts, with 1,192 posts broadly discussing stablecoins and 4,211 posts discussing risks.
- **Category 2** included 1,214 posts.
- **Category 3** included 2,243 posts (with 12 posts requiring manual classification due to GPT-4’s inability to classify them).
- **466 posts** were found to be unrelated to stablecoins (verified manually).

####  Examples of Classification Instructions Prompts:
Please categorize the text you enter afterward (the description of the post in the forum). The available types are listed below:

- **A. Introduction and Security Issues of Stablecoins**: This category includes posts discussing the fundamentals of stablecoins, such as their definitions, mechanisms, and value stability, as well as security concerns like vulnerabilities, hacking risks, and regulatory challenges.
- **B. Cryptocurrency Operational Assistance Requests**: This category includes posts where users seek help or guidance on various operational aspects of using cryptocurrencies.
- **C. Cryptocurrency Investment Advertisements**: This category includes posts that are promotional in nature, typically aimed at encouraging users to invest in various cryptocurrency projects or platforms.

For each input, you can select more than one of these categories. You only need to answer the serial number of the category, no explanations. If the category is not included above or it is not related to stablecoins, please answer “other categories”.

**Note**: Posts can only be categorized if their content clearly matches the category description, is implied or potentially cannot be categorized.

The following table presents the classification results.


| Category                              | Explanation                                                                                                                                          | Example                                                                                       | Number of posts |
|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|----------------|
| Introduction and Security Issues of Stablecoins | This category includes posts discussing the fundamentals of stablecoins, such as their definitions, mechanisms, and value stability, as well as security concerns like vulnerabilities, hacking risks, and regulatory challenges. | A European bank acknowledges using the stablecoin USDC instead of SWIFT for faster cross-border transfers. <br><br>Why are you guys using stablecoins? | 5403           |
| Cryptocurrency Operational Assistance Requests | This category includes posts where users seek help or guidance on various operational aspects of using cryptocurrencies.                             | How do I transfer USDT from my wallet to an exchange?                                          | 1214           |
| Cryptocurrency Investment Advertisements      | This category includes posts that are promotional in nature, typically aimed at encouraging users to invest in various cryptocurrency projects or platforms. | a DApp which allows you to swap stablecoins without slippage                                   | 2243           |
| Non-Stablecoin Related Content                | This category includes posts that were identified as outside the primary focus of stablecoin-related discussions and were therefore classified separately. | If you had the capital to buy 0.5 BTC, what would you do with it?                               | 466            |



### 2 Classification of Stablecoin Discussions (Excluding Risk-Related Topics)

We randomly selected 100 posts from a total of 1,192 posts on the topic of "Classification of Stablecoin Discussions Excluding Risk-Related Topics" using a randomization function for thematic analysis. Two authors independently analyzed 20% of the selected posts, developing initial codes and refining them through iterative comparison until a consistent codebook was established. Following this, the two authors applied the finalized codebook to the remaining posts and conducted a final consistency check after coding all the posts. This iterative process ensured the development of a robust and reliable coding framework.

To categorize all the posts, we utilized ChatGPT-4. We began by providing the AI with the manually developed coding criteria as a prompt and tested its accuracy by having it classify the same 100 posts that had already been manually coded. GPT-4 classified these posts with an accuracy rate of 87%. Following this, we applied this standard to the classification of the remaining posts using GPT-4. The following table presents the classification results.

####  Examples of Classification Instructions Prompts:
Please categorize the text you enter afterward (the description of the post in the forum). The available types are listed below:

- **A. Introduction of Stablecoin**: Introduce the basic concepts of stablecoins, explaining how they maintain their value stability, the entities that issue them, and how they operate in the market.
- **B. Concerns and Discussions About Using Stablecoins**: Discuss the concerns and questions about using stablecoins, including why people choose to use them and a comparison of different stablecoins, highlighting their advantages and disadvantages.
- **C. Using Stablecoins as a Means of Payment**: Explores the use of stablecoins for making payments, including their acceptance by merchants, transaction speed, and cost efficiency compared to traditional payment methods.
- **D. Using Stablecoins as a Medium of Exchange in the Crypto Market**: Examines how stablecoins are used as a trading pair in the cryptocurrency market, facilitating the exchange of other digital assets and providing liquidity.
- **E. Using Stablecoins as an Investment Asset**: Discusses the potential of stablecoins as an investment asset, including their use in yield farming, interest-earning accounts, and other investment strategies.
- **F. Tax Implications and Considerations for Stablecoins**: Addresses the tax considerations associated with stablecoins, including how they are treated under different tax jurisdictions, reporting requirements, and potential tax liabilities.

For each input, you can select more than one of these categories. You only need to answer the serial number of the category, no explanations. If the category is not included above or it is not related to stablecoins, please answer "other categories."

**Note**: Posts can only be categorized if their content clearly matches the category description, implied or potentially cannot be categorized.


The following table presents the classification results.


| Topic                                              | Explanation                                                                                                                                      | Example                                                                                                                                                                      | Post Quantity |
|----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|
| Introduction of Stablecoin                         | Introduce the basic concepts of stablecoins, explaining how they maintain their value stability, the entities that issue them, and how they operate in the market.            | How is volatility being fixed?—stablecoin                                                                                                                                     | 104           |
| Concerns and Discussions About Using Stablecoins   | Discuss the concerns and questions about using stablecoins, including why people choose to use them and a comparison of different stablecoins.                                    | Why are you guys using stablecoins?                                                                                                                                           | 171           |
| Using Stablecoins as a Means of Payment            | Discuss the use of stablecoins for making payments, including their acceptance by merchants, transaction speed, and cost efficiency compared to traditional payment methods.    | Visa announces plans to expand stablecoin settlement capabilities by leveraging USDC and utilizing the Solana blockchain                                                     | 331           |
| Using Stablecoins as a Medium of Exchange in the Crypto Market | Discuss how stablecoins are used as a trading pair in the cryptocurrency market, facilitating the exchange of other digital assets and providing liquidity.                      | Binance will remove and cease trading on the following spot trading pairs at USDC/BUSD, USDC/USDT.                                                                            | 317           |
| Using Stablecoins as an Investment Asset           | Discuss the potential of stablecoins as an investment asset, including their use in yield farming, interest-earning accounts, and other investment strategies.                  | Coinbase buffed USDC APY from 0.15% to 1.5%                                                                                                                                   | 231           |
| Tax Implications and Considerations for Stablecoins | Discuss the tax considerations associated with stablecoins, including how they are treated under different tax jurisdictions, reporting requirements, and potential tax liabilities. | Hello, I'm currently in talks to join a remote company that would pay me a salary in USDC. Although I find it exciting to be paid in crypto, I have a few concerns. Is it rather safe? | 38            |


### 3 Classification of Stablecoin Security Risk Discussions

In our study, we also randomly selected 100 posts from a total of 4,211 using a randomization function for thematic analysis. Two authors independently analyzed 20% of the selected posts, developing initial codes and refining them through iterative comparison until a consistent codebook was established. The finalized codebook was then applied by the two authors to the remaining posts, followed by a final consistency check after coding all posts. This iterative process ensured the creation of a robust and reliable coding framework.

To categorize the entire set of posts, we employed ChatGPT-4. We began by providing the AI with the manually developed coding criteria as a prompt and tested its accuracy by having it classify the same 100 posts that had already been manually coded. ChatGPT-4 achieved an accuracy rate of 91% in this task. Following this validation, we used the same criteria to categorize the remaining posts with ChatGPT-4. The following table presents the classification results.

| Topic                     | Explanation                                                                                                                                                   | Example                                                                                                                            | Post Quantity |
|---------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|---------------|
| Operator Risk             | Discussions on the risks associated with the issuers or operators of stablecoins, including potential mismanagement and lack of transparency                   | The issuers or operators of the stablecoin are in a situation in which financial instability or fraud results in the loss of a user’s funds | 1449          |
| Collateral Risk           | Discussions on the risks related to the backing reserves of stablecoins, such as the liquidity of collateral assets, over-collateralization, and the potential for collateral value fluctuations | If there indeed aren’t sufficient reserves, users may face financial losses                                                        | 638           |
| Operational Risk          | Discussions on the risks inherent in the operational mechanisms of stablecoins, including technological vulnerabilities and smart contract bugs                | The liquidation may take a while to complete due to market volatility and the time required for auctions                           | 387           |
| Third-party Institutions Risk | Discussions on the risks associated with third-party institutions involved in stablecoin transactions, such as exchanges, custodians, and other intermediaries | The value of USDT deviated from its dollar peg following revelations of its three billion exposure to Silicon Valley Bank           | 293           |
| Regulation Risk           | Discussions on legal and regulatory issues impacting stablecoins, including compliance requirements, regulatory scrutiny, and the potential for legal restrictions by governmental authorities | Due to the SEC’s use of securities laws to sanction BUSD, I am worried that the SEC may employ the same rationale to target other stablecoins | 1444          |

