---
title: MIT 14.01 Principles of Microeconomics
author: Adair Antonio da Silva Neto
date: \today
---

# 1. What is Microeconomics?

Is the study of how agents and firms take decisions in a world of scarcity.

Microeconomic problems are problems of constrained optimization.

Every choice has its tradeoffs, its opportunity cost.

Levels of understanding: intuitively, graphically, and mathematically.

## How to capture economic relations? The supply and demand model.

Which models can be used to understand Microeconomics?

Models never describe the phenomena perfectly, but they capture them as simply as possible.

Supply and demand: the demand curve has a downwards slope because when the price is bigger, fewer people consume. The supply curve is the inverse.

The point in which supply and demand intersection is called *market equilibrium*.

Market failures:
: When the market doesn't work as it should E.g. frauds, imperfect information, behavioral questions.

Consumers and firms serve their own best interests of what is best for society.

Demand:
: How does a consumer decide what they want? How to maximize utility given consumer preferences and budget constraints?

Supply:
: How does a firm decide what they want to produce? Which inputs to take and which outputs to produce?

# 2. How do we model people's tastes? Preferences and utility functions.

## Reasonable assumptions about preferences:

1. Completeness: you have preferences over any set of goods.
2. Transitivity.
3. Non-satiation: more is better.

## How to graphically represent preferences? Indifference curves.

They are preference maps.

All combinations of consumption among you are indifferent.

Properties:

1. Consumers prefer higher indifference curves because more is better.
2. Indifference curves are downward sloping, also because of non-satiation.
3. Indifference curves never cross, because of transitivity.
4. Only one possible indifference curve through every bundle, because of completeness.

## How to mathematically represent our preferences/tastes? Utility functions.

What is utility? Doesn't actually mean anything.

It's not a cardinal concept. But it's purely ordinal: they can be ranked.

Marginal utility:
: How to think about the next unit? It's the derivative of the utility function with respect to one of the elements. Always positive.
$$ \text{mu } = \frac{\partial u(x)}{\partial x_i} $$

Diminishing marginal utility:
: The more of it that you have, the less happy you are with the next unit.

It's easier to ask "do you want the next cookie?" than "how many cookies do you want?".

Marginal Rate of Substitution (MRS):
: The rate at which we agree to change a good one for another. It's the slope of the indifference curve.
$$ \text{MRS } = \frac{\Delta x_1}{\Delta x_2} = - \frac{\text{mu}_1}{\text{mu}_2} $$

Because of diminishing marginal utility, *indifference curves are not concave to the origin*.

# 3. How are budgets and choices constrained?

## How to construct Budget Constraints?

Assumption: budget = income.

Let $w$ be the income, $p$ the vector of prices, and $x$ the quantity, i.e., the vector of how many of each item you bought.
$$ p \cdot x = w $$

Marginal Rate of Transformation (MRT):
: The slope of the budget constraint.
$$ \frac{-p_1}{p_2} $$

Opportunity cost is the value of the next best alternative.

### Shocking the constraints.

Comparative statics:
: Making a change in one term or another and seeing what it does to the system.

Opportunity set:
: Set of choices available to you given your income and market prices.

## How do consumers make constrained choices?

What is the highest indifference curve you can reach given your budget? 

*Optimal*: tangency between your indifference curve and your budget constraint.

At the optimal, the rate of substitution is equal to the rate of transformation:
$$ \text{MRS } = \text{MRT} $$

I.e. the marginal benefits are equal to the marginal costs.

This can also be written as
$$\frac{\text{mu}_1}{p_1} = \frac{\text{mu}_2}{p_2}$$

This means that the happiness per dollar spent on the first item is the same as the happiness per dollar spent on the second one.

Example: if $\text{MRS } = \text{mu}_c / \text{mu}_p = 2.5$, that means that you are willing to trade $2.5$ slices of pizza ($p$) for one cookie ($c$).

Food stamps: people are happier receiving cash than food stamps. Should we be paternalistic and say that food consumption is more important than perceived satisfaction in this case?

# 4. Demand Curves and Income/Substitution Effects

## How to derive demand curves?

What do we need? 

1. The budget $w$;

2. The prices $p_1, p_2, \ldots, p_n$;

3. The utility function $u(\cdot)$.

Remember that the slope of the budget constraint is
$$ \frac{-p_1}{p_2} $$

Optimize (maximize) the utility function subject to the constraint $p \cdot x = w$.

## What determines the shape of the demand curve?  The elasticity of Demand.

The (price) elasticity of demand:
: Percentage change in quantity ($x$) over a percentage change in price.
$$ \varepsilon = \frac{\Delta x/x}{\Delta p/p} \leq 0 $$

*Perfectly inelastic demand*: $\varepsilon = 0$. Graphically, it's a vertical line. Quantity doesn't change with price. E.g. insulin.

*Perfect elastic demand*: $\varepsilon = - \infty$. Graphically, it's a horizontal line. Price never changes. E.g. perfect substitution.

What determines elasticity is substitutability. The most substitutable the goods are, the most elastic demanded they are.

## What happens when income shifts?

The income elasticity of demand:
: Percentage change in quantity ($x$) over a percentage change in income.
$$ \gamma = \frac{\Delta x/x}{\Delta w/w} $$

Engel Curve:
: The relationship between income and quantity demanded. It's the path of income expansion. And its slope is the income elasticity of demand.

*Normal goods*: $\gamma > 0$. Luxury if $\gamma > 1$; Necessities if $\gamma < 1$.

*Inferior good*: $\gamma < 0$.

## What are the effects of a price change?

Decompose the response to the price change into two effects:

Substitution effect:
: The change in the quantity of a good when the prices change holding utility constant (same indifference curve). 
$$
\frac{\partial x(p,w)}{\partial p}\Bigr|_{\bar{u}} < 0
$$

Compensated demand:
: Holding utility constant. When prices go up, you choose to reduce the consumption of a good.

