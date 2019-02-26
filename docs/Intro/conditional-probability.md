In our last unit, we assumed that the coin flips were independent, that is, the outcome of the first didn't affect the outcome of the second. From now on, we're going to study the more interesting cases where the outcome of the first does impact the outcome of the second, and to do so you need to use more variables to express these cases.

### Medical Example
Suppose there's a patient in the hospital who might suffer from a medical condition like cancer.
Let's say the probability of having this cancer is 0.1.
$$P(Cancer) = 0.1$$

The probability of being cancer free.
$$P(\text{No Cancer}) = 0.9$$

The outcome of the blood test may be positive or negative, but like any good test, it tells me something about the thing I really care about-whether the person has cancer or not. Let's say, if the person has the cancer, the test comes up positive with the probability of 0.9.
$$P(\text{Positive | Cancer}) = 0.9$$

The negative outcome will have 0.1 probability and that's because these two things have to add to 1.
$$P(\text{Negative | Cancer}) = 0.1$$

I've just given you a fairly complicated notation that says the outcome of the test depends on whether the person has cancer or not. We call this a **conditional probability**. There's a bar in the middle, and the bar says what's the probability of the stuff on the left given that we assume the stuff on the right is actually the case.

The probability of the test giving me a positive results-a false positive result when there's no cancer is 0.2.
$$P(\text{Positive | No Cancer}) = 0.2$$

The probability of a negative outcome in case we know for a fact the person doesn't have cancer:
$$P(\text{Negative | No Cancer}) = 0.8$$

**Truth Table**

|Cancer|Test|P|
|------|----|-|
|Yes|Positive|0.09|
|Yes|Negative|0.01|
|No|Postitive|0.18|
|No|Negative|0.72|

Irrespective of cancer, finding probability of positive result:
$$P(\text{Positive Result}) = 0.27$$

### Two Coins
This time around, we have a bag, and in the bag are 2 coins, coin 1 and coin 2.

1. In advance, we know that coin 1 is fair. So P of coin 1 of coming up heads is 0.5
$$P_1(H) = 0.5$$
$$P_1(T) = 0.5$$
2. Where as coin 2 is loaded, that is, P of coin 2 coming up heads is 0.9.
$$P_2(H) = 0.9$$
$$P_2(T) = 0.1$$

So now what happens is, I'm going to remove one of the coins from this bag, and each coin, coin 1 or coin 2, is being picked with equal probability.
$$P(1) = 0.5$$
$$P(2) = 0.5$$

Let me now flip that coin once, and I want you to tell me, what's the probability that this coin which could be 50% chance fair coin and 50% chance a loaded coin. What's the probability that this coin comes up heads?

|Pick|Flip|P|
|----|----|-|
|1|H|0.25|
|1|T|0.25|
|2|H|0.45|
|2|T|0.05|

$$P(H) = 0.7$$

#### Flip Twice Head-Tail
$$P(H, T) = ?$$

Observe just the cases where head is followed by tail:

1. The probability of picking coin 1 is 0.5. For the fair coin, we get 0.5 for heads, followed by 0.5 for tails. They're together is 0.125.
2. There's a 0.5 chance of taking coin 2. Now that one comes up with heads at 0.9. It comes up with tails at 0.1. So multiply these together, gives us 0.045.

|Pick|Flip 1|Flip 2|P|
|----|------|------|-|
|1|H|H||
|1|H|T|0.5 * 0.5 * 0.5 = 0.125|
|1|T|H||
|1|T|T||
|2|H|H||
|2|H|T|0.5 * 0.9 * 0.1 = 0.045|
|2|T|H||
|2|T|T||

$$P(H, T) = 0.17$$

#### Flip Twice Tail-tail
As before, taking coin 1 & 2 at 0.5 probability. But now I'm telling you that coin 1 is loaded, so give you heads with probability of 1. And coin 2 is also loaded. It gives you heads with 0.6 probability. what's the probability of seeing tails twice?
$$P(T, T) = ?$$
$$P_1(H) = 1$$
$$P_2(H) = 0.6$$
$$P(1) = 0.5$$

The only case where you might see tails/tails is when you actually drew coin 2, and this has a probability of 0.5 times the probability of tails given that we drew the second coin, which is 0.4 times 0.4 again, and that's the same as 0.08.

|Pick|Flip 1|Flip 2|P|
|----|------|------|-|
|1|T|T|0|
|2|T|T|0.5 * 0.4 * 0.4 = 0.08|