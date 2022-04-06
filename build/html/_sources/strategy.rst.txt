strategy package
================

Strategy handling: 
----------

We used Counterfactual Regret Minimization(CFR) for deciding which action we would like to use. The CFR has ability to explore every possible result of the action we made and reach Nash equilibrium. Since there does not exist any strategy that can guarantee we could win every single game, using the strategy that can reach Nash equilibrium becomes a good option. The advantage of using the Nash equilibrium strategies is that our exploitability is minimum. Therefore, our agent will not totally malfunction even though the opponent knows our strategy or we gave sufficient exploitative power. Since kuhn poker is a simple poker game, the whole result can be easily calculated by algorithm. We just directly used the result from CFR and used the random seed, which is an uniform distribution, to decide which action we want to take. For the PokerBot, we will engage two types of games, 3 cards and 4 cards, we used CFR sample code from the internet and modified it to generate 3 cards and 4 cards result. The reference website as following url: https://justinsermeno.com/posts/cfr/ 

Submodules
----------

strategy.agent\_strategy module
-------------------------------

.. automodule:: strategy.agent_strategy
   :members:
   :undoc-members:
   :show-inheritance:

strategy.base\_strategy module
------------------------------

.. automodule:: strategy.base_strategy
   :members:
   :undoc-members:
   :show-inheritance:

Module contents
---------------

.. automodule:: strategy
   :members:
   :undoc-members:
   :show-inheritance:
