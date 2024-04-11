---
title: "Intersection Homology"
draft: false
showDate: false
cardView: true
showSummary: false
groupbyYear: false
sharingLinks: [""]
showTableOfContents: false
herostyle: "background" # valid options: basic, big, background, thumbAndBackground
layoutBackgroundBlur: true # only used when heroStyle equals background or thumbAndBackground
layoutBackgroundHeaderSpace: false
showHero: true
showPagination: false
---
{{< katex >}} 

<html>
<head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.7.1/katex.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.7.1/katex.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.7.1/contrib/auto-render.min.js"></script>
</head>
<body>
    <script>
      renderMathInElement(
          document.body,
          {
              delimiters: [
                  {left: "$$", right: "$$", display: true},
                  {left: "\\[", right: "\\]", display: true},
                  {left: "$", right: "$", display: false},
                  {left: "\\(", right: "\\)", display: false}
              ]
          }
      );
    </script>
</body>
</html>

<a style= "font-family: 'Bebas'; color: white; font-size: 15pt">This is a reading seminar organized by professors of Algebraic depertment. In this seminar we will learn about</a> *Intersection homology* <a style= "font-family: 'Bebas'; color: white; font-size: 15pt">and</a> *Perverse Sheaves* <a style= "font-family: 'Bebas'; color: white; font-size: 15pt">from the book of</a> *Kirwan and Wolf*.


<center>
   <a style= "font-family: 'Bebas'; font-variant: small-caps; color: white; font-size: 21pt"> Schedule</a>
</center>

{{< timeline >}}

{{< timelineItem icon="" header="1. Overview Talk" badge="12/1" subheader="Overview talk by Prof. Suresh Nayak" >}}
     Notes taken by me (Latexed) - <a href="./notes/overview.pdf"> Overview Talk </a>.
{{< /timelineItem >}}

{{< timelineItem icon="" header="2. Review Talk" badge="19/1" subheader="Prognadipto Majumdar and Eeshan Pandey" >}}
     Notes by me (Latexed)- <a href="./notes/prereq.pdf">Prerequisites</a>.<br>

     In this lecture we will cover some prerequisite needed for this seminar like, review of singular, simplicial, Borel-Moore (co)homology etc and then Sheaf theory, sheaf cohomology (both from resolution and Derived functor point of view), cech cohomology, their relations (in some case). <br>
{{< /timelineItem >}}