Why is the substitution effect always negative?

1. Write the new tangency.

2. $\frac{\text{mu}_1}{\text{mu}_2} = \frac{p_1}{p_2}$

3. Since $\frac{p_1}{p_2}$ goes up,

4. $\frac{\text{mu}_1}{\text{mu}_2}$ also goes up.

5. Less of the item one and more of the item two.

Income effect:
: The change in the quantity of a good as income changes holding price constant.
$$
\frac{\partial x(p,w)}{\partial w}\Bigr|_{\bar{p}} \cdot w
$$

If the good is inferior, then substitution and income effects work against each other.

| Type of Good | Price change | Substitution Effect | Income Effect | Total    |
|:------------:|:------------:|:-------------------:|:-------------:|:--------:|
| Normal       | Up           | $\leq 0$            | $\leq 0$      | $\leq 0$ |
| Normal       | Down         | $\geq 0$            | $\geq 0$      | $\geq 0$ |
| Inferior     | Up           | $\leq 0$            | $\geq 0$      | ?        |
| Inferior     | Down         | $\geq 0$            | $\leq 0$      | ?        |

Giffen good:
: Upwards sloping demand curve. E.g. rice in poor families in China.

# 5. Production Theory

## Production Function

Their goal is not to maximize production, but profit, which is revenues minus costs.

Minimizing cost: producing as efficiently as possible.

Production Function:
: Is a function $q$ which depends on $L$, labor input, and $k$, capital input.
$$ q = f(L, k) $$

Capital is all the stuff that workers use to produce goods, like machines and buildings.

The inputs can be variable or fixed.

*Short vs. long run*: In the short run, labor is variable and capital is fixed. In the long run, everything is variable.

Intuitively, the short run is a matter of days or months and the long run is a matter of decades.

Technically, the long run is a period of time on which all inputs are variable.

## Production in Short Run

Here, $q = f(L, \bar{k})$.

Marginal Product of Labor (MPL):
: The change in output for the next unit of labor input.
$$ \text{MPL} = \frac{\Delta q}{\Delta L} $$

Marginal Product of Capital (MPK):
: The change in output for the next unit of capital input.
$$ \text{MPL} = \frac{\Delta q}{\Delta k} $$

Assume diminishing marginal product. The next worker, usually, adds less to the production than the last one. The reason behind that is that capital is fixed, like the size of the building.

Here the question is "How many works to hire?"

## Production in the Long Run

Tradeoff: workers vs. machines.

*Isoquants*: The combination of capital and labor that produce the same level of output.

*Perfectly substitutable inputs*, like $q = x+y$, produce linear isoquants.

*Perfectly nonsubstitutable inputs*, like $q = \min(x,y)$ (Leontieff production function). E.g. left and right side shoes.

What is the slope of the isoquant?

Marginal Rate of Technical Substitution (MRTS):
: The slope of the isoquant.
$$ \text{MRTS} = \frac{\Delta k}{\Delta L} $$

What combination of capital and labor yields the same output? 
$$ \Delta L \cdot \text{MPL} + \Delta k \cdot \text{MPK} = 0 $$
The next unit of labor times how productive that labor is plus the next unit of capital times how productive that capital is equal to zero because you stay in an isoquant.

Reorganizing,
$$ \frac{\Delta k}{\Delta L} = - \frac{\text{MPL}}{\text{MPK}} = \text{MRTS} $$ 

## Returns to Scale

What happens to production when you increase/decrease all inputs proportionally? 

Constant Return to Scale Function (CRS):
: If you double inputs, you double the output (homogeneity of degree one).
$$ f(\alpha L, \alpha k) = \alpha f(L, k) $$

Increasing Return to Scale Function (IRS):
: If you double inputs, you more than double the output.
$$ f(\alpha L, \alpha k) > \alpha f(L, k) $$

E.g. If a firm gets bigger, it learns to specialize. 

Decreasing Return to Scale Function (DRS):
: If you double inputs, you less than double the output.
$$ f(\alpha L, \alpha k) < \alpha f(L, k) $$

E.g. Difficulty of coordination.

## Productivity

Thomas Malthus: food production has two inputs, labor, and land. Since land is fixed even in the long run, we have an ever diminishing marginal product of farming, where the marginal product of labor will decrease. Hence, he predicted cycles of mass starvation.

What did he miss? Productivity/Innovation.

This motivates us to add a production factor $A$ to our production function:
$$ q = Af(L,k) $$

Amartya Sen studied famines and concluded that they're not a technological problem. Since no democratic nation had a famine, it's about politics and distribution.

*Standard of living* is determined by productivity. This is done by enhancing capital (by how much we save) but mostly by how innovative we are.

Total Factor Productivity (TFP):
: How does production goes up given the amount of capital and labor?

The standard of living gets better when working the same amount, the income rises.

How to spend productivity gains? Leisure (like Europe) or consumption (like the US)? 

Productivity gains can also be distributed differently. 

# 6. Costs

How do costs vary with the level of output? 

How to develop a cost curve?

## Short Run Cost

Fixed costs (FC): from capital $\bar{k}$.

Variable costs (VC): labor.

Total costs (TC): FC + VC.

How to turn the production function into a cost function?

Cost Function:
: Let $r$ be the *rental rate* and $w$ the *wage rate*. They are the period cost of using a machine or a worker.
$$ C = \bar{k}r+Lw $$

The short-run cost function can be deduced from $q$ by isolating $L$.

E.g. for $q = \sqrt{L\bar{k}}$, we have $L = q^2/\bar{k}$. If $r = \$ 10$ and $w = \$ 5$, then $C = 10\bar{k} + \frac{5q^2}{\bar{k}}$. If $\bar{k} = 1$, then the short-run cost function is $C = 10 + 5q^2$.

Marginal Cost:
: The derivative of cost with respect to quantity.
$$ \text{MC} = \frac{\Delta C}{\Delta q} $$

