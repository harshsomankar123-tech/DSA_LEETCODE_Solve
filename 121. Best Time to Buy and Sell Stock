class Solution:
    def maxProfit(self, prices: List[int]) -> int:
        minimum_prices_at_which_you_purchased=10**4
        maximum_profit=0
        for i in prices:
            if minimum_prices_at_which_you_purchased>i:
                minimum_prices_at_which_you_purchased=i
            if i-minimum_prices_at_which_you_purchased>maximum_profit:
                maximum_profit=i-minimum_prices_at_which_you_purchased

        return maximum_profit
