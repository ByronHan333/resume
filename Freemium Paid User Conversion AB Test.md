**Background**

Pocket Gems wants to offer a two-for-one promotion to non-paying customers. Specify a target group and design a test and evaluaiton protocol to find out if it maximizes incremental revenue without detriment possible full-price offer.

Assignment description: [[https://shimo.im/docs/xhyrkhVcRWwYWjhH/](https://shimo.im/docs/xhyrkhVcRWwYWjhH/)]

**Summary**

**Select Target Group**

1. On average, the conversion rate for our game is 6.77%. A non-paid player's conversion probability has dropped by 75% on average, if he/she has**one of the following traits.**
    * It is the**3rd day**since the player installed our game. [Figure 1]
    * It is the**26th session**since the player installed our game. [Figure 2]
    * Player has**earned 82 gems**. [Figure 3]
    * Player has**spent 49 gems**. [Figure 4]
2. Players with the later version iPhone/iPad is likely to convert later in session and eariler in gems spent (given the same 75%-drop threshold).
    * **19th session**(iPhone 6.1-/iPad 5.3-) vs**29th session**(iPhone 6.2+/iPad 5.4+) [Figure 5]
    * **54 gems spent**(iPhone 6.1-/iPad 5.3-) vs**49 gems spent**(iPhone 6.2+/iPad 5.4+) [Figure 6]
3. Therefore, we should select the non-paid players to target group based on his/her hardware and in-game behaivior.

**Design A/B Test and evaluation protocol**

1. After selected target group, we leave**10% of them to hold-out set**, which are users that will never experience any change for next 6 months, the**rest 90% players are experiment set**.
2. We start with 15% players in experiment set and allocate them as such:
    * 5% in control group with**regular-price**[A]
    * 5% in test group with 2-for-1**offer**[B]
    * 5% in test group with 2-for-1**offer**displayed before**hard****earn-gem task (who sees offer)**[C]
3. Evaluation metrics are:**total revenue, pay frequency**and**second-pay rate**. Topline metric is**total revenue.**
4. Experiment should**run for at least 14 days**, because 94% of multi-pay players paid second time by day 7 [Figure 7] and 74% of multi-pay players stopped paying any more by day 14 [Figure 8].
5. We can**evaluate cannibalizaiton effect**using previous metrics.**Second-pay rate**is a good**leading indicator**on cannibalization effect.**Pay frequency and total revenue**will capture 75% of the life time value variaiton by day 14.
5. Accounting for the difference between**before, during and after experiment**, we can compare AB, BC to find out the effect of offer and trigger respectively.
6. Also we need to**avoid metric dilution**by only**counting those who see regular-price/offer**.
7. At the end of 7 days, if we are confident about the result, we roll out the experiment to all of the experiment set. At the end of the 6 month, we can**evaluate the incremental revenue**by comparing**average 6-month revenue per person**between experiment set and hold-out set.
8. If we are not confident about the result, we can change offer, change trigger in experiment setup, extend experiment time or fall back to the control version.

**Analysis**

According to**Fogg's behavior model**, we can break down a player's conversion by 3 components:**Motivation, Ability and Trigger.**

![图片](https://uploader.shimo.im/f/0G00zkU0zZLY7MNK.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)

**Motivation**

Motivation is whether the product provides ample motivation for user to process through the channel.

We can appximate motivation using 4 numbers:

* day since install
* number of session played
* number of gems earned
* number of gems spent

![图片](https://uploader.shimo.im/f/x7fzmysgJvTx2IWm.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)


**Day since install**

Probability of players convert have dropped by ~78% by day 3. [Figure 1]

![图片](https://uploader.shimo.im/f/HhCYkyF3NnSFK6o7.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)

**Number of sessions played**

Probability of players convert have dropped by ~75% by 26 sessions. [Figure 2]

![图片](https://uploader.shimo.im/f/K9X1ZZBUAqeg8f2p.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)

**Number of gems earned**

Probability of players convert have dropped by ~75% by 85 gems earned. [Figure 3]

![图片](https://uploader.shimo.im/f/8UbAmyWhMifgeoBK.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)

**Number of gems spent**

Probability of players convert have dropped by ~75% by 49 gems spent. [Figure 4]

![图片](https://uploader.shimo.im/f/hK09g7YJ8SIdp8aP.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)


**Ability**

Ability is wether the offer is realistic for user in terms of their necessaity and affordability.

We can approximate this using the following traits.

* hardware version
* acquisition channel (organic, Google Ads, Facebook Ads etc.)
* country/language

Given limited data and amount of time, I only look into hardware version.

![图片](https://uploader.shimo.im/f/PlGZbG1z1jeWB4XB.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)

**(iPhone 6.2+/iPad 5.4+)**

**Session**[Figure 5.1]

![图片](https://uploader.shimo.im/f/tFU2DkdhR676gAjM.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)

**Gems spent**[Figure 6.1]

![图片](https://uploader.shimo.im/f/xUdktsay7DzaqiPv.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)

**(iPhone 6.2-/iPad 5.4-)**

**Session**[Figure 5.2]

![图片](https://uploader.shimo.im/f/C9zJ9iZiJLlUuDOA.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)

**Gems spent**[Figure 6.2]

![图片](https://uploader.shimo.im/f/taTQFwWHZfgYxNCt.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)


**Trigger**

Trigger is when it is a good time or a good format to push the offer message?

* Before vs after users spent in a key setting
* When user log in vs earn gems scene
* full-screen vs pop-out message

![图片](https://uploader.shimo.im/f/avOyzgrfbJgpl691.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)



**A/B Test Design and Evaluation**

94% of multi-payers paid 2nd payment by 7 days. [Figure 7]

![图片](https://uploader.shimo.im/f/TuMCRE5BYThOskJp.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)

74% of multi-payer stopped paying by day 14. [Figure 8]

![图片](https://uploader.shimo.im/f/KMI89mIVzr72pNwe.png!thumbnail?fileGuid=RTChyxcVCjTQct6w)





**After Thought**

1. In reality, this 2-for-1 offer experiment can extend to paid-customer when they are about to churn, i.e. BG/NBD lifetimes model.
2. We can introduce RMF Analysis/Survival Analysis to analyze churn behavior.
3. Users can be segmented using : Free-shrimp-dolphin-whale framework
4. Life cycle can be extend to acquisition-growth-active-churn.
5. And we can use unsupervised learning to add tags to the customers, and also add tags to their recency, frequency and monetization, also survival probability.