Average Cost:
: Is over the entire range of the production.
$$ \text{AC} = \frac{C}{q} $$

Average cost meets marginal cost at the minimum of average cost.

Notice that we can write the Marginal Cost as:
$$ \text{MC} = w \frac{\Delta L}{\Delta q} = \frac{w}{\text{MPL}} $$

That means that the marginal cost of the next unit will be higher the wage and lower the more productive the worker.

## Long Run Cost

How to choose the mix of labor and capital to optimize costs?

*Isocost curves*: firm's budget constraint. It's slope is given by
$$ \frac{\Delta q}{\Delta L} = - \frac{w}{r} $$

How to figure out the right amount of labor and capital? The tangency of isoquant and isocost curves. It's the cost-minimizing point.

The tangency condition is where the MRTS equals the slope of the isocost.
$$ -\frac{\text{MPL}}{\text{MPK}} = - \frac{w}{r} $$

Rewriting, $$ \frac{\text{MPL}}{w} = \frac{\text{MPK}}{r} $$

This means that the next dollar on wages is equal to the next dollar on machines.

Long-run cost function: rewrite $q$ using the optimum mix of $L$ and $k$, obtaining $L$ and $q$. Then, replace them in $C$.

E.g. (Continuation):

1. Optimization: Since $\text{MPL} = \frac{\mathrm{d}q}{\mathrm{d}L} = \frac{0.5k}{\sqrt{kL}}$ and $\text{MPK} = \frac{\mathrm{d}q}{\mathrm{d}k} = \frac{0.5L}{\sqrt{kL}}$, simplifying and equating to the slope of the isocost gives $-\frac{k}{L} = -\frac{w}{r} = - \frac{1}{2}$. Therefore, $k = \frac{1}{2}L$.

2. Finding the long-run cost function: Using the $k$ obtained gives $q = \sqrt{\frac{1}{2}L^2}$, i.e., $L = \sqrt{2}q$. Then $L = \sqrt{2}q$ and $k = \frac{\sqrt{2}}{2}q$. Hence, $C = r \frac{\sqrt{2}}{2}q + w \sqrt{2} q = 10 \sqrt{2} q$.

What happens when the prices of labor and capital change?

E.g. (minimum wage): if the price of labor increases, the optimum changes to fewer workers and more machines.

Long-rung Expansion Path:
: How does cost change as the quantity changes?

## Relationship Between Short and Long Costs

Long-run costs are everywhere lower than short-run costs.

Having an extra degree of freedom makes it easier to optimize.

## Fixed vs. Sunk Costs

Sunk Cost:
: Investment that once made, cannot be recovered.

# 7. Competition 1

We considered the cost side of the firms, now we'll consider the revenue side.

The market is going to determine what the firm can make from selling that good.

Extremes: Perfect Competition and Monopoly. 

## Perfect Competition

What is it?

Definition.
: Where producers are price takers. The firm can't affect the market price.
: I.e., when the demand for a firm's output is perfectly elastic.

Conditions:

1. Identical products (at least perceived as).

2. Full information about prices.

3. Low transactional costs.

### Firm vs. Market Demand

Demand Function of the Market:
: $Q(p)$ downwards sloping function of the price.

Residual Demand:
: Is the function $S^0(p)$ such that:
: $$ q(p) = Q(p) - S^0(p) $$

Notice that
$$ \frac{\mathrm{d}q}{\mathrm{d}p} = \frac{\mathrm{d}Q}{\mathrm{d}p} - \frac{\mathrm{d}S^0}{\mathrm{d}p} $$

Hence $\frac{\mathrm{d}q}{\mathrm{d}p}$ is bigger, in absolute value, than $\frac{\mathrm{d}Q}{\mathrm{d}p}$ because the latter is negative and $\frac{\mathrm{d}S^0}{\mathrm{d}p}$ is positive.

Assuming $N$ identical firms, $q = Q/N$. Hence
$$ S^0 = (N-1) q $$

Then we can write
$$ \varepsilon_i = N \varepsilon - (N-1)\eta $$

where $\varepsilon$ is the market demand elasticity (negative), $\varepsilon_i$ is the firm demand elasticity, and $\eta$ is market supply elasticity (positive). Therefore, $\varepsilon_i$ is a negative number.

### Short-Run Profit Maximization

Assume in the short-run that no firm entry/exit.

What is profit?

Definition.
: **Profit** is revenue minus costs.
: $$ \pi = r - c $$

How to maximize profits?
$$ \frac{\mathrm{d}\pi}{\mathrm{d}q} = \frac{\mathrm{d} R}{\mathrm{d}q} - \frac{\mathrm{d} C}{\mathrm{d} q} = \text{MR} - \text{MC} = 0$$

Where MR is the **maximum revenue**, which is the price.

Therefore, **profits are maximum when prices equal marginal cost.**
$$ P = \text{MC} $$

Profit per unit:
: Is equal to price minus average cost:
: $$ \frac{\pi}{q} = \frac{R}{q} - \frac{C}{q} = \text{P} - \text{AC} $$

# 8. Competition II

## Shut Down Decision

In the short run, you can choose to produce zero.

Shut down if revenues are less than variable costs. I.e., if the price is less than the average variable cost.

## Short-Run Equilibrium

1. Each firm has a fixed amount of capital and a production function $q = f(\bar{k},L)$, with some inputs $w$ and $r$. This produces a cost function $C$.

2. Optimal production level: $\text{MC} = P$ which yields the supply function.

3. Market supply curve $Q$.

4. Demand equals supply to derive the price.

5. Given this price, we derive the quantity $q$.

Requisites: demand curve, cost function, number of firms in the market.

## Long-Run Competition

If the profits $\pi$ are positive, firms will enter the market. If $\pi < 0$, firms will exit. This will run until $\pi = 0$.

