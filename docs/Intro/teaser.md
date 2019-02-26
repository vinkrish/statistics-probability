I figure I'll start with giving you a teaser, a challenging teaser. I will prove in a second that you are unpopular. The reason why I show this is to show you how deep statistics is and how we can easily fool ourselves.
So let's dive in.

Let's say there are two types of people for simplicity: **Type A** and **Type B**.

- Type A are the popular one, they have 80 friends
- Type B are less popular, they only have 20 friends

You might now say that I don't know which type you are.
I will compute what's called the **expected** or **average** number of friends.
To do so, I assume that half of the people are of type A
and half of the people are of type B.

You have a 50% chance of being a type A and a 50% chance of being a type B.

$$\frac{50}{100} * 80 + \frac{50}{100} * 20$$
$$40 + 10 = 50$$
 
50 friends! so far, so good, but why are you unpopular?  

Let's pick a random one of your friends.
Before I raise the question how many friends this person has,
let's consider that this might be either a type A or a type B person.

- What are the chances you picked a type A friend?  
- What are the chances you picked a type B?

This should be a number between **0** and **1**.

You link to type A and to type B in a proportion of 80 to 20.

|Type|Proportion|
|----|--------|
|A|0.8|
|B|0.2|

That means most of your friends you link to are type A.

**How many friends does this friend of yours have?**  
The way to get there is with 0.8 chance you'll pick a type A who has 80 friends
and with 0.2 chance you'll pick a type B who has 20 friends.

$$0.8 * 80 + 0.2 * 20$$ 
$$64 + 4 = 68$$