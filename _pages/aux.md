---
---



<!-- <div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
#{% endfor %}

</div>
-->




---
---

@string{aps = {American Physical Society,}}

@inproceedings{dali/CassanoFAC20,
  abbr      = {DaLi 2020},
  author    = {Cassano, V. and
               Fervari, R. and
               Areces, C. and
               Castro, P.},
  noeditor    = {Fontaine, P.},
  title     = {Default Modal Systems as Algebraic Updates},
  booktitle = {3rd Workshop on Dynamic Logic: New Trends and Applications},
  noseries    = {LNCS},
  novolume    = {11716},
  nopages     = {161--177},
  publisher = {Springer},
  year      = {2020},
  html       = {http://www.cs.cas.cz/dali2020/},
  abstract  = {Default Logic refers to a family of formalisms designed to carry out non-monotonic reasoning over a monotonic logic (in general, Classical First-Order or Propositional Logic). Traditionally, default logics have been defined and dealt with via syntactic consequence relations. Here, we introduce a family of default logics defined over modal logics. First, we present these default logics syntactically. Then, we elaborate on an algebraic counterpart. We do the latter by extending the notion of a modal algebra to acommodate for the main elements of default logics: defaults and extensions. Our algebraic treatment of default logics concludes with an algebraic completeness result. To our knowledge, our approach is novel, and it lays the groundwork for studying default logics from a dynamic logic perspective.},
  pdf       = {dali2020.pdf}
}

@inproceedings{deon/CastroCFA20,
  abbr      = {DEON 20/21},
  author    = {Castro, P. and
               Cassano, V. and
               Fervari, R. and
               Areces, C.},
  editor    = {Fontaine, P.},
  title     = {Deontic Action Logics via Algebra},
  booktitle = {15th International Conference on Deontic Logic and Normative Systems},
  noseries    = {LNCS},
  novolume    = {11716},
  nopages     = {161--177},
  publisher = {College Publications},
  year      = {2020},
  html       = {https://collegepublications.co.uk/DEON/Castro&%20Cassano%20&%20Fervari%20&%20Areces_DEON2020.pdf},
  abstract  = {Deontic logics are dubbed the logics of normative or prescriptive reasoning.	These logics can roughly be categorized into {ought-to-be}, dealing with the prescription of state of affairs, or {ought-to-do}, dealing with the prescription of actions. An important family of {ought-to-do} deontic logics have their origin in Segerberg's {Deontic Action Logic} (DAL). In this work, we provide an algebraic characterization of DAL and some known variants.	In brief, we capture actions and formulas as elements of different base algebras, and deontic operators as algebraic operations; different algebras capture the different variants. This algebraization enables us to obtain completeness results via standard algebraic means.	Moreover, we argue that this algebraic framework offers a natural way of (re-)thinking many deontic logical issues at large.},
  pdf       = {deon2020.pdf}
}

@inproceedings{cade/CassanoFHAC19,
  abbr      = {CADE 2019},
  author    = {Cassano, V. and
               Fervari, R. and
               Hoffmann, G. and
               Areces, C. and
               Castro, P.},
  editor    = {Fontaine, P.},
  title     = {A Tableaux Calculus for Default Intuitionistic Logic},
  booktitle = {27th International Conference on Automated Deduction},
  series    = {LNCS},
  volume    = {11716},
  pages     = {161--177},
  publisher = {Springer},
  year      = {2019},
  html       = {https://doi.org/10.1007/978-3-030-29436-6\_10},
  doi       = {10.1007/978-3-030-29436-6\_10},
  abstract  = {We build a Default Logic variant on Intuitionistic Propositional Logic and develop a sound, complete, and terminating, tableaux calculus for it. We also present an implementation of the calculus. We motivate and illustrate the technical elements of our work with examples.},
  pdf       = {cade2019.pdf}
}

@inproceedings{jelia/CassanoFAC19,
  abbr      = {JELIA 2019},
  author    = {Cassano, V. and
               Fervari, R. and
               Areces, C. and
               Castro, P.},
  editor    = {Calimeri, F. and
               Leone, N. and
               Manna, M.},
  title     = {Interpolation and Beth Definability in Default Logics},
  booktitle = {16th European Conference on Logics in Artificial Intelligence},
  series    = {LNCS},
  volume    = {11468},
  pages     = {675--691},
  publisher = {Springer},
  year      = {2019},
  html      = {https://doi.org/10.1007/978-3-030-19570-0\_44},
  doi       = {10.1007/978-3-030-19570-0\_44},
  abstract  = {We investigate interpolation and Beth definability in default logics. To this end, we start by defining a general framework which is sufficiently abstract to encompass most of the usual definitions of a default Logic. In this framework a default logic DL is built on a base, monotonic, logic L. We then investigate the question of when interpolation and Beth definability results transfer from L to DL. This investigation needs suitable notions of interpolation and Beth definability for default logics. We show both positive and negative general results: depending on how DL is defined and of the kind of interpolation/Beth definability involved, the property might or might not transfer from L to DL.},
  pdf       = {jelia2019.pdf}
}

@inproceedings{tark/CastroCFA19,
  abbr      = {TARK 2019},
  author    = {Castro, P. and
               Cassano, V. and
               Fervari, R. and
               Areces, C.},
  editor    = {Moss, L.},
  title     = {An Algebraic Approach for Action Based Default Reasoning},
  booktitle = {17th Conference on Theoretical Aspects of Rationality and Knowledge},
  series    = {{EPTCS}},
  volume    = {297},
  pages     = {91--105},
  year      = {2019},
  html      = {https://doi.org/10.4204/EPTCS.297.7},
  doi       = {10.4204/EPTCS.297.7},
  abstract  = {Often, we assume that an action is permitted simply because it is not explicitly forbidden; or, similarly, that an action is forbidden simply because it is not explicitly permitted. This kind of assumptions appear, e.g., in autonomous computing systems where decisions must be taken in the presence of an incomplete set of norms regulating a particular scenario.
	Combining default and deontic reasoning over actions allows us to formally reason about such assumptions. With this in mind, we propose a logical formalism for default reasoning over a deontic action logic.	The novelty of our approach is twofold.	First, our formalism for default reasoning deals with actions and action operators, and it is based on a deontic action logic originally proposed by Segerberg.	Second, inspired by Segerberg's approach, we use tools coming from the theory of Boolean Algebra.	These tools allow us to extend Segerberg's algebraic completeness result to the setting of Default Logics.},
  pdf       = {tark2019.pdf}
}

@inproceedings{lpar/CassanoAC18,
  abbr      = {LPAR-22},
  author    = {Cassano, V. and
               Areces, C. and
               Castro, P.},
  editor    = {Barthe, G. and
               Sutcliffe, G. and
               Veanes, M.},
  title     = {Reasoning About Prescription and Description Using Prioritized Default Rules},
  booktitle = {22nd International Conference on Logic for Programming, Artificial Intelligence and Reasoning},
  series    = {EPiC Series in Computing},
  volume    = {57},
  pages     = {196--213},
  publisher = {EasyChair},
  year      = {2018},
  html      = {https://easychair.org/publications/paper/Zn7P},
  abstract  = {In this paper we introduce a prioritized default logic. We build this logic modularly from Standard Deontic Logic by the addition of default rules and priorities among them. Our main aim is to provide a logical framework to reason about  scenarios where prescriptive and descriptive statements coexist and may be incomplete and contradictory.	We motivate and illustrate the technical elements of our work with the use of examples (classical, and coming from software engineering).	In addition, we present sound, complete, and terminating (with loop check) tableau-based proof calculi for credulous and sceptical reasoning in our logic.},
  pdf       = {lpar2018.pdf}
}
