## Nash Equilibrium in Mixed Stratergies

#### Formal definition

In game theory, a mixed strategy is a probability distribution over a player's set of possible pure strategies. A pure strategy is a specific choice of action that a player can make, while a mixed strategy involves choosing a pure strategy randomly according to some probability distribution.

Formally, let S_i be the set of pure strategies available to player i, and let p_i(s) be the probability that player i chooses pure strategy s, where 0 ≤ p_i(s) ≤ 1 for all s ∈ S_i and Σ_s∈S_i p_i(s) = 1. Then, a mixed strategy for player i is a probability distribution over the set of pure strategies S_i, represented by the vector p_i = (p_i(s))_s∈S_i.

When each player chooses a mixed strategy, the outcome of the game is determined by a joint probability distribution over the set of pure strategies chosen by all players. The expected payoff for a player i given a mixed strategy profile (p_1, ..., p_n) is the sum of the payoffs for each possible outcome weighted by the probability of that outcome occurring.

A Nash equilibrium in a mixed strategy game is a mixed strategy profile for all players, such that no player can improve their expected payoff by unilaterally changing their strategy, given the strategies of the other players.

Mixed strategies are often used to model situations where players have incomplete information about their opponents or face uncertainty about the environment in which the game is played. They also allow for more complex and varied behavior in games, as players can randomize their strategies in a way that may be difficult to predict.

#### 2-citizen tax evasion game
The tax evasion game is a classic example of a game that can be analyzed using game theory. Consider a simple two-player game in which each player must choose whether to evade taxes or not. Each player has two possible strategies: to evade taxes (E) or to pay taxes (P).

If both players pay taxes, they each receive a payoff of R (for "reward"), which is greater than the amount they would receive if they both evaded taxes. If both players evade taxes, they each receive a payoff of T (for "temptation"), which is greater than the amount they would receive if they both paid taxes. However, if one player pays taxes and the other evades taxes, the player who evades taxes receives a higher payoff S (for "sucker") than the player who pays taxes, who receives a lower payoff P (for "punishment").

The payoffs for each outcome are represented in the following payoff matrix:

|     | Pay Taxes (P) | Evade Taxes (E) |
|-----|-------------|-------------|
|**Pay Taxes (P)**| Reward (R), Reward (R) | Sucker (S), Temptation (T) |
|**Evade Taxes (E)**| Temptation (T), Sucker (S) | Punishment (P), Punishment (P) |

In this game, the Nash equilibrium is for both players to evade taxes. This is because if one player pays taxes and the other evades taxes, the player who evades taxes receives a higher payoff than the player who pays taxes. Therefore, neither player has an incentive to change their strategy unilaterally.

However, this outcome is not socially optimal, as both players would receive a higher payoff if they both paid taxes. The challenge in this game is to find ways to encourage both players to pay taxes and avoid the temptation to evade taxes. Possible solutions could include increasing the penalties for tax evasion, improving the enforcement of tax laws, or increasing public awareness of the importance of paying taxes.

#### citizen and government tax evasion game

Here is an example of a game between a government and a citizen where the government has two possible moves: "audit" and "trust", and the citizen has two possible moves: "pay taxes" and "evade taxes":

| | Pay Taxes | Evade Taxes |
|----------|-----------|-------------|
| **Audit**     | -a, b     | c, 0 |       
| **Trust**     | -t, s     | d, e |

If the government chooses to "audit" and the citizen chooses to "pay taxes", the government incurs a cost of a, and the citizen receives a benefit of b.
If the government chooses to "audit" and the citizen chooses to "evade taxes", the government receives a benefit of c (e.g., in the form of fines or penalties), and the citizen receives no benefit.
If the government chooses to "trust" and the citizen chooses to "pay taxes", the government incurs a cost of t, and the citizen receives a benefit of s.
If the government chooses to "trust" and the citizen chooses to "evade taxes", the government receives a benefit of d (e.g., in the form of increased revenue from other sources), and the citizen incurs a cost of e (e.g., in the form of fines or penalties).
To find the Nash equilibrium, we need to look for a situation where neither player has an incentive to change their strategy unilaterally. One possible Nash equilibrium in this game is where the government chooses to "trust" and the citizen chooses to "pay taxes". In this case, the payoffs are (-t, s) for the government and (s-t) for the citizen. Neither player has an incentive to change their strategy, as any deviation would result in a lower payoff for that player.

However, there may be other Nash equilibria in this game, depending on the values of the parameters a, b, c, d, e, s, and t. Additionally, the socially optimal outcome may be for the citizen to "pay taxes" and the government to "audit", as this would maximize tax revenue and discourage tax evasion.

#### Equilibrium Outcome

|       | Pay     | Evade  |
| ----- | ------- | ------ |
| Audit | 130/256 | 30/356 |
| Trust | 78/256  | 18/256 |

$\therefore\sum(Payoffs) = 1$

<hr>

#### What if S is in infinite set (infinite moves)?

[todo]

#### What is a mixed strategy in a cournot game?

[todo]

#### Individual Randomisation

If the taxpayer knows what the government is going to do, he can calculate the best response. Thus the government can use an indiduvually, truly randomised functions such as using a roulette to decide whether to audit or trust, is important.

