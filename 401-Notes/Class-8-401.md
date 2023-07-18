# Class 8 Reading Notes

These readings are about abstracting code, and releasing MVP as opposed to mature products in the software development lifecycle.  These readings are important because they are about the real world considerations of software development and not just the coding.  Abstraction is important in business because it can make code more maintainable, and MVP is important because it can prevent you from doing a lot of unnecessary work as a developer.

## Don't Repeat Yourself and the Rule of Three

- Are there any projects that you’ve built during your time at Code Fellows (or prior) which could benefit from applying the Rule of Three to DRY up your code?

> In my project for 301, I typed out the full url as seperate variable in multiple different API call functions.  While the end of the URL changed depending on the CRUD method, it would have been benificial to store the base of the URL  itself in a global variable.  That way if my server address changed. I would only have needed to change it in the single variable as opposed to in each method.

- Explain how you would dry up your code if you noticed that you are repeating the same logic in multiple places?

> I would write a helper function, global variables, or other methods that would abstract away the repetition so that changes would only need to happen in one place as opposed to in each repeating block of code.  This would make it more maintainable in the long run.

## You Aren't Gonna Need It and Minimum Viable Product

- Describe some benefits of releasing an MVP of a product.

> One of the potential benefits is preventing yourself from doing a lot of unnecessary work.  If the MVP of a product leads to clear feedback from users, your assumptions about other needed features may change radically.  If you move too far forward, you can end up with significant rework as opposed to simpler iterations on the MVP.  Another benefit is getting to test your assumptions about the product early on.  Getting feedback provides real data that can assist with the product development cylce.

- What are some potential pitfalls of waiting until a product is fully mature to release it.

> One potential pitfall of waiting for a mature product to release it is that you don't get to test product market fit. Your technological hypothesis can be correct and the software can do what you want it to do, but there may not be a business need that will make your idea profitable so you will have wasted a lot of time and resources getting to maturity when you could have pivoted much earlier in the process by realeasing an MVP.

## Things I want to know more about

- What kind of testing can be done beforehand to establish what the MVP actually is?