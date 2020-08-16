# **Movie Recommendation System**

**Fastai Library or API**
- [Fast.ai](https://www.fast.ai/about/) is the first deep learning library to provide a single consistent interface to all the most commonly used deep learning applications for vision, text, tabular data, time series, and collaborative filtering.
- [Fast.ai](https://www.fast.ai/about/) is a deep learning library which provides practitioners with high-level components that can quickly and easily provide state-of-the-art results in standard deep learning domains, and provides researchers with low-level components that can be mixed and matched to build new approaches.

**Collaborative Filtering**
- Collaborative filtering is a technique used by recommender systems. In the newer, narrower sense, collaborative filtering is a method of making automatic predictions or filtering about the interests of a user by collecting preferences or taste information from many users collaborating.

**Preparing the Model**
- I have used [Fastai](https://www.fast.ai/about/) API to train the Model. It seems quite challenging to understand the code if you have never encountered with Fast.ai API before.
One important note for anyone who has never used Fastai API before is to go through [Fastai Documentation](https://docs.fast.ai/). And if you are using Fastai in Jupyter Notebook then you can use doc(function_name) to get the documentation instantly.

**Dataset**
- Fastai has its own [Dataset](https://docs.fast.ai/datasets.html).I have used [Fastai ML Dataset](https://course.fast.ai/datasets) using the following lines of codes:

```javascript
untar_data(URLs.ML_SAMPLE)
```

**Collaborative Filtering with Fastai**
- Collaborative filtering is a technique used by recommender systems. In the newer, narrower sense, collaborative filtering is a method of making automatic predictions or filtering about the interests of a user by collecting preferences or taste information from many users collaborating.
- It can be done using Fastai Collab Learner API which will do Collaborative Filtering. It is done as follows:

```javascript
collab_learner(data, n_factors=40, y_range=y_range, wd=1e-01)
```
**Recommendation of the Model**
![Image](https://res.cloudinary.com/dge89aqpc/image/upload/v1595591790/Zoom_tahofz.png)
