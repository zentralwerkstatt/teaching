# MAT594SP: Aesthetics and Politics of Artificial Intelligence

Wednesdays and Fridays, 2-4, Elings 2003

## Description

The class starts from a basic hypothesis, put forward by Philip Agre in the late 1990s: ["AI is philosophy underneath"](https://web.stanford.edu/group/SHR/4-2/text/agre.html). Given the rapid development of the field since 2012, does this hypothesis hold? When we talk about artificial intelligence today, we talk about highly specialized machine learning models. Unlike in the 1990s, the primary function of these models is not the mechanization of reason but the mechanization of perception, most prominently the mechanization of vision. As a consequence, the tasks that many machine learning models operate on are aesthetic tasks, ranging from the classification of images in regard to their content and form to the generation of completely new images.

At the same time, the technical opacity of many machine learning models makes it inherently difficult to properly evaluate their results. This is complicated even further whenever a model is deployed as a product and opacity becomes a desirable property. In fact, the interpretability of machine learning models — their ability to generate and/or facilitate explanations of their results — has not only become an independent field of research within computer science but has also grown into an increasingly important legal challenge. Hence, the once speculative phenomenological question "how does the machine perceive the world" suddenly becomes a real-world problem.

Contemporary machine learning models thus raise a set of issues that are completely independent of the ones raised by the possibility of a future general artificial intelligence. Most prominently, they are real-life socio-technical systems that have politics. Adapting Agre's hypothesis: AI is aesthetics and politics underneath.

Participants in the class meet twice weekly to investigate this peculiar nexus of aesthetics and politics in contemporary machine learning through equal parts of critical reading and technical reviews (of technical papers and code examples).

## Syllabus

:book: = article/book/blog post; :mortar_board: = talk; :computer: = source code close reading; :vhs: = video in class

Class GitHub repository: https://github.com/zentralwerkstatt/MAT594SP.

### 4/4: Introduction

- :book: Ceglowski, Maciej, [Superintelligence. The Idea That Eats Smart People](http://idlewords.com/talks/superintelligence.htm) (2016)
- :book: Krakovna, Victoria, [Is There a Tradeoff Between Immediate and Longer-term AI Safety Efforts?](https://vkrakovna.wordpress.com/2018/01/27/is-there-a-tradeoff-between-safety-concerns-about-current-and-future-ai-systems/) (2018)

### 4/6: Artificial Intelligence as a Philosophical Project

- :book: Turing, Alan M., [Computing Machinery and Intelligence](https://www.jstor.org/stable/2251299), Mind 59, no. 236 (1950), 433–60
- :book: Searle, John R., [Minds, Brains, and {rograms](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/DC644B47A4299C637C89772FACC2706A/S0140525X00005756a.pdf/minds_brains_and_programs.pdf), Behavioral and Brain Sciences 3, no. 3 (1980), 417–24
- :book: Nagel, Thomas, [What It’s Like to Be a Bat](https://www.jstor.org/stable/2183914), The Philosophical Review 83, no. 4 (1974), 435–450
- :book: Agre, Philip E., [The Soul Gained and Lost. Artificial Intelligence as a Philosophical Project](https://web.stanford.edu/group/SHR/4-2/text/agre.html), SEHR 4, no. 2 (1995)
- :book: Agre, Philip E., [Toward a Critical Technical Practice: Lessons Learned in Trying to Reform AI](http://polaris.gseis.ucla.edu/pagre/critical.html) (1997)
          
### 4/11: History of Deep Learning

- :book: Krizhevsky, Alex et. al., [Imagenet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf), Advances in Neural Information Processing Systems (2012)
- :book: Kurenkov, Andrey, [A 'Brief' History of Neural Nets and Deep Learning](http://www.andreykurenkov.com/writing/a-brief-history-of-neural-nets-and-deep-learning/) (2015)
- [The neural network zoo](http://www.asimovinstitute.org/neural-network-zoo/) (2016)

### 4/13: Limits of Deep Learning

- :book: Katz, Yarden, [Manufacturing an artificial intelligence revolution](https://ssrn.com/abstract=3078224) (2017)
- :book: Marcus, Gary, [Deep Learning. A Critical Appraisal](https://arxiv.org/abs/1801.00631) (2017)
- :book: Lake, Brenden M. et. al., [Building Machines That Learn and Think Like People](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/A9535B1D745A0377E16C590E14B94993/S0140525X16001837a.pdf/div-class-title-building-machines-that-learn-and-think-like-people-div.pdf), Behavioral and Brain Sciences (2017)
- :computer: https://github.com/zentralwerkstatt/MAT594SP/blob/master/1-generalization.ipynb

### 4/18: Deep Dreaming I
          
- :book: McDonald, Kyle, [A Return to Machine Learning](https://medium.com/@kcimc/a-return-to-machine-learning-2de3728558eb) (2016)
- :book: Mordvintsev, Alexander et. al., [Inceptionism. Going Deeper into Neural Networks](https://research.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html) (2015)
- :computer: [https://github.com/google/deepdreamgoogle/deepdream](https://github.com/google/deepdreamgoogle/deepdream)
- :book: Chayka, Kyle, [Why Google's Deep Dream is Future Kitsch](https://psmag.com/environment/googles-deep-dream-is-future-kitsch) (2015)
- :book: Rayner, Alex, [Can Google’s Deep Dream Become an Art Machine?](https://www.theguardian.com/artanddesign/2016/mar/28/google-deep-dream-art), The Guardian (2016)
          
### 4/20: Deep Dreaming II

- :computer: https://github.com/zentralwerkstatt/MAT594SP/blob/master/2-deepdream.ipynb

### 4/25: Feature Visualization I

- :book: Chollet, Francçois, [How Convolutional Neural Networks See the World](https://blog.keras.io/how-convolutional-neural-networks-see-the-world.html) (2016)
- :book: Olah, Chris, [Feature Visualization](https://distill.pub/2017/feature-visualization) (2017)
- :book: Olah, Chris, [The Building Blocks of Interpretability](https://distill.pub/2018/building-blocks) (2018)
- :computer: https://github.com/zentralwerkstatt/MAT594SP/blob/master/3-features.ipynb
          
### 4/27: Feature Visualization II

- :mortar_board: 3pm: Mhaskar, Hrushikesh, A New Look at Machine Learning as Function Approximation (Webb Hall 1100)
     
### 5/2: Feature Visualization III

- :computer: Goh, Gabriel, [Image Synthesis from Yahoo's open_nsfw](https://open_nsfw.gitlab.io/) (2016)
- :book: Offert, Fabian, ["I know it when I see it". Visualization and Intuitive Interpretability](https://arxiv.org/abs/1711.08042) (2017)
- :book: Szegedy, Christian et. al., [Intriguing Properties of Neural Networks](https://arxiv.org/abs/1312.6199) (2013)
- Zech, John, [What are Radiological Deep Learning Models Actually Learning?](https://medium.com/@jrzech/what-are-radiological-deep-learning-models-actually-learning-f97a546c5b98) (2018)
- :computer: https://github.com/zentralwerkstatt/MAT594SP/blob/master/4-nsfw.ipynb
          
### 5/4: Interpretability I

- :book: Lipton, Zachary C., [The Mythos of Model Interpretability](https://arxiv.org/abs/1606.03490f) (2017)
- :book: Dijkstra, Edsger W., [On Anthropomorphism in Science](https://www.cs.utexas.edu/users/EWD/transcriptions/EWD09xx/EWD936.html) (1985)
- :book: Kim, Been et. al., [Towards a Rigorous Science of Interpretable Machine Learning](https://arxiv.org/abs/1702.08608) (2017)
- :book: Kim, Been et. al., [How do Humans Understand Explanations From Machine Learning Systems? An Evaluation of the Human-interpretability of Explanation](https://arxiv.org/abs/1802.00682) (2018)
          
### 5/9: GANs

- :book: Goodfellow, Ian J. et. al., [Generative Adversarial Nets](https://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf), Advances in Neural Information Processing Systems (2014)
- :book: Goodfellow, Ian J. et. al., [Improved Techniques for Training GANs](https://arxiv.org/abs/1606.03498) (2016), chapter 4 only
- :computer: https://github.com/zentralwerkstatt/MAT594SP/blob/master/5-gans.ipynb
          
### 5/16: Word Embeddings

- :mortar_board: 12pm: Wang, William, Deep Learning for Computational Social Science (SSMS 1310)
- :book: Mikolov, Tomas et. al., [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781) (2013)
- :book: Offert, Fabian, [Intuition and Epistemology of High-dimensional Vector Space](https://zentralwerkstatt.org/post_vsm.html) (2017)
- :computer: [How to Make a Racist AI without Really Trying](http://blog.conceptnet.io/posts/2017/how-to-make-a-racist-ai-without-really-trying/)
- :book: Bolukbasi, Tolga et. al., [Man Is to Computer Programmer as Woman Is to Homemaker? Debiasing Word Embeddings](https://papers.nips.cc/paper/6228-man-is-to-computer-programmer-as-woman-is-to-homemaker-debiasing-word-embeddings.pdf), Advances in Neural Information Processing Systems (2016)
- :computer: https://github.com/zentralwerkstatt/MAT594SP/blob/master/6-nlp.ipynb

### 5/18: Reinforcement Learning

- :mortar_board: 2pm: [Luo, Rodger](http://rodgerluo.com/) and Green, Sam, Visualization for Deep Reinforcement Learning (Elings 2003)

### 5/23: RNNs

- :book: Karpathy, Andrej, [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) (2015)
- https://www.khanacademy.org/computing/computer-science/informationtheory
- :computer: Goldberg, Yoav, [The Unreasonable Effectiveness of Character-level Language Models](http://nbviewer.jupyter.org/gist/yoavg/d76121dfde2618422139)
- :computer: https://github.com/zentralwerkstatt/MAT594SP/blob/master/6-nlp.ipynb

###  5/25: FAT

- :vhs: [The Trouble with Bias](https://www.youtube.com/watch?v=fMym_BKWQzk&t=698s) (2017)
- :book: Murphy, Heather [Why Stanford Researchers Tried to Create a 'Gaydar' Machine](https://www.nytimes.com/2017/10/09/science/stanford-sexual-orientation-study.html), New York Times (2017)
- :book: Mattson, Greggor [Artificial Intelligence Discovers Gayface. Sigh](https://greggormattson.com/2017/09/09/artificial-intelligence-discovers-gayface/) (2017)
- :book: Joy Buolamwini, Timnit Gebru, [Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification](http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf), Proceedings of Machine Learning Research (2018)
- [Gender Shades](http://gendershades.org/)
- Crispin, Sterling, [Data Masks](http://www.sterlingcrispin.com/data-masks.html) (2013-2015)
- Blas, Zach, [Facial Weaponization Suite](http://www.zachblas.info/works/facial-weaponization-suite/) 
- :book: Frank Pasquale, The Black Box Society (2015), excerpts

### 5/30: Interpretability II

- :book: Crawford, Kate et. al., [Seeing without Knowing: Limitations of the Transparency Ideal and its Application to Algorithmic Accountability](http://journals.sagepub.com/doi/full/10.1177/1461444816676645) New Media and Society (2016)
- :book: Selbst, Andrew D. et. al., [The Intuitive Appeal of Explainable Machines](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3126971) (2018)
- :book: Weinberger, David, [Optimization over Explanation](https://medium.com/berkman-klein-center/optimization-over-explanation-41ecb135763d) (2018)
- :book: Doshi-Velez, Finale et. al., [Accountability of AI under the Law: The Role of Explanation](https://arxiv.org/abs/1711.01134) (2017)
- :book: Goodman, Bryce et. al., [EU Regulations on Algorithmic Decision-making and a "Right to Explanation"](https://arxiv.org/abs/1606.08813) (2016)
- [EU GDPR](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32016R0679&from=EN)

## Further Resources

### Interpretability

- [Proceedings of NIPS 2016 Workshop on Interpretable Machine Learning for Complex Systems](https://arxiv.org/html/1611.09139v1)
- [Proceedings of NIPS 2017 Symposium on Interpretable Machine Learning](https://arxiv.org/html/1711.09889)
- [Ahn Nguyen's website](http://anhnguyen.me/research/)
- [Been Kim's website](https://beenkim.github.io/)
- [Rich Caruana's website](https://www.microsoft.com/en-us/research/people/rcaruana/#!publications)
- [Chris Olah's Blog](http://colah.github.io/)

### FAT

- [Toward Ethical, Transparent and Fair AI/ML: A Critical Reading List](https://medium.com/@eirinimalliaraki/toward-ethical-transparent-and-fair-ai-ml-a-critical-reading-list-d950e70a70ea)
- [Mirror Mirror. Reflections on Quantitative Fairness](https://shiraamitchell.github.io/fairness/)
- [FAT 2018 conference proceedings](http://proceedings.mlr.press/v81/)
- [Critical Algorithm Studies reading list](https://socialmediacollective.org/reading-lists/critical-algorithm-studies/)
- [Anatomy of an AI System]( https://anatomyof.ai)

### Art

- [PAGE, British Computer Arts Society journal](http://computer-arts-society.com/page)
- [ITP-NYU Neural Aesthetic class (taught by Gene Kogan)](http://ml4a.github.io/classes/itp-F18/)
- [Machine Learning for Artists](https://ml4a.github.io/ml4a/)
- [DIGIMAG 76: Smart Machines for Enhanced Arts](https://issuu.com/digicultlibrary/docs/digimag76/1?ff=true)
- [A Return to Machine Learning](https://medium.com/@kcimc/a-return-to-machine-learning-2de3728558eb)
- [Garnet Hertz: Critical Making](http://conceptlab.com/criticalmaking/)

### History and Philosophy

- [Philipp A. Agre's (archived) website](http://polaris.gseis.ucla.edu/pagre/)
- [A Queer History of Computing](http://rhizome.org/editorial/2013/feb/19/queer-computing-1/)
- [Philosophy & Technology special issue: Rethinking Art and Aesthetics in the Age of Creative Machines](https://link.springer.com/journal/13347/30/3)
- [The Neural Net Tank Urban Legend](https://www.gwern.net/Tanks)
- [AI Magazine special issue on the Turing test](https://www.aaai.org/ojs/index.php/aimagazine/issue/view/213)

### Technology

- [Stanford CS221: Artificial Intelligence: Principles and Techniques](https://web.stanford.edu/class/cs221/)
- [Stanford CS231: Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/optimization-2/)
- [Deep Learning book (Goodfellow)](http://www.deeplearningbook.org/)
- [Deep Learning With Python book (Chollet)](https://www.manning.com/books/deep-learning-with-python)
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/)
- [MIT 6.080/6.089: Great Ideas in Theoretical Computer Science (taught by Scott Aaronsen)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-080-great-ideas-in-theoretical-computer-science-spring-2008/index.htm)
- [Explanation of the mathematics behind GANs](https://lilianweng.github.io/lil-log/2017/08/20/from-GAN-to-WGAN.html)
- [An overview of gradient descent algorithms](http://ruder.io/optimizing-gradient-descent/)
- [Academic Torrents datasets](http://academictorrents.com)
