# Energy Supply Allocation Framework

Our project focuses on developing a comprehensive framework for equitable and efficient distribution of energy resources among various stakeholders using game-theoretic and machine learning approaches. The framework addresses two main stages in the energy supply chain:

Suppliers to Agents (Energy Supply Allocation)
Agents to Consumers (Energy Distribution)
1. Suppliers to Agents (Energy Supply Allocation)
In the first stage, multiple suppliers provide energy to agents. The allocation of energy from suppliers to agents is governed by bargaining rules, which are optimized using machine learning models. This approach ensures that the negotiation process between suppliers and agents is fair, efficient, and adaptable to dynamic market conditions.

Key Components:
Multiple Suppliers: Various energy providers offering different amounts of energy resources.
Agents: Intermediaries who receive energy from suppliers and later distribute it to consumers.
Bargaining Rules: Rules that govern the negotiation process between suppliers and agents, ensuring a fair distribution of energy resources.
Machine Learning Models: Models that optimize bargaining rules by learning from historical data and predicting the most efficient negotiation outcomes.
Process:
Data Collection: Gather historical data on energy supply, demand, pricing, and previous bargaining outcomes.
Model Training: Train machine learning models on the collected data to learn effective bargaining strategies.
Optimization: Use the trained models to predict optimal bargaining outcomes, ensuring a fair distribution of energy from suppliers to agents.
Allocation: Allocate energy resources based on the optimized bargaining rules.
2. Agents to Consumers (Energy Distribution)
In the second stage, agents distribute energy to consumers. This allocation is modeled as a bankruptcy problem and resolved using Nash bargaining theory combined with bankruptcy rules. This approach ensures an equitable distribution of limited energy resources among consumers during periods of shortage.

Key Components:
Single Supplier (Agent): The intermediary that receives energy from multiple suppliers and distributes it to consumers.
Consumers: End-users who receive energy from the agent.
Bankruptcy Rules: Rules that address the allocation of scarce resources among consumers, ensuring fairness and equity.
Nash Bargaining Theory: A game-theoretic approach that resolves conflicts and ensures that the allocation is Pareto-optimal and equitable.
Bankruptcy Rules Applied:
Proportional Rule (PRO): Allocates resources proportionally based on claims.
Constrained Equal Award (CEA) Rule: Ensures each consumer receives an equal share of available resources, constrained by their claims.
Constrained Equal Losses (CEL) Rule: Distributes losses equally among consumers relative to their claims.
Talmud Rule: Combines CEA and CEL rules based on the total available resources.
Piniles Rule: Adjusts allocations based on the specific constraints and available resources.
Process:
Define Claims: Determine the energy demand (claims) of each consumer.
Available Resources: Assess the total available energy resources.
Apply Bankruptcy Rules: Use the defined bankruptcy rules to allocate energy resources equitably.
Nash Bargaining Optimization: Apply Nash bargaining theory to ensure the allocation is fair and efficient, considering disagreement points and bargaining weights.
Distribution: Distribute the allocated energy to consumers.
Conclusion
By integrating machine learning models with bargaining rules for supplier-to-agent allocation and combining bankruptcy theory with Nash bargaining for agent-to-consumer distribution, our framework ensures a fair, efficient, and adaptable approach to energy resource management. This methodology not only addresses the complexities of dynamic energy markets but also promotes equity and efficiency in resource distribution.

Implementation
This project is implemented in Python and hosted on GitHub. The repository includes:

Data Collection Scripts: For gathering and preprocessing historical energy supply and demand data.
Machine Learning Models: For optimizing bargaining rules between suppliers and agents.
Bankruptcy and Nash Bargaining Algorithms: For equitable distribution of energy from agents to consumers.
Simulation Scripts: To simulate and validate the energy allocation framework under various scenarios.
Documentation: Detailed instructions on how to set up, run, and extend the project.
Feel free to contribute and improve the framework by submitting issues and pull requests. Your feedback and contributions are valuable in enhancing the efficiency and fairness of energy resource distribution.
