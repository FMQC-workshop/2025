---
layout: home
---

# Invited Speakers

## [Jørgen Ellegaard Andersen](https://portal.findresearcher.sdu.dk/en/persons/jea)

<table class="no-border">
  <tbody>
    <tr>
      <td style="vertical-align:top">
<strong>Replacing Monte Carlo Simulation with Gaussian Boson Sampling</strong>

<br>

Gaussian Boson Sampling (GBS) is a special purpose quantum computing platform, which can only sample in a certain probability distribution, similarly to Boson Sampling, which was first proposed by Aronson and Arkhipov and proven to be impossible on a classical computer (unless the polynomial hierarchy collapses).

        <details>
          <summary>
            (Click for long version)
          </summary>
Hamilton and coauthors subsequently showed the same for GBS. We will offer a new practical application of GBS, namely, to estimate Gaussian Expectation Value problems, for which we have established provable exponential speedup over Monte Carlo Simulations under certain assumptions. Computing Gaussian Expectation Values has a number of industrial applications including financial, and various optimization problems, including energy production, drug design and logistics. We will address its advantage, even if our assumptions for exponential speedup do not apply.
        </details>
      </td>
      <td style="width:60px;vertical-align:top;">
        <p>
          <img src="assets/images/joergen.jpg" alt="Jørgen" height="200"/>
        </p>
      </td>
    </tr>
  </tbody>
</table>

## [Lukas Burgholzer](https://burgholzer.me/)

<table class="no-border">
  <tbody>
    <tr>
      <td style="vertical-align:top">
<strong>SAT for Quantum: From Circuit Mapping over Clifford Synthesis to Optimal State Preparation for Neutral Atom Architectures</strong>

<br>

Boolean satisfiability (SAT) solving has emerged as a powerful technique for tackling complex design problems in quantum computing. This cross-cutting talk explores SAT-based approaches spanning three fundamental challenges: optimal circuit mapping, depth-optimal Clifford synthesis, and shuttling strategies for zoned neutral atom architectures.

        <details>
          <summary>
            (Click for long version)
          </summary>
The talk will first show how symbolic encodings of the complete mapping space allow SAT solvers to generate (near-)optimal circuit layouts under architectural constraints. Then, leveraging the stabilizer formalism, it will demonstrate how Clifford synthesis can be framed as a family of SAT problems. Finally, it will address the fault-tolerant synthesis of state preparation protocols for zoned neutral atom architectures using SMT solvers. Throughout, the talk will emphasize the role of formal methods in bridging scalability with optimality, and highlight experimental results from the Munich Quantum Toolkit (MQT).
        </details>
      </td>
      <td style="width:60px;vertical-align:top;">
        <p>
          <img src="assets/images/lukas.jpg" alt="Lukas" height="200"/>
        </p>
      </td>
    </tr>
  </tbody>
</table>

## [Alfons Laarman](https://alfons.laarman.com/)

<table class="no-border">
  <tbody>
    <tr>
      <td style="vertical-align:top">
<strong>The Unreasonable Effectiveness of Automated Reasoning in Quantum Computing</strong>

<br>

In this talk, we will show that existing classical automated reasoning methods perform surprisingly well for computationally hard problems in quantum computing.

        <details>
          <summary>
            (Click for long version)
          </summary>
<div>
We first show how to reduce three key quantum circuit compilation problems to #SAT or model counting: simulation, equivalence checking and synthesis. This method supports many universal gate sets including those with rotation gates. An implementation of this method, called Quokka#, outcompetes other state-of-the-art approaches using an off-the-shelf #SAT solver that supports negative and complex weights (Ganak).
</div>

<div>
While decision diagrams offer a viable alternative, we unveil their inherent limitations stemming from an inability to represent the prevalent stabilizer states. This limitation is particularly noteworthy considering the efficient classical simulatability of circuits generating such states using the so-called stabilizer formalism. To alleviate this bottleneck, we introduce Local Invertible Map Decision Diagrams (LIMDDs), which offer exponential improvements in succinctness compared to the combination of stabilizer formalism and existing decision diagrams. Recent implementations of this method show remarkable improvements in practice.
</div>

<div>
Finally, we show how these findings compare to well-known approaches used in physics to tackle quantum-hard problems like simulation of many-body systems and finding the ground energy of such systems. For this, we use Darwiche's seminal "knowledge compilation map" approach. We provide a first knowledge compilation map for quantum information comparing various decision diagrams against tensor networks and Boltzmann machines. Our results show that existing automated reasoning methods have a strong potential for quantum computing and physics.
</div>
        </details>
      </td>
      <td style="width:60px;vertical-align:top;">
        <p>
          <img src="assets/images/alfons.jpg" alt="Alfons" height="200"/>
        </p>
      </td>
    </tr>
  </tbody>
</table>

## [John van de Wetering](https://vdwetering.name/)

<table class="no-border">
  <tbody>
    <tr>
      <td style="vertical-align:top">
<strong>Picturing Quantum Software</strong>

<br>

The ZX-calculus is a graphical language for reasoning about quantum processes. In this talk I will give an overview of how we can use ZX-diagrams and a small set of rewrite rules to prove interesting properties regarding optimisation, verification, classical simulation and quantum error correction.
      </td>
      <td style="width:60px;vertical-align:top;">
        <p>
          <img src="assets/images/john.jpg" alt="John" height="200"/>
        </p>
      </td>
    </tr>
  </tbody>
</table>
