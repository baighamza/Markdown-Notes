<b>Lesson 2: Features and labels</b>

- In machine learning, we often identify <i>features</i> and from these <i>features</i> we produce <i>labels</i>

An example of this could be figuring out the features to your favourite song. The features may be:

- Intensity
- Tempo
- Genre
- Gender of the voice singing it

And from these features, we will determine whether or not we like or don't like the song 

![1543772343464](https://raw.githubusercontent.com/HBaig30/Markdown-Notes/master/Machine%20Learning/imgs/img1.png)

Source: Intro to machine learning by Sebastien and Katie; Lesson 2: Features and Visualization

Take this as an example. Let's say that you prefer music that has high intensity but varying tempo. This places your music taste in the upper half of this graph represented by green dots. The lower half of the graph represents music with low intensity and varying tempos.

Now let's say that there is a new song that is represented by the black square illustrated above. Because of where this square is located (high intensity, mid-low tempo) we can safely say that we will enjoy this song because it's within the green-dotted area. 

This looks easy enough, but let's say that you have the following scatter plot below:



![1543773329458](https://raw.githubusercontent.com/HBaig30/Markdown-Notes/master/Machine%20Learning/imgs/img2.png)

Source: Intro to machine learning by Sebastien and Katie; Lesson 2: Features and Visualization

The data points are a lot more mixed. Let's say that a new song emerges that is once again illustrated by the black square above. Would you "like" or "dislike" this song?

The answer to that is that it is <b>unclear</b>. 

An algorithm detect <b>decision surfaces</b> from the pre-existing dataset. A decision surface is a defined region in a scatter plot where a majority of similar points lie.

![1543774295116](https://raw.githubusercontent.com/HBaig30/Markdown-Notes/master/Machine%20Learning/imgs/img3.png)

Source: Intro to machine learning by Sebastien and Katie; Lesson 2: Features and Visualization

There are two decision surfaces here, the red cross and the blue circle

