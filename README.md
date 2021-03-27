### My name is Mathieu Tuli, I am an MSc student in the department of Computer Science co-supervised by Sheila McIlraith and Scott Sanner at the University of Toronto and as affiliate with the Vector Institute.

![Github Stats](https://github-readme-stats.vercel.app/api?username=mathieutuli&count_private=true&show_icons=true&include_all_commits=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mathieutuli&hide=TeX&layout=compact)

### 🔭 I’m currently working on controllable text generation for task-oriented dialogue systems
All my code can be found at [controllable-text-generation](https://github.com/MathieuTuli/controllable-text-generation)

Specifically, I am focused at the intersection of AI automated planning and Machine Learning.

### I’m looking to collaborate on task-oriented dialogue so send me email if you have ideas or simply wish to chat!

### 📫 How to reach me: email is the best bet: <tuli.mathieu@gmail.com>

### Here are some other projects I (have) work(ed) on

#### [dyanmic-stable-matching](https://github.com/MathieuTuli/dyanmic-stable-matching) (Present)
In this project my colleagues and I are investigating a variant of the classic [stable matching problem](https://en.wikipedia.org/wiki/Stable_marriage_problem). The traditional setup is to have N men and women, each with associated preferences for the opposite sex, and the goal is to match each man and woman in a stable fashion. We question what happens when preferences decay over time (divorce does happen after all), and how well state-of-the-art algorithms handle time-decaying preferences and whether some are better than others. As an ambition, we are also looking into how we might improve current methods to better handle time-decaying preferences.

This variant is much more interesting froma practical standpoint, where agents in a system will have varying utilities for other agents, and finding a stable match, or the most stable match over time, can be critical to things like efficieny and long-term satisfaction.

#### [AdaS](https://github.com/mahdihosseini/adas) (Present)
In this project, my colleague ([Mahdi Hosseini](https://github.com/mahdihosseini)) and I designed a new adaptive optimization technique for stochastic gradient descent. This project is built in PyTorch. The code format, training pipeline, and general construction in my major contribution to this work, while Professor Hosseini development the optimizer theoretically prior to my involvement with the work.

#### [UHINet](https://github.com/MathieuTuli/uhinet) (2019-2020)
In this project, my colleagues and I investigated the use of satellite imagery and satellite tempearture maps to model the effect of infrastructure development on temperature changes in a city ([urban heat island effect](https://www.nationalgeographic.org/encyclopedia/urban-heat-island/) = UHI). The contributions are two-fold
1. I architected and trained a model that could interpret satellite imagery and translate it to temperature maps with 1 degree Celcius accuracy. This model allows us to understand how (large) infrastructures influence the surround temperature of an area.
2. We built a prototype interface that allowed users to navigate a map, select an area, and modify its infrastructure (e.g. park -> apartment building). We could then compare this change using our model to visualize and quantity the potential effects on the local climate.

#### [thumbnail-colour-and-view-count](https://github.com/MathieuTuli/thumbnail-colour-and-view-count) (2018)
Now an old project, this was one of the first machine learning projects I ever did on my own, tackling a problem for fun. The idea was to analyze YouTube thumbnail colour features against the resulting view count for a single topic/creator. Specifically, I focused on Ali-A, a gamer. 

To provide some more context, I noticed while watching a few of his videos back then that certain games he played were much more vibrant in colour, and as a result so were the associated thumbnail images. I also felt that those with more vibrant colours had higher view counts, so I wanted to investigate this theory. The idea behind the solution is simple: I built a KNN algorithm to process the thumbails and return the dominant colour clusters in the thumbnail, and then associated those clusters with view counts, and attempted to analyze the results.

Unfortunately, although fun and interesting, the results did not pan out. A few issues arose:
1. It was hard to account for external factors like growing popularity of YouTube and the games themselves, which could have contributed to higher view counts
2. The clustering of colours ends up resolving to blended colours that didn't really represent the initial samples well. Meaning, although the image looks very pink, there is in fact a lot of black/brown/grey around edges, in shadows, etc. that means that the image clusters towards a dark brown/pink. 

Looking back, there are many things I would do differently, although I would spend paragraphs talking about it. If you'd like to chat about it, send me an [email](tuli.mathieu@gmail.com)!
