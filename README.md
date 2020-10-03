# UnitaryEvolution

These are files concerning the semester project persued with Dr Sreejith GJ at IISER Pune, in the Covid affected semester of Jan2020. The project mainly dealt with tensor networks. We were interested in a particular decomposition of SU(N^2) in particular that of SU(9) which allows us to talk about the unitaries modulo the leg degrees of freedom. This leads us to some special duality conditions (can be realised as submanifolds of the space) which allows us to write analytical correlation function for some special non-integarble systems.    
For N=2, which describes the case of Qubits, this is well understood. Essentially the problem is to find a paremtrization for the Quotient Space SU(N^2)/SU(N)XSU(N). For the qubit case this can be realised as a group decomposition, which is related to the Cartan Decomposition of SU(4) over SO(4) and can be shown using Lie-algebra isomorphism of so(4) and su(2)xsu(2).
This structre does not generalise for higher N primarily due to two reasons:
  a. so(N^2) is in general not conjugate to so(N)xso(N)
  b. SU(N^2) is in general not Cartan Decomposable over SU(N)xSU(N)

We approach the problem with the following construction. First we look at the subspace of SU(9)/SU(3)XSU(3), where an Cartan Decomposition structure is possible.
  Let, SU(3)XSU(3) be K (a compact subgroup of SU(9)). Lower case alphabets (k, su(9) respectively) deonote the corresponding algebras. We denote the set of generators that generate the normal subspace of K in SU(9) by p. This is essentially the quotient space generators. Now we look at the commuting subspaces of the quotient space (call the corresponding set of generaotors a). The maximal such subalgebra is called the Cartan Subalgebra.

We look at the structres G=K.Exp{a}.K. G is automatically a subgroup of SU(9), that has the desired structres. We try to find all such possible a, upto conjugation. That gives us the knowledge of all the subgroups, where we can go on looking for Duality Conditions. Geometrically speaking, these forms tori in the SU(9) manifold, and the Cartan Subalgebra generates the maximal tori. For SU(9) the maximal tori is 8 dimensional as vector space. At this point we know existence of two disctinct 6 dimensional tori, having 2 dimensional and 1 dimensional dual subspace respectively. (File 2.1)

There are two directions of possible way ahead.
  a. To look for interesting physical nonintegrable hamiltonians and try to study various phenomena that the analytical correlation functions allows us to look at.
  b. To find a set of non-conjugate tori that spans the whole quotient space. We would like nice properties like this set to be orthogonal (but not exclusive) and minimal. The quotient space for SU(9) is 48 dimensional. Such a thing cant be a subgroup, as clearly the total set of generators are not closed under commutation, and niether they are all commuting like qubit case. If we find components made up of mutually exclusive sets of toris, we would need to also find transition unitaries (unlikely). Even though that is not neccesairly a group decomposition, it will be a self-consistent description of the quotient manifold robust enough to deal with the duality conditions.
  c. If b is not true, then we would instead like to look at the maximal submanifold that has the structre of b, and then would like to determine the neccesary and sufficient conditions for exiestence of such submanifolds. 
  In either case (b/c) we would finally like to determine how the structre/conditions generalise for higher N.
  
  Here I would gather the major calculations, and keep updating them as time flows. The plan is to add latex files with sufficient background and mathematical details (proofs, theorems etc.)  
  
  
  ## Files
  
  1. **File 2:** Various unorganised raw results regarding the group structre and Cartan-Decomposition of SU(9). Some are important. I will organise these results later.
  2. **File 2.1: Commuting Subspaces of P.** Contains detailed caculation about duality conditions of the two subspaces. Has the proof of the subgroup structre of KAK.   
  3. **File 3: 3 level Potts Model**.
      Mathematica file concerning the 3 level Potts model. The basis change from (\sigma,\tau) to Gell-Mann Matrices has been obtained for relevant unitaries. Yet to obtain the swap matrices, that allows us to bring one class of unitaries from the L to R of another class.

   
