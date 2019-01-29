
<h1 align="center">
    <br>
    <a href="#"><img src="https://i.imgur.com/4IovkRE.jpg" alt="Malarkey!" width="200"></a>
    <br>
    Malarkey!
    <br>
</h1>

<h4 align="center">A powerful tool for description classification using generative adversarial networks.</h4>

<p align="center">
    <a href="http://pytorch.org/">
        <img src="http://forthebadge.com/images/badges/made-with-python.svg" alt="">
    </a>
    <img src="http://forthebadge.com/images/badges/built-with-science.svg" alt="">
    <img src="http://forthebadge.com/images/badges/makes-people-smile.svg" alt="">
</p>

<p align="center">
    <a href="#related-workd">Related Works</a> •
    <a href="#learning-goals">Learning Goals</a> •
    <a href="#engineering-goals">Engineering Goals</a> •
    <a href="#ux-goals">UX Goals</a> •
    <a href="#license">License</a>
</p>

## Related Works

[Learning to Generate Reviews and Discovering Sentiment](https://arxiv.org/abs/1704.01444) is a great paper by [OpenAI](https://openai.com/), which builds upon the principles used in [Representation Learning](https://arxiv.org/abs/1206.5538) (Bengio, 2013) in an exciting new way. These two papers inspired me to do this project.

## Learning Goals
* Generative Recurrent Neural Networks
* Adversarial Classification
* Chose between PyTorch and TensorFlow

## Engineering Goals
* Build an unsupervised generative network to create realistic tweets given a prompt
* Train a sister network to classify tweets using the feature vectors of the generative network
* Use Steven and a third sibling network to create an adversarial network pair by using both the generated data and real tweets

## UX Goals
* Build a robust and user friendly way to collect human data on immeasurable features (ie. truth vs. lies, malarkey meter, funniness)

<!--
## Conclusion
<p align="center">
    <a href="https://saythanks.io/to/Atif-Mahmud">
        <img src="https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg">
    </a>
</p>
-->

## License

MIT

---

> [Atif Mahmud](https://atif-mahmud.github.io) &nbsp;&middot;&nbsp;
> GitHub [@Atif-Mahmud](https://github.com/Atif-Mahmud) &nbsp;&middot;&nbsp;
> Twitter [@Atif_Mahmud101](https://twitter.com/Atif_Mahmud101)
