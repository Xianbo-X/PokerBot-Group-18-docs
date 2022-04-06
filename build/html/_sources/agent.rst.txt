agent module
============

For agent class, we treat image classifiers and action generators as two components of the agent. So, two member variables `self.model` and `self.strategy` are introduced to provide services for the agent.
By designing like this, our agent class will focus on how to pass information from image classifiers to the strategy generator. And the agent is responsible for passing information between internal components image classifiers, strategy generator and external controller.
Also, we can easily use new image classifiers and new strategy generators to replace current components without having to consider the implementation of the agent. We just make sure the two components follow interface specifications and change the loaded `self.model`` and `self.strategy`. 
Then our agent can run normally without any further changes in the agent class. 

.. automodule:: agent
   :members:
   :undoc-members:
   :show-inheritance:
