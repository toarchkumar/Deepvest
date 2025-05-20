# Deepvest: Investing in People's Potential

## The Concept

Instead of investing in companies, what if you could invest directly in talented individuals, betting on their future success and earnings? Deepvest introduces a novel way to do just that.

## How It Works

### For the Earner (Talented Individual)

1.  **Commitment:** Individuals (earners) pledge a percentage of their current salary as collateral. This collateral is pooled together with other earners to create a fund.
2.  **Tokenization:** Based on the amount each earner contributes to the pool, tokens are issued. These tokens represent a share of the pooled collateral and potential future earnings. Earners receive an upfront payment when these tokens are sold to investors.
3.  **Earnings and Dividend Contribution:** The following year (and for an agreed period), earners contribute a portion of their actual salary to a dividend pool. As modeled in our Proof of Concept, this contribution is calculated as **50% of their original collateral commitment percentage, applied to their *new* salary** (i.e., `0.50 * Original Collateral % * New Salary`). This pool is then distributed to token holders.
4.  **Collateral Security:** The collateral acts as security for investors. If an earner becomes unemployed and is unable to make their dividend contribution, their pledged collateral can be used to compensate investors.

### For the Buyer (Investor)

1.  **Purchase:** Investors buy tokens from the pooled fund. The price of each token is based on the total value of the pooled collateral, plus a premium markup and a component for platform fees.
2.  **Returns from Dividends:** Investors receive dividends from the pool funded by earners' contributions. As modeled, this is based on each earner contributing `0.50 * Original Collateral % * New Salary`.
3.  **Returns from Token Value Appreciation:** The token's value may appreciate based on the collective performance of the earners and the dividend generation.
4.  **Security:** The collateral provides a safety net. If an earner defaults on their dividend contributions due to job loss, their collateral can be drawn upon.

## An Example:

Let's say 10 earners come together and contribute a total of approximately **$390K** as collateral based on percentages of their current salaries. This collateral is then tokenized into **1 million tokens**.

If an earner with a current salary of $250K contributes 10% (or $25K) to the pool, they would receive tokens proportional to their contribution. If all tokens are sold to investors at a markup (e.g., covering premium and platform fees), the net proceeds are distributed back to the earners based on their token holdings, providing them with upfront capital.

The following year, earners make their dividend contributions based on their new salaries and original commitment levels. For instance, the earner who committed 10% initially would contribute `5%` (which is `50% of 10%`) of their new salary to the dividend pool. These pooled dividends are then distributed to all token holders.

## Benefits:

* **For Earners:** They receive an upfront investment which they can use as they see fit. It's a way to monetize future potential today.
* **For Investors:** They have the opportunity for returns based on the future success of talented individuals. The collateral provides a level of security for their investment.

## More Details

### Earner's Incentive and Profit (Initial Phase)

Suppose an earner has a base salary of **$250K** annually. They commit **10%** of their current earnings as collateral in exchange for an upfront investment in their potential. This **$25K** is pooled with contributions from other earners. With 10 such earners, the total pool amounts to **$389,347** (rounded to $390K for simplicity in narrative). This pool is tokenized into **1,000,000** tokens, with each earner receiving tokens proportional to their contribution.

| Potential Earner | Present Salary | Percentage Committed in Collateral | Collateral Amount in $ | Relative % of Crowd Fund | Shares Tokenized |
| :--------------- | :------------- | :--------------------------------- | :--------------------- | :----------------------- | :--------------- |
| Earner 1         | $250,000       | 10%                                | $25,000                | 6.42%                    | 64,210           |
| Earner 2         | $350,000       | 13%                                | $45,500                | 11.69%                   | 116,862          |
| Earner 3         | $200,000       | 9%                                 | $18,000                | 4.62%                    | 46,231           |
| Earner 4         | $190,000       | 8%                                 | $15,200                | 3.90%                    | 39,040           |
| Earner 5         | $400,000       | 30%                                | $120,000               | 30.82%                   | 308,208          |
| Earner 6         | $195,000       | 18%                                | $35,100                | 9.02%                    | 90,151           |
| Earner 7         | $296,000       | 20%                                | $59,200                | 15.20%                   | 152,049          |
| Earner 8         | $310,000       | 17%                                | $52,700                | 13.54%                   | 135,355          |
| Earner 9         | $232,900       | 5%                                 | $11,645                | 2.99%                    | 29,909           |
| Earner 10        | $233,400       | 3%                                 | $7,002                 | 1.80%                    | 17,984           |
| **Crowd Total** | **$2,657,300** | **Avg. ~14.65%** | **$389,347** | **100.00%** | **1,000,000** |