Why firms don't want the whole market? Because of the marginal costs.

Competition forces cost minimization because 1. competition forces each firm to produce where price equals marginal cost and 2. forces entry and exit until marginal cost equals average cost.

## Which assumptions did we make?

### Limited Entry

Sunk costs create barriers to entry.

In the short run, you enter if profits are greater than zero.

In the long run, you enter if profits are greater than the barriers to entry.

Profits only go down until barriers to entry.

### Firms may differ

Different firms have different cost functions.

Long-run profits can come from heterogeneous costs.

### Input prices may not be fixed

Inputs may have an upward sloping supply.

E.g. to produce more, you need to pay more to workers. A higher wage means a higher marginal cost.

# 9. Supply and Demand & Consumer/Producer Surplus

## Shocking Supply and Demand

Demand curve: willingness to pay.

A shift in the demand curve makes the firms move along (forwards) the supply curve.

A shift in the supply curve makes the firms move along (upwards) the demand curve.

In both cases, the price goes up.

**Why do demand curves shift?**

1. Taste (preference) change.

2. Income change.

3. Change in a price of a complementary or substitutable good.

4. Change in the market size.

5. Expectations (i.e. thoughts about the future).

**Why do supply curves shift?**

1. Changes in input costs.

2. Shift in technology. 

## Shapes of Supply and Demand Curves

What role do shapes play? 

How shapes of supply and demand will affect the response to shocks?

The more elastic is the demand, the more price shock will come through in quantity and less in prices.

The more inelastic is the demand, the more supply shock will come through at prices and not in quantity.

## Consumer Surplus

Welfare:
: A measure of well-being.

Welfare Economics:
: Tools of normative analysis, for measuring well-being.

How to measure well-being?

Compensating Variation:
: Instead of asking how happy you are, I ask you how much do I have to pay you to become sadder (not to be worse-off)? Or how much are you willing to pay to become happier (to be better-off)? 

How to get willingness to pay? Use the demand curve.

Consumer Surplus:
: The benefit that a consumer gets from consuming a good above the price of that good.
: The difference between what a consumer is willing to pay and the cost of the good.
: The area below the demand curve and above the price.

If demand is perfectly inelastic, the consumer surplus is infinite. Because they are willing to pay anything for that good.

If demand is perfectly elastic, the consumer surplus is zero. Because they are indifferent to a perfect substitute.

E.g. Christmas gifts: a gift always has a lower surplus than giving cash. However, this ignores the utility of the person who bought the gift.

What happens to consumer surplus when prices change? Shrinks by a trapezoid.

What determines whether consumer surplus is large or small? The elasticity of demand.

## Producer Surplus

How much is a firm willing to supply a good? Use the supply curve.

Producer Surplus:
: The difference between the willingness to supply a good and its price.
: The area between the price line and upward sloping supply curve.

In the long run, producer surplus is the profit. Why is that so?

1. In the long run, average costs equal marginal costs.

2. The supply curve is the marginal cost curve, therefore is the average cost curve.

3. Profits are defined as price minus average costs.

4. That is the shaded area in the definition.

In the short run, that's not true.

Obs. Consider the following concepts:

1. Heterogeneous firms: firms with different levels of efficiency.

2. Barriers to entry: sunk costs to enter the market.

3. Upward sloping input supply: you have to charge higher prices as production goes up.

There are profits in the first two. In the last one, that is not necessarily true. The supply curve may be upwards sloping just because of the inputs arising.

# 10. Welfare Economics

## Competition Maximizes Welfare

First Fundamental Theorem of Welfare Economics:
: Competition maximizes welfare.

What is welfare?

Social Welfare:
: Consumer surplus plus producer surplus.
: $$ \text{SW} = \text{CS} + \text{PS} $$

The competitive equilibrium, where supply equals demand, is the point that maximizes social welfare.

## Government Intervention

What happens when a government imposes a price ceiling? 

Suppliers will produce less because of increasing marginal costs.

Hence, we have an excess demand that can't be resolved because the demand curve can't be moved.

And consumer surplus will diminish. 

**Costs of government intervention:**

1. **Deadweight loss:** if you didn't restrict things, there will be people who would have brought gas and the government isn't letting that happen. This is an **efficiency loss** because trades that would make people better off don't get made.

2. **Allocative inefficiency:** Is a mismatch between what is needed and who gets it. Induces opportunity cost and technical inefficiency. The market equilibrium doesn't just deliver more but delivers to those who want it the most.

**Benefits:**

Equity because rich people have more surplus than poor people.

## Examples

1. Ticket Scalping.

2. Food banks.

3. Taxi medallions.

# 11. Monopoly I

## Monopoly Profit Maximization

A monopoly is a market with only one firm.

Most markets are between perfect competition (never exists) and monopoly (rarely exists), i.e., oligopoly.

In a monopoly, firms are price makers.

Sets one price, there is no price discrimination.

Remember that profit maximization occurs where
$$ \text{MR} = \text{MC} $$

Since the costs don't change, to maximize profit the monopolist must change marginal revenue.

Marginal Revenue in a Monopoly:
: In a monopoly, marginal revenue is not profit. 
: $$ \text{MR} = p + \left(\frac{\mathrm{d} p}{\mathrm{d} q}\right) q $$
: Where $\frac{\mathrm{d} p}{\mathrm{d} q} < 0$ because demand is downward sloping, called **the poisoning effect**.
: I.e., to sell another unit, you have to lower your price.

How to get marginal revenue? Take the demand and price function, write $R = pq$ and derive.

How is marginal revenue related to the elasticity of demand?

Note that
$$ \text{MR} = p + p \left(\frac{\mathrm{d} p}{\mathrm{d} q}\right) \frac{q}{p} $$

Hence,
$$ \text{MR} = p \left( 1 + \frac{1}{\varepsilon} \right) $$

To get the price, you must solve for quantity but respect the demand curve.

