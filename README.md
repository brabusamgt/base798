# base798
Ranking Most Active Senders
from collections import Counter

senders = Counter()
for tx in block.transactions:
    senders[tx["from"]] += 1

print(senders.most_common(5))
