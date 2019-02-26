Probability is just the opposite of statistics. Put differently, in statistics we are given data and try to infer possible causes that relate to the data, whereas in probability we are given the description of the causes and we'd like to predict the data.

Let's talk about a fair coin. The probability of the coin coming up heads is written in this P notation. This reads probability of the coin coming up heads. And in a fair coin, the chances are 50%. That is, in half the coin flips, the coin should come up heads. In probability we often write 0.5, which is half of 1. 

So a probability of 1 means it always occurs. A probability of 0.5 means it occurs half the time.

**What's the probability of observing heads and heads if you flip the same unbiased coin twice?**
$$P(H) = 0.5$$
$$P(T) = 0.5$$
$$P(H, H) = ?$$
$$P(H, H) = P(H) * P(H)$$
$$P(H, H) = 0.5 * 0.5 = 0.25$$

**Truth Table**

|Flip 1|Flip 2|Probability|
|------|------|-----------|
|H|H|0.25|
|H|T|0.25|
|T|H|0.25|
|T|T|0.25|

The truth table gets more interesting when we ask different questions. Suppose we flip our coin twice. What we care about is that exactly one of the two things is heads, and thereby exactly the other one is tails. For a fair coin, what do you think the probability would be that if I flip it twice we would see heads exactly once?

$$P(exactly one H) = 0.5(sum of 2nd & 3rd case)$$

I take a fair coin and flip it 3 times, and I want to know the probability that exactly 1 of those 3 flips comes up heads.

|Flip 1|Flip 2|Flip 3|Probability|
|------|------|------|-----------|
|H|H|H|1/8|
|H|T|H|1/8|
|T|H|H|1/8|
|T|T|H|1/8|
|H|H|T|1/8|
|H|T|T|1/8|
|T|H|T|1/8|
|T|T|T|1/8|

$$P(\text{exactly one H in 3 flips}) = 3 * \frac{1}{8} = 0.375$$

---
### If we change probability of the flip

$$P(H) = 0.6$$
$$P(T) = 0.4$$

**Truth Table**

|Flip 1|Flip 2|Probability|
|------|------|-----------|
|H|H|0.36|
|H|T|0.24|
|T|H|0.24|
|T|T|0.16|

|Flip 1|Flip 2|Flip 3|Probability|
|------|------|------|-----------|
|H|H|H|-|
|H|T|H|-|
|T|H|H|-|
|T|T|H|0.096|
|H|H|T|-|
|H|T|T|0.096|
|T|H|T|0.096|
|T|T|T|-|

$$P(\text{exactly one H in 3 flips}) = 3 * 0.096 = 0.288$$

Suppose we throw a fair die twice. What do you think the probability of a double is?
Double means both outcomes are identical with the same number regardless of what that number is.

|Throw-1|Throw-2|Probability|
|-------|-------|-----------|
|1|1|1/36|
|2|2|1/36|
|3|3|1/36|
|4|4|1/36|
|5|5|1/36|
|6|6|1/36|

$$P(Double) = 6 * \frac{1}{36}= 0.1667$$