{{< timelineItem icon="" header="3. Pseudomanifold and Intersection Homology" badge="02/02" subheader="Soumya Dasgupta" >}}
    Notes by Soumya - <a href="./notes/IH_notes.pdf">Lecture-3</a>.<br>
     Introduction to stratified spaces, Psudomanifold, Perversity and `Intersection Homology' with examples. Heading towards resolving Poincare duality - Normalization of topological spaces.
{{< /timelineItem >}}

{{< timelineItem icon="" header="4. First Properties of I.H. and I.H for Quasi projective Varites" badge="09/02" subheader="Trishan Mondal" >}}
    Notes by me - <a href="./notes/talk5.pdf">Lecture 4</a>.<br>
      In this talk, we will discuss the homological properties of intersection homology like pushforward maps, excision and Mayer-Vietoris. We will compute the intersection homology of cones. We then discuss Whitney stratifications for complex quasi-projective varieties and the associated pseudomanifold structure on their underlying topological space. We will conclude with a discussion of Poincaré duality, Lefschetz hyperplane and hard Lefschetz theorems in the context of intersection homology.
{{< /timelineItem >}}

{{< timelineItem icon="" header="5. \(L^2\)- Cohomology and Intersection Cohomology." badge="16/02" subheader="Aaratrick Basu" >}}
    Notes by Aaratrick - <a href="./notes/lec-5.pdf">Lecture 5</a>.<br>
    We introduce \(L^2\)-cohomology of smooth manifolds with riemannian metric, which is closely related to de Rham cohomology. We will then discuss strong Hodge theorem and a conjecture of Cheeger about intersection cohomology and \(L^2\)-cohomology. In the case of complex projective varieties with simple singularities, we show that \(L^2\)-cohomology does coincide with its intersection cohomology. If time permits, we will discuss the relation between the \(L^2\)-cohomology of a locally symmetric space and the intersection cohomology of its Baily-Borel compactification.
{{< /timelineItem >}}

{{< timelineItem icon="" header="6. Sheaf theoretic Intersection homology" badge="24/02" subheader="Jishnu Biswas" >}}
    In this talk, we sheafify the construction of the intersection homology we have seen so far by showing that it can be computed as the homology group of a certain complex of sheaves. As a consequence, it is shown that intersection homology is a topological invariant of a pseudomanifold, i.e, it does not depend on the choice of a stratification. This is done using Deligne's construction which given any stratification associates to a complex of sheaves, a new complex of sheaves. This construction is then applied to the complex computing intersection homology for the canonical (coarsest) stratification to derive the independence of stratification.
{{< /timelineItem >}}

{{< timelineItem icon="" header="7. Continuation" badge="01/03" subheader="Jishnu Biswas,Trishan Mondal" >}}
In this talk we will first look into The Kähler package, then we will get back proving the fact Intersection homology sheaf is invariant of stratification.
{{< /timelineItem >}}

{{< timelineItem icon="" header="8. Perverse sheaves" badge="08/03" subheader="Animesh Renanse" >}}
 Notes by Animesh - <a href="./notes/lecture8.pdf">Lecture 5</a>.<br>
 Let X be an n-pseudomanifold. In the last two talks, we constructed the simplicial intersection complex of sheaves over X and showed that its hypercohomology is the intersection homology. Furthermore, it is completely characterized in the derived category by a list of axioms. Continuing with this, we will see that these axioms ensure that this complex is a perverse sheaf with a twist. We will see that the category of perverse sheaves enjoys special properties in the derived category; it is abelian and is closed under Verdier duality. Thinking of perverse sheaves as an enlargement of intersection homology with local coefficients, we will see that every perverse sheaf can be “approximated” by finitely many of them; that is, the category of perverse sheaves is artinian. We will end with some more remarks and examples from complex varieties.
{{< /timelineItem >}}

{{< timelineItem icon="" header="8. Nearby and Vanishing cycle" badge="15/03" subheader="Raushon toor nair" >}}
     We define nearby and vanishing cycles functors, associated with a function \(f: \mathbb{C}^n \to \mathbb{C}\), from the bounded derived category of constructible sheaves on \(\mathbb{C}^n\) to those on the special fiber of 0 of the function \(f\). We will then discuss the Beilinson-Bernstein-Deligne-Gabber decomposition theorem for intersection homology.
{{< /timelineItem >}}


{{< timelineItem icon="" header="9,10. Weil's conjecture for the singular case" badge="05/04, 12/04" subheader="Kannappan Sampath" >}}
     We will introduce Weil's zeta function of a smooth projective variety over finite fields and Weil's conjectures about them. We will then explain how one could deduce these conjectures from a reasonable cohomology theory; we will then explain that such a cohomology theory with coefficients in \(\mathbb{Q}_p\) that is functorial for morphisms between smooth projective varieties cannot exist. We will then mention that \(\ell\)-adic etale cohomology (with ell not equal to p) is a Weil-cohomology theory. We will end by computing the "naive" zeta function of some explicit examples of singular varieties.
{{< /timelineItem >}}


{{< /timeline >}}

<center>
   <a style= "font-family: 'Bebas'; font-variant: small-caps; color: white; font-size: 21pt"> References</a>
</center>

- <a style= "font-family: 'Bebas'; font-variant: small-caps; color: white; font-size: 14pt"> Main Text :</a> F. Kirwan, J. Woolf, *An introduction to intersection homology theory* [CRC Press, 2006] - [Pdf](./documents/Frances%20Kirwan,%20Jonathan%20Woolf.pdf)
- <a style= "font-family: 'Bebas'; font-variant: small-caps; color: white; font-size: 14pt"> Furthers :</a> 
  
     1. L. G. Maxim, Intersection Homology & Perverse Sheaves - [Pdf](./documents/Laurenţiu%20G.%20Maxim%20.pdf).
     2. M. Goresky, R. MacPherson, Stratified Morse theory - [Pdf](./documents/Stratified%20Morse%20Theory.pdf).
     3. A. Dimca, Sheaves in topology - [Pdf](./documents/(Universitext)%20Alexandru%20Dimca.pdf).
     4. A. Borel, Intersection cohomology - [Pdf](./documents/(Progress%20in%20Mathematics%2050)%20Armand%20Borel%20(auth.)%20.pdf).
     5. V. Pati. Notes on intersection homology - [Pdf](./documents/Intersection%20homology(pati).pdf).

<center>
   <a style= "font-family: 'Bebas'; font-variant: small-caps; color: white; font-size: 21pt">Other links</a>
</center>


- <a style= "font-family: 'Bebas'; color: white; font-size: 14pt">Web page :</a> of [Charanya Ravi](https://charanyaravi.github.io/Sem2-23-24/Sem2-23-24:IH:index.html) related to this seminar.