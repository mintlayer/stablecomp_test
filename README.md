# stablecomp_test
Stablecomp solidity test


The purpose of this test is evaluate your basic Solidity development skills, whether you can write clean maintainable code and to look at how you go about testing your code.

The idea is to create a token, an erc-20, with a total supply of 1_000_000 tokens and distribute it amongst 5_000 different addresses. There should be 2 separate vesting schedules and 2_500 addresses should be on vesting schedule 1 with the remaining 2_500 on schedule 2.

Vesting schedule 1 should start vesting immediately with no cliff and should vest at a rate of 5%/monthly so all tokens are vested after 20months.
Vesting schedule 2 should have a vesting cliff of 4 months and then vest at 6.25%/month, taking a total of 16months to finish vesting.
