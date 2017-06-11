# Predicting User Churn

There are 2 Jupyter notebooks that shows my work on predicting user churn for the [Mood Listener](http://www.moodlistener.com) iOS App created by my company [Bear & Fox](http://www.bearandfox.co/projects.html). The app was created as a side project in our free time. It is a collection of music playlists handpicked by us, tailored to different moods such as 'good morning', 'rainy days' etc. The music can be streamed through the application which is sourced by SoundCloud API. It is a lightweight, simple to use app for a group of people that shares a particular music taste. You can download the app from this [link](https://itunes.apple.com/gb/app/mood-listener/id1033906190?l=tr&mt=8).

The app was released in the Apple App Store in September 2015. Shortly after launch, it was featured in [producthunt.com](http://www.producthunt.com) and was listed in top 10 for the day, reaching as high as second position. This lead to the attention of multiple media outlets, where the app was published in multiple sources including [AppAdvice](http://www.appadvice.com). Publications has lead to some spikes in downloads, however, we have decided to follow a particular acquisition strategy. We contacted the owners of Turkey based popular instagram accounts that were sharing type of posts that we believed to be inline with the music we have been curating. We have started an [instagram account](https://www.instagram.com/mood_listener/) sharing a taste of music in the form of short music videos along with images. We have collaborated with the these popular instagram accounts by featuring them in the Mood Listener application in the form of custom playlists, letting them broadcast the news to their followers. This has lead to as much as 17,000 followers on Instagram and a good number of downloads. We have received around 10,000 downloads in general over 2 years with a quite loyal customer base.  

### What is Churn?

As described in [this](http://blog.yhat.com/posts/predicting-customer-churn-with-sklearn.html) blog post; 

"Churn Rate is a business term describing the rate at which customers leave or cease paying for a product or service. It's a critical figure in many businesses, as it's often the case that acquiring new customers is a lot more costly than retaining existing ones (in some cases, 5 to 20 times more expensive)."

In broad terms, churn is user inactivity. However, it is usually a vague term that is defined in various ways depending on the use case. In our case, I will be defining a churned user as a user that downloads, uses the app once and and never comes back. Therefore I will we investigating the causes of this behaviour and, hopefully, accurately predict wether a user will 'churn' on day 1 based on its demographic features. 