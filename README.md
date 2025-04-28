# cs550-lab-4--first-order-logic-proofs-in-lisa-solved
**TO GET THIS SOLUTION VISIT:** [CS550 Lab 4- First Order Logic proofs in LISA Solved](https://www.ankitcodinghub.com/product/cs550-lab-4-first-order-logic-proofs-in-lisa-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118171&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS550 Lab 4- First Order Logic proofs in LISA Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Prelude: Proof Assistants

Proof assistants, also called interactive theorem provers (ITP) are tools allowing to write fully formal mathematical proofs. Typically, the system is built on a small, fixed syntax for mathematical statement and set of inference rule, for example first order logic. Everything else is then built on those small foundations. The main role of the proof assistant is then to provide tools and assistance to the user to help produce such low level proofs. The assistant typically builds level of abstraction that hide the low level formalism and expose higher level concepts. It also provides tactics, algorithms that will partially or fully solve mathematical statements of some kind while producing a low level proof.

This approach is quite different from what you’ve seen in Stainless. While it is possible to state some mathematical statements and properties in Stainless, it is aimed at formalizing programs rather than maths. But mostly, Stainless doesn’t produce explicit proofs: Programs and correctness conditions are transformed into SMT formulas (Satisfiability Modulo Theories, i.e. propositional statements over theories such as linear arithmetic, arrays, strings and more). Then the formula is given to a specialized decision procedure, a solver, who will answer if the formula is true or not. However, neither the transformation of the program into SMT formulas nor the decision procedure are witnessed by formal proofs. Note that a minority of proof assistants designed for mathematics adopt a similar procedure: Their set of deduction rules is then an algorithm that decide if a set of formulas entails another formula.

Producing proofs is generaly a burden to very advanced decision procedure, as it slows down the search. But said procedure are also very complicated tools, prone to bugs and errors. Producing proofs is a great way to ensure you will never accept a statement that is in fact not correct.

The Lab

In this Lab, you will use LISA, a proof assistant developed in the LARA. The first step for you is to read the first chapter of the user manual and to install LISA as per the instruction. Once you’ve followed all the installation, run git switch Lab04 Then start sbt with sbt and finally within sbt’s environment, project fv-lab04

If you now hit run, you’ll see 3 theorems printed in green and 6 in yellow. Those correspond to the 9 theorems you can find in the file

fv-lab04/src/main/scala/Lab04.scala

Your goal for this Lab is to is to complete the proofs of the last 6 theorems so that they are all accepted. Read carefuly the first chapter of LISA’s user manual, and the 3 proofs given as example: They contain all the tools needed to complete the proofs. Keep the last theorem, richGrandfather, for last: It is significantly more challenging.

When you’ve finished, upload your file Lab04.scala on moodle (one submission per group).
