What is dimensionality reduction

Dimensionality Reduction refers to any technique which maps information in many dimensions onto fewer dimensions. While there are uses for it across many different areas of inquiry, it's especially popular in biological sciences where the datasets have so, so many dimensions.

Why would you want to reduce the number of dimensions? Isn't more information about something you're studying always better? Well, yes and no!

One reason you might want to reduce the number of dimensions you're working with is if a bunch of your dimensions are contributing largely the same information. This is called multicollinearity, and if you want to use statistical or machine learning methods to figure out how much different values in each feature contribute to the probability of a data point being a member of one group versus another, multicollinearity can really muck things up. Dimensionality reduction can help you combine all of the features that are contributing basically the same thing into a smaller group of components.

The price of this is that you lose interpretive power.

The other big reason you might want to perform dimensionality reduction is so that you can actually look at some approximation of the shape or distribution of all of your data. Our datasets can have hundreds of different kinds of measurements, and unfortunately we're limited to being able to see three dimensions visually. Ideally, it's best if we can get it down to two so that we don't have to rotate things in order to see what is happening.

Are there other ways to do this? You can tie the extra dimensions to other visual properties, and this can be very effective. But after a point, this gets to be visually busy, and you certainly can't make it to hundreds of dimensions.

So, having established that this is a useful thing to be able to do, I'm going to talk about three different popular methods for doing this, and go through some examples of applications to datasets

What methods are there

What is PCA
How does it work
What can you use it for
How do you use it practically

What is T-SNE
* Teenage Student Ninja Eagles
How does it work
What can you use it for
How do you use it practically

What is UMAP
How does it work
What can you use it for
How do you use it practically

Case studies
RV144
CMV