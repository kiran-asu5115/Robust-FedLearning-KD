# CSE598- Machine Learning Security and Fairness Project

<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Towards Robust Federated Learning using
Knowledge Distillation Techniques</h3>
  <p align="center">
    Federated learning architecture using Knowledge Distillation along with robustness in our algorithm to common
training-time adversarial attacks.
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#frameworks-and-tools-used">Frameworks And Tools Used</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#references">References</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project


This is the project for the course CSE 598: ML Security and Fairness. It
presents a literature survey that discusses pertinent related
works, shortcomings, and the background material used for
project execution. It outlines the main contributions
of our work and the challenges faced during the execution of
Federated learning. Further, we discusses the core methodology and
the stages of execution followed during the project. In the end, we
comprehensively defines the experimental setups and results
obtained, followed by conclusions and future work.

High level overview:
* Knowledge Distillation Techniques for Federated Learning
* Improving Fairness and Robustness of Federated Learning
Architectures


<p align="right">(<a href="#top">go to top</a>)</p>

### Frameworks And Tools Used

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [Python](https://www.python.org/)
* [Tensorflow](https://www.tensorflow.org/)
* [Sklearn](https://scikit-learn.org/)

<p align="right">(<a href="#top">go to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

This section contains instructions on setting up the project locally.
To get a local copy up and running follow these simple steps.

There are two folders, codebase and report each containing their separate dependencies and code.
To install the required dependencies, run

```
pip3 install -r requirements.txt
```

We provide a jupyter notebook that simulates the federated learning implementation. To run that, make sure you are under the Codebase folder, and

```
jupyter notebook
```
then open ```feddistillation.ipynb```, and directly run the notebook cell by cell to reproduce the results.



<p align="right">(<a href="#top">go to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">go to top</a>)</p>

<!-- REFERENCES -->
## References

* [FedMD: Heterogenous Federated Learning via Model Distillation
](https://arxiv.org/abs/1910.03581)
* [Ditto: Fair and Robust Federated Learning
](https://arxiv.org/abs/2012.04221)

<p align="right">(<a href="#top">go to top</a>)</p>
