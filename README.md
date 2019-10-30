# gosteau

A web service that plans and buys your groceries locally. Because anyone can cook! Reduce food waste, reduce cost, and eat healthier.

## Features

- Meal Planning
  - Gosteau helps plan meals specific to your family.
  - Gosteau can import premium recipes from sources such as American's Test Kitchen, BBC good eats, AllRecipes and other URL's. _(Note: for premium services, you will need a subscription to access the recipe, Gosteau just provides the ingredient list)._
  - Intelligent suggestions for meals to make.
- Grocery purchasing
  - Gosteau can order your meal plan via Amazon Fresh. You can schedule pick up or delivery.
  - Other grocery stores are on the way
- Communication via chat
  - You can communicate with Gosteau by sending him a recipe you found that you want to make. 
  - He can remind you to order your groceries.

## Pricing

Currently, Gosteau is an entirely free service that makes it's money via affliate links by Amazon Fresh.
In the future, there will be paid plans that will include premium features.

I have no plans to make this supported by ads, but based on community feedback, I will consider it.

## Why not use (insert meal kit in a box service here) instead?

Wouldn't you rather get your groceries from the safeway down the street rather than being shipped to you in a box from California?
The prices of shipping is baked into the price of the meal kit service.

While it's not guaranteed, you're much more likely to get local produce by shopping from a local store.

## Bugs or suggestions

If you have a suggestion or feature you would like to see, submit an issue on github or email me directly at matt@gosteau.com.

## Future areas of improvement

These are the next features that I want to support:

- Family accounts and joining accounts together
- More grocery providers
- Store user recipes
- Allow modifications and notes for recipes to be stored/shared

Feel free to send me an email or open a github issue if you have a feature you want.

## Why did you build Gosteau?

I built Gosteau because I was tired of coming up with a meal plan each week and shopping at two different grocery stores (one for produce and one for everything else).
In America, 30-40% of food (or 133 billion pounds) is wasted. 
Most of it is produce, which we tend to buy and throw out because we don't know.
The key to solving food waste is not buying produce that would have been made into juice, but by planning what you are going to eat.
Meal planning is hard and difficult.
It requires pre-planning what you want to eat before you buy it and sticking to your plan.
I built and designed Gosteau because I was tired of planning the meals each week, noting them on the sticky note on the fridge, then losing the sticky note.
My life would be easier if I could just pick up my groceries and there was some central place where all our meals were planned.

Enter Gosteau.

The first meal planner that goes the extra mile and 

## Privacy

We don't use Google Analytics.
The only tracking we use is {} and their privacy policy can be here.

I do my best to keep all PPI (Personally Identifying Information) off our servers.
Review the repo as all our code is stored here.
If you find a flaw in our ability to keep your data safe from everyone (including us), open a PR or issue and we will address it.
Your user data is stored on our servers encrypted as a binary blob, which we do not have access to.
Optionally, you can choose to provide data to us to use as a machine learning set.
What is included in the data you provide is detailed {here}, but in short is is things like 

 - Family size
 - Preferences for recipes
 - State/Country
 - Shopping budget

What it will NOT include:

 - Address
 - Name
 - Household income

This will improve the suggestions that the meal recommendation system makes.
All data that is released to us becomes public, and will be included as part of this repo under **/data**.

We will never sell your data as we don't have it or have given it away for free.

## License

The code provided here is for your benefit.
Since Gosteau is offered for free, everything is licensed under 