The market power of a monopolist:
: Ability to charge a price greater than marginal cost.

Markup:
: $$ \frac{p-\text{MC}}{p} = - \frac{1}{\varepsilon} $$

## Welfare Effects

### Standard Case

Here the First Fundamental Theorem of Welfare Economics doesn't apply.

Market failure:
: A case where market equilibrium doesn't maximize social welfare.

### Price Discrimination

If monopolists set perfect price discrimination, then the welfare is maximized. But producers get all surplus.

# 12. Monopoly II

## How do monopolies arise?

### Cost advantages

Natural monopoly:
: For all relevant quantities, one firm can produce at a lower average cost than several other firms can.
: Average costs are always declining and have the marginal cost as an asymptote.
: E.g. utilities.

### Government action

The government can create barriers to entry, like patents, which is exclusive grant to sell something for a fixed period of time.

## Addressing monopolies

### Government regulation

**Optimal price regulation:** To eliminate the deadweight loss, the government can impose a price cap equal to the price that would prevail in a competitive market.

Problems:

1. How to find the demand curve? How much people are willing to pay for water, for example? Contingent valuation.

2. How to measure the supply curve? The regulator doesn't know the marginal cost function of the firm.

**Introducing competition:** e.g. public school choice, charter schools, and vouchers in the US.

## Contestable markets

Contestable markets:
: Monopoly markets without market power.

E.g. airline deregulation.

Consequences:

1. Prices went down.

2. Many more routes.

3. Flying sucks: no meals, tiny seats (from quality to price competition).

4. Rise of the hub and spoke system. Airports are a natural monopoly.

# 13. Oligopoly I

## What is it?

Oligopoly:
: A market with a small group of firms competing with each other and some barriers to entry.
: E.g. auto industry.

Firms can behave in two ways:

1. Cooperatively: cartel (e.g. OPEC; acts like a monopoly);
2. Non-cooperatively.

## Game Theory

Oligopolies firms engage in a game. 

**What is the strategy?**

**What is the equilibrium? When is the game over?**

Nash Equilibrium:
: The point at which no player wants to change their strategy given what the other players are doing.
: E.g. prisoner's dilemma.

Given a payoff matrix, what is the **dominant strategy**, i.e., a strategy that I would pursue no matter what the other persons are doing? 

The insight from prisoner's dilemma: non-cooperative games are worse than cooperative ones. Here, competition leads to the worst outcome.

The equilibrium is where dominant strategies intersect.

## Cournot Model

Supposes a non-cooperative game. 

Cournot Equilibrium:
: Exists when a firm chooses a quantity such that given the quantity chosen by the other firms, they don't want to change. 

How to find the Cournot Equilibrium?