The base price for each token is calculated as Total Collateral / Total Tokens (e.g., `$389,347 / 1,000,000 \approx \$0.389`).
The final token price for investors is determined by applying a premium and accounting for platform fees. Following the Proof of Concept model (`Base Price * (1 + Premium % + Fee %)`), with a 30% premium and a 5% fee component in this calculation, the price becomes approximately **$0.5265**.

Selling all 1M tokens at ~$0.5265 would generate **~$526,500**.
A platform service fee (e.g., 5% of the total sale amount) is deducted: `~$526,500 * 0.05 = ~$26,325`.
The remaining **~$500,175** is distributed among the earners based on their respective token contributions, providing them with upfront capital.

The pooled collateral (**$389,347**) is reserved. It serves as a fallback if an earner becomes unemployed and cannot meet their dividend obligations. If an earner's salary doesn't increase (or even decreases) but they remain employed, they are still expected to contribute to the dividend pool from their current salary based on the agreed formula.

### Buyer's Incentive and Profit (Future Phase)

The next step is to assess the earners' potential salary for the following year and the resulting dividends for investors. The dividend contributed by each earner is calculated as: **(Earner's Future Salary) \* (Earner's Original Collateral Commitment Percentage) \* 50%**.

| Potential Earner | Salary Raise | Future Salary | Effective Dividend Rate (50% of Orig. Commit %) | Dividend Contribution from Earner ($) |
| :--------------- | :----------- | :------------ | :---------------------------------------------- | :------------------------------------ |
| Earner 1         | 3%           | $257,500      | 5.0% (50% of 10%)                               | $12,875.00                            |
| Earner 2         | 5%           | $367,500      | 6.5% (50% of 13%)                               | $23,887.50                            |
| Earner 3         | 6%           | $212,000      | 4.5% (50% of 9%)                                | $9,540.00                             |
| Earner 4         | 1%           | $191,900      | 4.0% (50% of 8%)                                | $7,676.00                             |
| Earner 5         | 0%           | $400,000      | 15.0% (50% of 30%)                              | $60,000.00                            |
| Earner 6         | 0%           | $195,000      | 9.0% (50% of 18%)                               | $17,550.00                            |
| Earner 7         | 1%           | $298,960      | 10.0% (50% of 20%)                              | $29,896.00                            |
| Earner 8         | 10%          | $341,000      | 8.5% (50% of 17%)                               | $28,985.00                            |
| Earner 9         | 20%          | $279,480      | 2.5% (50% of 5%)                                | $6,987.00                             |
| Earner 10        | 0%           | $233,400      | 1.5% (50% of 3%)                                | $3,501.00                             |
| **Crowd Total** |              |               |                                                 | **$200,897.50** |

The **Total Dividend Pool** collected from all earners is **$200,897.50**.

According to the Proof of Concept's valuation model, the new total capital backing the tokens (`Future Cap Amount`) is the sum of the initial net capital distributed to earners and this new total dividend pool:
`Future Cap Amount = Net Upfront Capital to Earners + Total Dividend Pool`
`Future Cap Amount = ~$500,175 + $200,897.50 = ~$701,072.50`

The new value per token is then:
`New Token Value = Future Cap Amount / Total Tokens`
`New Token Value = ~$701,072.50 / 1,000,000 = ~$0.7011`

This translates to a potential profit for investors:
* Initial Token Cost for Investor: ~$0.5265
* New Token Value: ~$0.7011
* Profit per Token: `~$0.7011 - ~$0.5265 = ~$0.1746`
* **Return on Investment (ROI): (`~$0.1746 / ~$0.5265`) * 100% $\approx$ 33.16%**

For illustrative purposes, here's how the profit might be distributed among five example investors based on this ~33.16% ROI:

| Owner of Shares | Shares Owned | Approx. Cost (at ~$0.5265/share) | Approx. Future Value (at ~$0.7011/share) | Approx. Profit to Buyer |
| :-------------- | :----------- | :------------------------------- | :--------------------------------------- | :---------------------- |
| Buyer 1         | 300,000      | $157,950                         | $210,330                                 | $52,380                 |
| Buyer 2         | 200,000      | $105,300                         | $140,220                                 | $34,920                 |
| Buyer 3         | 100,000      | $52,650                          | $70,110                                  | $17,460                 |
| Buyer 4         | 350,000      | $184,275                         | $245,385                                 | $61,110                 |
| Buyer 5         | 50,000       | $26,325                          | $35,055                                  | $8,730                  |
*(Note: Values are rounded, precise figures depend on exact inputs from `earner_present.csv` into the Python model).*

The initial collateral pool remains a security measure. If an earner defaults (e.g., job loss leading to zero income and inability to pay their dividend portion), their pledged collateral would be drawn upon to compensate token holders, further supporting the token value. The exact mechanism for this distribution from collateral would be defined in the platform's terms.

