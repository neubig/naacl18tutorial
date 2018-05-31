# Modelling Natural Language, Programs, and their Intersection

A tutorial at [NAACL 2018](http://naacl2018.org) by [Graham Neubig](http://phontron.com) (CMU) and [Miltos Allamanis](https://miltos.allamanis.com) (Microsoft).

**Abstract:** As computers and information grow a more integral part of our world, it is becoming more and more important for humans to be able to interact with their computers in complex ways. One way to do so is by programming, but the ability to understand and generate programming languages is a highly specialized skill. As a result, in the past several years there has been an increasing research interest in methods that focus on the intersection of programming and natural language, allowing users to use natural language to interact with computers in the complex ways that programs allow us to do. In this tutorial, we will focus on machine learning models of programs and natural language focused on making this goal a reality. First, we will discuss the similarities and differences between programming and natural language. Then we will discuss methods that have been designed to cover a variety of tasks in this field, including automatic explanation of programs in natural language (code-to-language), automatic generation of programs from natural language specifications (language-to-code), modeling the natural language elements of source code, and analysis of communication in collaborative programming communities. The tutorial will be aimed at NLP researchers and practitioners, aiming to describe the interesting opportunities that models at the intersection of natural and programming languages provide, and also how their techniques could provide benefit to the practice of software engineering as a whole.

## Slides

Slides can be found here:

[Modelling Natural Language, Programs, and their Intersection](naacl18tutorial.pdf)

## References

* Miltiadis Allamanis, Earl T Barr, Christian Bird, and Charles Sutton. Learning natural coding conventions. In Proceedings of the International Symposium on Foundations of Software Engineering (FSE), 2014.
* Miltiadis Allamanis, Earl T Barr, Christian Bird, and Charles Sutton. Suggesting accurate method and class names. In Proceedings of the Joint Meeting of the European Software Engineering Conference and the Symposium on the Foundations of Software Engineering (ESEC/FSE), 2015.
* Miltiadis Allamanis, Earl T Barr, Premkumar Devanbu, and Charles Sutton. A survey of machine learning for big code and naturalness. arXiv preprint arXiv:1709.06182, 2017.
* Miltiadis Allamanis, Marc Brockschmidt, and Mahmoud Khademi. Learning to represent programs with graphs. In ICLR, 2018.
* Miltiadis Allamanis, Hao Peng, and Charles Sutton. A convolutional attention network for extreme summarization of source code. arXiv preprint arXiv:1602.03001, 2016.
* Miltiadis Allamanis, Daniel Tarlow, Andrew Gordon, and Yi Wei. Bimodal modelling of source code and natural language. In ICML, 2015.
* Uri Alon, Meital Zilberstein, Omer Levy, and Eran Yahav. code2vec: Learning distributed representations of code. arXiv preprint arXiv:1803.09473, 2018.
* Uri Alon, Meital Zilberstein, Omer Levy, and Eran Yahav. A general path-based representation for predicting program properties. arXiv preprint arXiv:1803.09544, 2018.
* Robert Balzer, Neil Goldman, and David Wile. Informality in program specifications. IEEE Transactions on Software Engineering, 1978.
* Anton Barua, Stephen W Thomas, and Ahmed E Hassan. What are developers talking about? an analysis of topics and trends in stack overflow. Empirical Software Engineering, 19(3):619–654, 2014.
* Rohan Bavishi, Michael Pradel, and Koushik Sen. Context2Name: A deep learning-based approach to infer natural variable names from usage contexts. 2017.
* James Clarke, Dan Goldwasser, Ming-Wei Chang, and Dan Roth. Driving semantic parsing from the world’s response. In Proc. CoNLL, pages 18–27, 2010.
* Edsger W Dijkstra. On the foolishness of “natural language programming”. In Program construction, pages 51–53. Springer, 1979.
* Li Dong and Mirella Lapata. Language to logical form with neural attention. In Proc. ACL, 2016.
* Li Dong and Mirella Lapata. Coarse-to-fine decoding for neural semantic parsing. arXiv preprint arXiv:1805.04793, 2018.
* Benjamin Floyd, Tyler Santander, and Westley Weimer. Decoding the representation of code in the brain: An fMRI study of code review and expertise. In Proceedings of the International Conference on Software Engineering (ICSE), 2017.
* Alexander L Gaunt, Marc Brockschmidt, Rishabh Singh, Nate Kushman, Pushmeet Kohli, Jonathan Taylor, and Daniel Tarlow. Terpret: A probabilistic programming language for program induction. arXiv preprint arXiv:1608.04428, 2016.
* Xiaodong Gu, Hongyu Zhang, Dongmei Zhang, and Sunghun Kim. Deep api learning. In Proceedings of the 2016 24th ACM SIGSOFT International Symposium on Foundations of Software Engineering, pages 631–642. ACM, 2016.
* Srinivasan Iyer, Ioannis Konstas, Alvin Cheung, and Luke Zettlemoyer. Summarizing source code using a neural attention model. In Proc. ACL, pages 2073–2083, 2016.
* Robin Jia and Percy Liang. Data recombination for neural semantic parsing. In Proc. ACL, pages 12–22, Berlin, Germany, August 2016. Association for Computational Linguistics.
* Siyuan Jiang, Ameer Armaly, and Collin McMillan. Automatically generating commit messages from diffs using neural machine translation. In Proceedings of the 32nd IEEE/ACM International Conference on Automated Software Engineering, pages 135–146. IEEE Press, 2017.
* David Kavaler, Sasha Sirovica, Vincent Hellendoorn, Raul Aranovich, and Vladimir Filkov. Perceived language complexity in github issue discussions and their effect on issue resolution. In Proc. ASE, pages 72–83. IEEE Press, 2017.
* Nate Kushman and Regina Barzilay. Using semantic unification to generate regular expressions from natural language. In Proc. NAACL, 2013.
* Yujia Li, Daniel Tarlow, Marc Brockschmidt, and Richard Zemel. Gated graph sequence neural networks. arXiv preprint arXiv:1511.05493, 2015.
* Bin Lin, Fiorella Zampetti, Gabriele Bavota, Massimiliano Di Penta, Michele Lanza, and Rocco Oliveto. Sentiment analysis for software engineering: How far can we go? In Proceedings of the International Conference on Software Engineering (ICSE), 2018.
* Xi Victoria Lin, Chenglong Wang, Luke Zettlemoyer, and Michael D. Ernst. NL2Bash: A corpus and semantic parser for natural language interface to the linux operating system. In Proc. LREC, 2018.
* Wang Ling, Phil Blunsom, Edward Grefenstette, Karl Moritz Hermann, Tom ́aˇs Koˇcisky ́, Fumin Wang, and Andrew Senior. Latent predictor networks for code generation. In Proc. ACL, 2016.
* Cristina V Lopes, Petr Maj, Pedro Martins, Vaibhav Saini, Di Yang, Jakub Zitny, Hitesh Sajnani, and Jan Vitek. D ́eja`vu: a map of code duplicates on github. Proceedings of the ACM on Programming Languages, 1(OOPSLA):84, 2017.
* Pablo Loyola, Edison Marrese-Taylor, and Yutaka Matsuo. A neural architecture for generating natural language descriptions from source code changes. arXiv preprint arXiv:1704.04856, 2017.
* Dana Movshovitz-Attias and William W. Cohen. Natural language models for predicting programming comments. In Proc. ACL, pages 35–40, Sofia, Bulgaria, August 2013. Association for Computational Linguistics.
* Yusuke Oda, Hiroyuki Fudaba, Graham Neubig, Hideaki Hata, Sakriani Sakti, Tomoki Toda, and Satoshi Nakamura. Learning to generate pseudo-code from source code using statistical machine translation. In Proc. ASE, pages 574–584, 2015.
* Illia Polosukhin and Alexander Skidanov. Neural program search: Solving programming tasks from description and examples. arXiv preprint arXiv:1802.04335, 2018.
* Michael Pradel and Koushik Sen. Deep learning to find bugs. 2017.
* Chris Quirk, Raymond Mooney, and Michel Galley. Language to code: Learning semantic parsers for if-this-then-that recipes. In Proc. ACL, 2015.
* Veselin Raychev, Martin Vechev, and Andreas Krause. Predicting program properties from “Big Code”. In Proceedings of the Symposium on Principles of Programming Languages (POPL), 2015.
* Andrew Rice, Edward Aftandilian, Ciera Jaspan, Emily Johnston, Michael Pradel, and Yulissa Arroyo-Paredes. Detecting argument selection defects. Proceedings of the ACM on Programming Languages, 1(OOPSLA):104, 2017.
* Kyle Richardson and Jonas Kuhn. Learning semantic correspondences in technical documentation. In Proc. ACL, pages 1612–1622, Vancouver, Canada, July 2017. Association for Computational Linguistics.
* Armando Solar-Lezama. Program synthesis by sketching. University of California, Berkeley, 2008.
* Phillip D Summers. A methodology for lisp program construction from examples. In Readings in artificial intelligence and software engineering, pages 309–316. Elsevier, 1986.
* Jason Tsay, Laura Dabbish, and James Herbsleb. Let’s talk about it: evaluating contributions through discussion in github. In Proceedings of the 22nd ACM SIGSOFT international symposium on foundations of software engineering, pages 144–154. ACM, 2014.
* Bogdan Vasilescu, Casey Casalnuovo, and Premkumar Devanbu. Recovering clear, natural identifiers from obfuscated js names. In Proceedings of the International Symposium on Foundations of Software Engineering (FSE), 2017.
* Yi Wei, Nirupama Chandrasekaran, Sumit Gulwani, and Youssef Hamadi. Building bing developer assistant. Technical report, Technical Report MSR-TR- 2015-36, Microsoft Research, 2015.
* Edmund Wong, Taiyue Liu, and Lin Tan. CloCom: Mining existing source code for automatic comment generation. In Proceedings of the International Conference on Software Analysis, Evolution, and Reengineering (SANER), pages 380–389. IEEE, 2015.
* Yuk Wah Wong and Raymond Mooney. Learning for semantic parsing with statistical machine translation. In Proc. HLT, pages 439–446, 2006.
* Ziyu Yao, Daniel S Weld, Wei-Peng Chen, and Huan Sun. Staqc: A systematically mined question-code dataset from stack overflow. In Proc. WWW, 2018.
* Pengcheng Yin, Chunting Zhou, Junxian He, and Graham Neubig. StructVAE: Tree-structured latent variable models for semi-supervised semantic parsing. In The 56th Annual Meeting of the Association for Computational Linguistics (ACL), Melbourne, Australia, July 2018.
* John M Zelle and Raymond J Mooney. Learning to parse database queries using inductive logic programming. In Proc. AAAI, pages 1050–1055, 1996.
* Victor Zhong, Caiming Xiong, and Richard Socher. Seq2sql: Generating structured queries from natural language using reinforcement learning. arXiv preprint arXiv:1709.00103, 2017.
