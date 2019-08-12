---
title: Statistical Significance in the World of B2B SaaS
date: '2019-08-11'
spoiler: Are you crying over a panel of B2C growth experts chatting about their AB tests? Me too. 
---

```

Dear B2C Growth Teams, 

Feel free to bounce away, we’ve heard enough about your infinite backlog 
of experiments that flow into an infinite growing base of users to achieve
significance in a matter of minutes/days. 

Sincerely, B2B Growth Teams

```

Okay, now that we got that out of the way we can chat about how statistical significance is so tricky in B2B SaaS. To start, your target market isn’t all consumers, it’s a subset of businesses looking to solve a particular pain point. As a result, your funnel is restricted and the base of users you have to experiment with will decrease substantially as you move further and further down.


We used [frequentist statistics](https://www.statisticshowto.datasciencecentral.com/frequentist-statistics/) when looking at sample sizes and evaluating our experiments. 

Our flow: 
* Look at historical data (if we have it) to get a baseline conversion rate 
* Predict the % increase our experiment will have on that conversion rate
* Plug this into Evan Miller’s sample size calculator 
* Build out the experiment and stop it once we hit that sample size 

---

When starting a growth team at Jobber, we prioritized a scientific approach and made the conscious decision to hold ourselves accountable to proper experimentation. Statistical significance was at the core of our decision making while leaving our educated opinions on the sidelines. 

Sounds good, right? One problem, our trusty sample size calculator continuously spits back a number of samples to reach 95% confidence that will take months to reach. 

>"Buzz, your sample size" 

![Home Alone Woof](./woof.gif)

So what does a savvy growth person do? 

Well, we increase the % lift we believe we will see in order for a sample size to get smaller level, which in turn, gets us the thumbs up to go ahead and ship that experiment off into the wild. 

Raise your hand if you've ever played with a sample size calculator to fit a certain time frame? 

![Guilty Caption: "Me!"](./guilty2.gif)

---

##So… what are we to do? 

After a few long and drawn out experiments, we began looking at other approaches. Specifically, a shift into Baysien statistics which welcomes an individual's faith in the predicted result of the experiment. By adding this into the equation, we can make faster decisions in a short amount of time. This jumped us into a brand new shiny calculator.  

Now, I’m not a statistician… so I’m not going to get into the debates behind the theory. All I know is Baysien gave our team another tool to evaluate our experimentation in areas with volume constraints. 

--- 

##Is it perfect? No. 

We’ve ran into issues with positive results in our experiments with both Bayesian & Freuquentist statistics. Software is always changing, as well as your target market. 

One change sees a positive lift, but then product team A releases something new and marketing changes its positioning. Suddenly, your change is now doing nothing for the business. 

Variables are consistently being manipulated in software. I was the snob in sprint reviews pointing to the importance of statistical significance every test ran across the business. Guess what? If the company listened to me, we would be moving at a snail's pace. 

Now, our team continues to be a data-focused team taking an experimental approach to growth opportunities. We leverage both frequentist & bayesian statistics pending the are of the funnel that we are working in. Our main goal is continuous learning, and we accept the constraints of volume we find ourselves in.

We’re still trying to figure this out…and we will continue to play with different ways to evaluate & optimize our experimental process. At the end of the day, get out and learn. Be honest about your approach and transparent with your results. 

In B2B, we can’t solely rely on statistical significance to make proper decisions. Why fight it? Use it when you can, forget it when it doesn’t. All we can do is try to make the best decision possible with the variables we are given. 

---