1. Solve for residual demand function (market demand minus the other firms' demand). How your demand changes when some of it is absorbed by the other firms? 

2. Develop marginal revenue, which is a function of your quantity and other firms' quantity.

3. Set marginal revenue equal to marginal cost. This delivers an optimal quantity as a function of other firms' quantity.

4. Do the same thing for other firms.

5. Solve the system of equations obtained above.

Reaction (or best response) curve:
: What is the best thing to do given what the other firms are doing.

# 14. Oligopoly II

## Cartels

Cartels may enhance the profit, but cheating is lucrative for them too, because the poisoning effect is not evenly distributed between firms.

Hence, cartels are unstable.

## Comparing Equilibria

Quantities sold ($Q$) versus profits per firm ($\pi$).

Generally speaking, the oligopoly outcome is between the competitive and monopoly outcome.

The more you monopolize, the more profit you'll have.

What's welfare? As we monopolize the market, there'll be fewer goods, generating a deadweight loss, and minimizing welfare.

The more competitive the market, the more welfare, and the less profit.

## Many Firms

As the number of firms gets large, the Cournot equilibrium approaches the competitive equilibrium.

The **markup** is equal to
$$ \frac{p-\text{MC}}{p} = - \frac{1}{n \varepsilon} $$
where $n$ is the number of firms.

Mergers trade-off: economies of scale vs. market power.

## Price Competition

Bertrand Competition:
: Two firms compete over the price and then the demand curve sets the quantity.

Where Cournot competition is more likely? In what kinds of markets is Bertrand more likely? 

If there are long lags in production (e.g. auto companies), it's harder to do price competition.

Price competition is more likely the smaller the production lag.

In a Bertrand Competition, **Product Differentiation** enables pricing above the marginal cost.

# 15. Input Markets I — Labor Market

## Factor Markets

What are the prices for inputs, like labor and capital?

Assume perfect competitive input and output markets.

## Factor Demand

### Short-run labor demand

Marginal Revenue Product:
: The value of the next unit of labor.
: $$ \text{MRP}_L = \text{MP}_L \times \text{MR}$$

Remember that in a perfectly competitive market, $\text{MR} = p$.

Optimal amount of labor:
: Set the Marginal Revenue Product equal to the wage. 
: $$ \text{MP}_L \times p = w $$

### Long-run labor demand

Long-run labor demand is more elastic than short-run labor demand.

Capital Demand:
: We want to invest in new machines until the marginal product of capital times the price equals the interest rate.
: $$ \text{MP}_k \times p = r $$

## Deriving Labor Supply

How do we model how hard people want to work? 

We'll use leisure supply instead of labor supply to be able to model the trade-off between two goods: consumption and leisure.

Let $H$ be the number of hours of work and $l$ the number of hours of leisure.
$$ H = 24 - l $$

The price of leisure is the wage (opportunity cost).

As the wage goes up, the price of leisure goes up. By the substitution effect, less leisure is wanted (leisure goes down). By the income effect, more normal goods are wanted (leisure goes up).

In other words, the income effect naturally goes against the substitution effect.

What is the net effect?

## Evidence

### Research from 70s

While married women had the biggest substitution effect, men had the biggest income effect.

Labor supply curve. For women, was an upward slopping curve. 

Women's labor supply was more elastic. For men, was almost zero.

### Since then

Women's labor supply is less elastic and men's labor supply remains almost the same.

E.g. Free trade of rice in Vietnam reduced child labor and enhanced their education.

# 16. Input Markets II — Labor and Capital

## Labor Market Equilibrium & Minimum Wage

Since $\text{MP}_L \times p = w$, by introducing a minimum wage (increasing $w$), the marginal product of labor must increase. Hence, fewer workers will be hired and social welfare goes down.

However, evidence has pointed that a rise in the minimum wage didn't lower the number of jobs. What could explain that?

1. Minimum wage is not binding. Empirically false. 

2. Inelastic supply or demand. Also, empirically false.

3. Noncompetitive labor market.

Monopsony:
: Labor market where firms have market power over workers. Like a monopoly has power over goods, monopsony has over workers.

Just as a firm has no surplus in a perfectly competitive goods market, a firm hiring workers makes no surplus in a perfectly competitive labor market.

In a perfectly competitive market, a worker's wage is exactly the Marginal Revenue Product: $w = \text{MRP}_L$.

However, in a monopsony, a firm can pay less than that: $w < \text{MRP}_L$. Here, a minimum wage above the market wage and below the marginal revenue product will transfer the surplus to workers without causing deadweight loss.

## Capital Markets

The idea came from farming: consumption today vs. saving for next year.

Just as the supply of labor that determines how many workers a firm can hire comes from your decision of how hard to work, the supply of capital that determines how many machines a firm can buy comes from your decision of how hard to save.

Where does the demand function come from?

Marginal Revenue Product of Capital:
: The value of the next unit of capital.
: $$ \text{MRP}_k = \text{MP}_k \times p $$

The supply of capital comes from borrowing from people at a given interest rate.

The higher the interest rate, the more I'm willing to loan to the firm. Hence, upward slopping supply curve.

How does that happen in the real world?

1. Corporate Debt (Bonds);

2. Investing in their equity (Stock).

3. Put into a bank, that then loan to the companies.

Where does the supply curve come from?

Intertemporal Choice:
: Choosing over time. How to decide how much to save? How much do you value money today versus how much do you value money tomorrow? 

What if the interest rate increases?

We can spend more now because fewer savings are necessary to satisfy a given savings target (substitution effect).

Or we can save more (income effect).

Which effect dominates: substitution or income effect?

The evidence on this topic is weak.

The decision about life in three steps:

1. How hard to work? Maximizing utility of consumption and labor determines labor: $u(c,l) = L$.

2. How to spread that over time? Intertemporal choice determines savings: $u(c_1, c_2) = S$.

3. Maximize utility over all the goods that I want to consume $u(x_1, \ldots, x_n)$.

These steps are integrated and affect each other.

# 17. Making Choices Over Time

## Present Value

A dollar tomorrow is worth less than a dollar today.

Present Value:
: The value of every period payments in terms of today.
: Take future dollars and discount them to get what it's worth today.
: $$ PV = \frac{FV}{(1+i)^t} $$
: where $PV$ is the present value, $FV$ is the future value, $i$ is the interest rate and $t$ is the time.

For a **stream of payments**, the **present value** is:
$$ PV = f \left[ \frac{1}{(1+i)} + \frac{1}{(1+i)^2} + \ldots + \frac{1}{(1+i)^t} \right] = \frac{f}{i} \left[1 - \frac{1}{(1+i)^t} \right] $$

If the payments are made forever, we have
$$ PV = \frac{f}{i} $$

Conversely,
$$ FV = f [1 + (1+i) + (1+i)^2 + \ldots + (1+i)^{t-1}] = \frac{f}{i} [(1+i)^t - 1] $$

That's why compounding gives higher returns.

## Inflation

**Consumer Price Index (CPI)**: the government takes the price of a bundle of goods, weights them (because we spend much more on housing than on food, for example), and determines how much, in percentage, these weighted prices changed.

Real interest rate:
: Is the nominal interest rate minus the inflation rate. How much more do you have in terms of goods you can get, instead of dollars.
: $$ r = i - \pi$$

We'll assume inflation zero over the rest of the course.

## Choices Over Time

How do people make decisions over time?

Evaluate choices in present value terms.

## Investment Decisions

How do firms make investment decisions?

Net Present Value:
: In every period, account for the cost and benefits of that period, i.e., the present value of the expected return and the present value of the costs.
: A firm should make an investment only if the net present value is positive: $NPV = R - C > 0$.
: $$ NPV = R_0 - C_0 + \frac{R_1 - C_1}{(1+i)} + \frac{R_2 - C_2}{(1+i)^2} + \ldots + \frac{R_t - C_t}{(1+i)^t} $$

The interest rate is the opportunity cost of the investment.

The higher the interest rate, the lesser firms want to invest. That's why high-interest rates are bad for the economy.

Discount rate: compare with the next best thing you can do with the money.

### Worked Example: Insulating the house

Suppose that a non-insulated house costs $2000/year in gas bills. Insulating the house would reduce the gas bill in $500/year and cost $4000. Should the house be insulated?

Writing down the NPV,
$$ -4000 + \frac{500}{i} \geq 0 \iff i \leq 0.125 $$

Hence, if the interest rate is 12.5% or lower, insulating the house is the best option.

# 18. Increasing Savings & Introduction to Trade

## Increasing Savings

As savings goes up, the capital supply shifts outward, the interest rate falls, NPV of investment goes up and investment goes up.

Hence, savings lead to more investments.

Tax subsidy to retirement savings is a tool to increase savings.

If you take money to a bank, you receive $r(1-\tau)$, where $\tau$ is the tax. Due to the substitution effect, this is an incentive to not invest. 

How to deal with that?

1. Pensions: the employer takes some of your pay and puts it aside in some account.

2. 401(k) is like a pension, but the individual controls the money.

3. Individual retirement accounts (IRA). 

Are tax-deferred: pay the taxes only when you take the money out, taking advantage of present value.

Three classes of funds:

1. Money market: government bonds (treasury securities), are the safest path.

2. Bonds: corporate bonds, with moderate risk.

3. Stocks: corporate equity, with more risk.

Risk-return tradeoff:
: The riskier the investment, the higher the returns.

Key recommendation: diversification, to get the right amount of risk and return.

## What is Trade?

International Trade is a good thing for the same reason that the (internal) market is good.

The tradeoff of international trade (loss in national jobs) is worth it.

## Production Possibility Frontier (PPF)

Shows the combination of outputs you can get given a fixed level of inputs.

Economies of Scope:
: By producing more than one thing at once, you get better at both.

## Comparative Advantage

Why is international trade desirable?

Is cheaper to produce computers in the US than in Colombia. On the other hand, it is cheaper to produce roses in Colombia than in the US.

Colombia has a **comparative advantage** in roses compared to the US, because it can produce roses at a lower opportunity cost than the US. Conversely, the US has a comparative advantage in computers compared to Colombia.

It matters where you're *relatively* better.

The US is better at producing computers because to produce one computer, the US has to give up fewer roses than Colombia does.

Trade introduces economies of scope by allowing **specialization**. With trade, Colombia doesn't need to produce computers and the US doesn't need to produce roses.

Without trade, the US is inefficiently producing computers and Colombia is inefficiently producing roses.

Hence, by introducing trade the world as a whole ends up better-off.

Trade expands our PPF.

What are the sources of comparative advantage?

1. Factor endowments.

2. Technology.

# 19. International Trade: Welfare and Policy

## Welfare Trade

International trade creates a perfectly elastic supply (horizontal price curve).

Imports: Looking only at domestic welfare, introducing trade increases consumer surplus, while diminishing producer surplus.

Expanding the opportunity set allows consumers to get cheaper goods, raising consumer surplus more than you reduce producer surplus. I.e., we are better off even considering consumer plus producer surplus.

Exports: Introducing trade increases producer surplus, while diminishing, in a lesser lever, consumer surplus. Society as a whole is better off.

Welfare goes up in both cases. It's a win-win game.

## Trade Policy

However, importation reduces the number of domestic jobs.

Two kinds of import deterrence:

1. Quotas: limits the number of imported goods. Less used today.

2. Tariff: a tax on the price of imported goods.

What is the impact of tariffs on surplus? 

Diminishes not only consumer surplus but the total surplus.

Trade policy creates **trade wars**, making producers worse-off and losing jobs in other areas (such as computers in the US).

Trade policy also makes **other countries worse-off**. 

Why are people so opposed to free trade?

1. We don't compensate the losers.

2. Socially damaging routes to comparative advantage.

3. Trade policy as a tool of foreign policy.

# 20. Uncertainty

## Expected Utility

Expected value:
: Probability that you win times what you win plus probability that you lose times what you lose.
$$ \mathrm{EV} = \mathrm{Pr(win)} \times \mathrm{Value(win)} + \mathrm{Pr(lose)} \times \mathrm{Value(lose)} $$

Fair bet:
: Expected value equal to zero.

More than fair bet:
: Expected value bigger than zero.

Expected utility:
: Probability that you win times the utility that you win plus probability that you lose times the utility that you lose.
$$ \mathrm{EU} = \mathrm{Pr(win)} \times \mathrm{U(win)} + \mathrm{Pr(lose)} \times \mathrm{U(lose)} $$

The utility function has a diminishing MRS (it is concave). This implies a non-linearity.

Risk aversion: 
: A certain dollar is worth more than an uncertain dollar.

This explains why, even in a more than fair bet, we choose not to bet: the expected utility is worse than doing nothing.

![Risk Aversion](Images/perloff_17.2.png "Risk Aversion")

## Extensions

As gambles become smaller relative to your income, the utility function becomes locally flatter. As a result, you become more and more risk-neutral.

Loss aversion:
: Losing makes us sadder than happier when we get something new.

## Applications

### Insurance

Insurance is a big business in America. Why is that?

Risk premium: 
: How much do you pay to be taken out of a gamble.

Insurance is a profitable business because people are willing to pay to avoid risky situations.

The bigger the risk (how much further from the linear part of the utility function), the more we are willing to pay.

### Lottery

Lotteries are less than fair bets. Still, they are very popular. Why do people play lotteries?

Four theories:

1. Risk loving, which is wrong (see Insurance).

2. Risk tolerance varies: people are locally risk-averse but globally risk-loving. This is also wrong because most money put on lotteries is in small quantities.

3. Entertainment. 

4. Ignorance.

# 21. Efficiency and Equity

The equity-efficiency tradeoff: making equity results in loss of efficiency. E.g. Okun's leaky bucket.

## Valuation

How does society think about redistribution?

Social Welfare Function (SWF):
: Society utility function. Is an aggregate of all societies utilities:
$$ \mathrm{SWF} = f(u_1, u_2, \ldots, u_n) $$

Isowelfare curves: society's indifference curves.

### Utilitarian SWF

$$ \mathrm{SWF} = u_1 + u_2 + \ldots + u_n $$

In this model, the optimum is redistribution until all marginal utilities are equal.

### Rawlsian SWF

The goal of society is to optimize the well-being of its worst well-off members. See "veil of ignorance".

$$ \mathrm{SWF} = \min(u_1 + u_2 + \ldots + u_n) $$

### Nozickian View

Never redistribute income, only redistribute opportunities.

What is equal opportunity?

Ignores luck.

### Commodity Egalitarianism

All that matters is not relative income, but to make sure that everybody has the basics.

A mix of Rawlsian and Nozickian views.

## Inequality

What do we know about inequality? How to measure it?

Inequality is a measure of relative distribution.

The poverty line is a measure of absolute deprivation. How many people are living with less than they need?

But how to judge what is deprivation? Poverty line.

The Baltimore example: deprivation leads to lower life expectancy.

## Sources of leakage

Why is not possible to have a leak-free bucket?

Sources:

1. Administrative costs

2. Efficiency cost of taxation

3. Efficiency cost of transfers 

The effect on the labor market: when you tax people, they work less.

Is it worth redistributing? Use SWFs to measure it.

Marginal tax rate:
: Only pay on the next dollar. Example: 20% over 20k.

# 22. Government Redistribution and Taxation

## Taxation in the US

### Tax Incidence: Who bears the taxes?

E.g. increasing $\$ 0.50$ the gas tax.

Increasing tax changes the supply curve.

Consumer burden: $\$ 0.30$.

Producer burden: $\$ 0.20$.

Statury burdens are not real burdens.

Tax wedge:
: The difference between the tax including the price and the tax after paying price. The difference between what the consumers pay and what producers receive from a transaction.

The *side of the market is irrelevant*: if we add $\$ 0.50$ to the consumer, the demand curve changes, but the burden is exactly the same on both consumer and producer.

Tax salience:
: Awareness of a tax. How tax is presented changes demand and how people behave.

Inelastic parties: get stuck with taxes.

Elastic parties: avoid taxes.

### What should be taxed? 

Income ($y$) or Consumption ($c$)?

Europe uses, mainly, VAT (Valued Added Tax), which is a kind of consumption tax.

What this matters?
$$ y = c + s $$
where $s$ represents savings.

If income is taxed, the savings are also taxed. If consumption is taxed, the savings are not taxed.

What about fairness?

## Transfers

Transfers are *implicit taxes*. 

E.g. a transfer $T = \max(0, 10000-y)$. 

Categorial transfers:
: Instead of giving money to everybody, give it only to a certain population. E.g. SSI (Supplemental Security Income), TANF (Temporary Assistance for Needy Families), UBI (Universal Basic Income). 

In-kind transfers:
: E.g. Self-reveal. Reason to use it: because politicians are paternalistic.

EITC (Earned Income Tax Credit): Conditional transfer (requires work). Wage subsidy (negative tax). 

EITC increases labor supply and redistributes, avoiding the bucket leak.

# 23. Market Failures I: Externalities

## Externality Theory

Externality:
: When the actions of one party impacts another party in a way that the first party does not receive the costs or the benefits.

A **Negative Production Externality** comes from the supply side and negatively affects other party. E.g.: industries polluting a river and fisherman.

Here, Social Marginal Benefit is equal to Private Marginal Benefit, but Social Marginal Cost includes the costs/benefits to other parties.

Smoking is an example of **Negative Consumption Externality**. Social Marginal Cost equals Private Marginal Cost, but Social Marginal Benefit is below Private Marginal Benefit.

A neighbor that mowing his lawn is a **Positive Consumption Externality**.

Companies' investment in research and development is an example of **Positive Production Externality**.

## Government Solutions

Market Failure:
: Will the private market fail to maximize welfare?

Is there a market failure? Can de government actually make it better instead of worse?

Options to deal with market failure:

1. Regulation. Problems are the same as in regulating monopoly: requires too much information, the supply, the demand and the size of the externality.

2. Corrective Taxation. In externalities, taxes can reduce deadweight losses, by making the Private Marginal Cost equal to Social Marginal Cost (for example).

## Government Policy

### Environmental Externalities

Hard problem: imposing restrictions now that will only benefit people in the future. Costs today and benefits tomorrow.

### Health Externalities

Examples: smoking, drinking, illegal drugs.

Most externalities from illegal drugs come from fighting them.

# 24. Market Failures II: Informational Asymmetry

## Why Social Insurance? 

Are government-provided insurance programs.

Kinds of market failures:

- Imperfect competition.

- Externalities.

- Informational Asymmetry.

Informational Asymmetry:
: Difference in the information available to sellers and buyers in a given market.

Example: lemons in used cars market. Transactions that would be made both parties better-off didn't happen because of imperfect information.

Adverse Selection:
: Due to informational asymmetries, only the worse risks will participate in the market. That will cause people selling in the market to lose money.

Insurance problem: healthy people are kept outside of insurance by adverse selection.

**Government solutions:**

1. Subsidization. Tax subsidy to employer health insurance.

2. Mandate. Workers' compensation.

3. Provide.

## Social Insurance Tradeoff

Moral Hazard:
: Adverse behavior that is encouraged by insurance.

This has two costs:

1. Lower efficiency. Remember that the worker will trade consumption and leisure until the marginal value of leisure equals the wage. People will work less than the socially optimal.

2. Raises tax revenues required.

## Social Security

Biggest social insurance in the US.

Tradeoff: keep working and earning more or retire? 

# 25. Health Economics

US spends about 19.7% of GDP on health. A lot more than other countries.

If you are in the system, the US has one of the best health systems in the world.

However, the access is highly unequal.

60% of Americans have employer-sponsored insurance (ESI).

6% have individual/nongroup health insurance. 

20% have government-sponsored insurance (Medicare and Medicaid). Medicare is for the elderly. Medicaid is for the poor.

15% uninsured, mostly working poor (not qualified for Medicaid, their jobs don't offer insurance and they can't afford individual insurance).

How the government can deal with health insurance?

1. Subsidization.

2. Single-payer. Political problems:

2.1. Paying for it. ESI is a hidden tax, reducing wages.

2.2. Status quo bias. 

2.3. Insurance companies' lobbying.

3. Three-legged stool approach (e.g. Affordable Care Act).

3.1. Ban insurance discrimination.

3.2. Individual mandate.

3.2. Subsidies.

The increase in health expenses made it better.

About a 1/3 of the spending on health is wasteful.

How to deal with the costs of healthcare:

1. Regulatory path.

2. Supply regulation.

3. Price regulation.

4. Incentives.