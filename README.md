# Vision

The goal of this open-source number theory textbook is to gather up all the core subfields of number theory into one text. By making it open-source, everyone will be able to contribute in terms of adding new material and improving existing material, and tailor it to their own learning or teaching.

It is an era of mass collaboration, in mathematics and many other fields. I aim to follow the example of other successful online textbooks such as CRing and the Stacks Project. Because we all are good at different subfields, we will be able to achieve much more if each person writes notes on an area they have studied well. For instance, I have found that one of the best ways to learn a semi-advanced topic is to find an undergraduate thesis on it: because the author has spent a long time thinking on the subject, had long conversations with advisors, and taken time to lay out the big motivations and deeper connections.

The philosophy behind this textbook is the following. If you'd like to contribute to this work I'd recommend following these guidelines (but any contribution is welcome).

+ Take a problem-oriented approach. In other words, **give motivation** behind abstract theory by relating them to interesting, concrete problems. 
+ Create a **user-friendly learning resource**: Start each chapter by telling the reader why the material matters, what problems in number theory it solves, and how it fits into the big picture. For instance, class field theory gives a way to understand field extensions through information intrinsic to the field, it gives framework for reciprocity laws (among many other things, see chapter~\ref{ch:cft-app}), and it is part of the larger Langlands program. Give a summary of the takeaway ideas after the chapter, and exercises that help the reader conceptually grasp the material. Always motivate proofs, especially long hard ones, and tell the reader why the big theorems matter. Make connections between different ways of approaching a particular problems. Highlight recurring techniques. For more, see my post on [what makes a math book good](http://holdenlee.github.io/Math%20books.html).[^f1]
	+ These points have not all been implemented in the chapters here, but it is what I'm shooting for. Currently the chapter which I think best implements this approach is the chapter on "Special values of L-functions" (in the main number theory book). See [this blog post](https://holdenlee.wordpress.com/2014/06/27/acnf/) for a discussion of the writing.
+ Be a \textbf{self-contained} work: This means that proofs should refer to theorems in the text itself, possibly from a previous part (for instance, refer to the Algebraic Number Theory section in the Class Field Theory section.) For necessary background from other fields, include a summary as a chapter or appendix. For example, this is done with complex analysis background for analytic number theory.
+ Connect up elementary with advanced number theory, and offer a road map of the subject.

[^f1]: See also [Writing curriculum](http://holdenlee.github.io/Writing%20curriculum.html) and [Proofs as obstacle avoidance](http://holdenlee.github.io/Proofs%20and%20stories%20as%20obstacle%20avoidance.html).

# Contributing

+ All material is under a creative commons license.
+ Please contribute! You will be credited. It doesn't have to be finished/polished stuff---it takes much less time to edit material that's already written than to write it myself.
+ If you find mistakes, add missing sections, edit the material, etc., then send me a pull request on github. 
+ Alternatively, you email me corrections, suggestions, and contributions at holdenlee@alum.mit.edu and I'll update the document. 
+ In either case, I'll list you as a contributor.

# Files

There are two versions of the files. The "-draft" file will contain labels and comments, for ease in editing. The file without "-draft" is the published version.

+ number-theory.tex: contains the notes for algebraic number theory and analytic number theory.
	+ number-theory-draft.tex: contains most notes together. A lot of sections are incomplete.
+ ant.tex: Algebraic number theory. Mostly complete.
+ analytic-nt.tex: Analytic number theory. Mostly complete.
+ elliptic.tex: Elliptic curves. Incomplete.
+ cnt.tex: Combinatorial number theory. Just one chapter now.

# Shortlinks

Shortlinks to the pdfs:

+ Algebraic number theory: [tiny.cc/algnt](http://tiny.cc/algnt)
+ Analytic number theory: [tiny.cc/annt](http://tiny.cc/annt)
+ Number theory: [tiny.cc/ntbook](http://tiny.cc/ntbook)

# Contributors

+ Teo Andrica
+ Dan Elbert
+ Timo Keller
+ Holden Lee
+ Delong Meng
+ Oleg Muskarov
