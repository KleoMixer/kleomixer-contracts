# alephium_mixer
smart contracts and sdk implementations for kleo mixer application

# our strategy at kleo
out general mixing strategy is to have users make an encrypted code linked to the coins they will have depsoited using one of our many deposit options (alph for the start). from there the users coins are withdrawn from the contract and 120 $MIX will be taken on each deposit as platform fees and developer costs. then the coins are then sent to our mixing protocol.

# mixing at kleo
once the coins have entered the main mixed entry wallet we run up to as many additional "mixed wallets" as we see needed. this number will likely scale as we get larger but for now lets say 16 total "mixing wallets". you and many other users coins will enter the entry wallet only to be randomly divided and randomly selected but never all selected "mixing wallets"; once your coins are at this stage they will be mixed and swapped randomly up to 4 times over a randomly selected number of "mixing wallets". should you not decide to withdraw after that your coins will continue to be mixed at least once a day. *notice* due to the transaction fees assigned to each alph tx the number you received may indeed be a hair smaller than what you expect, the longer left in the more this number grows. should you apply for deposit your code is immediately verified and the funds are sent from not one "mixing wallet" but randomly many and in randomly different amounts.

# immediate withdraws and mixes (not yet implemented)
options for short term and instant withdraws / sends can also be done.

# address logging (basically can't the mixing addresses be marked and then logged?)
as the protocol grows and it mixes new addresses begin to join the race as old addresses are retired and their funds (your funds) moved to the new fresh wallets.
