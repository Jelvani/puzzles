# Solution: 4 men crossing a bridge

One option is to ofcourse brute force this puzzle. But a method of thinking about this is to realize that any time you have 2 people crossing the bridge, you want to minimize the lost time potential of the 2 people crossing the bridge. This means you want to always have the slowest people cross together, and kill 2 birds with 1 stone. 

Also, realize that we always need a person to come back the way he came, because we need the torch. We want this person to be one of the faster men, and not a slow poke. 

So how do we approach this? Well first lets setup our fast man to be on the other side of the bridge, so we are not stuck with a slow man comning back when we cross the 2 slowest men to minimize lost potential.

1. Man 1 and Man 2 cross
2. Man 1 returns

**Time used: 3 min**

3. Man 3 and Man 4 cross
4. Man 2 returns

**Time used: 12 min**

5. Man 1 and Man 2 cross

**Time used: 2 min**

Therefore, we cross all men and used 17 min exactly.