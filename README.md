# chemistry-copilot
Chemistry copilot that helps in visualizing and solving Stiochiometry problems. Try it at: https://chemistry-copilot.netlify.app/

## Overview

The goal of this project is to provide a framework to visualize Stoichiometry problems and to use “The Bridge” method for easily determining quantities of reactants and products that participate in or are produced during a chemical reaction. The visualization also helps in understanding which reactant is the limiting agent.

## Understanding Moles
Typically a balanced chemical reaction provides us with the ratios in which different reactants must be combined and the relationship (ratio) of the product with the reactants (just like in a recipe). In a recipe, the actual measurements are usually done in units such as gms, ounces etc. Similarly in a chemistry lab, how does one measure out the reactants? For solid reactants, mass (gms) is a reasonable way of measuring. But do the ratios apply directly to the masses of the reactants? Not really. The relationship and therefore ratios are more in terms of the number of atoms or molecules of the elements or compounds involved because the chemical reaction must be balanced in terms of the atoms and molecules. However since atoms and molecules are infinitesimally small, we need to be able to measure out reactants and products in a more practical way. It so happens that when you take 6.022 * 10 raised to 23 (which is also referred to as Avogadro’s number) atoms/molecules, their mass in gms equals the atomic/molecular mass. This unit of 6.022 * 10 raised to 23 atoms or molecules is referred to as 1 mole. All ratios in chemical reactions are molar ratios. Quantities can be measured out in gms but must be converted to and from moles to relate reactants and products to each other.

The concept of translating from any quantity (mass, vol) to moles, then using the ratio from the balanced equation to get the equivalent moles of other reactants/products, and finally converting back from the moles to the required quantity (mass, vol) using the molar mass, is known as the bridge method. We will use this to visualize and solve different types of problems.

## Types of Problems Supported

1. The quantities of all reactants are provided and the quantity of the product is to be determined. The limiting reactant needs to be identified.

<b>Example problem:</b> 
Hydrogen gas reacts with nitrogen gas to produce ammonia according to the balanced chemical equation: N2(g)+3H2(g)→2NH3(g)
In a reaction vessel, 5.00 g of nitrogen gas (N₂) is mixed with 2.00 g of hydrogen gas (H₂). Determine which reactant is the limiting reactant and the mass of ammonia (NH₃) produced.

2. The quantity of one reactant is provided, all other reactants are available in excess and the quantity of the product is to be determined.
	
<b>Example problem:</b> 
Propane combusts completely in oxygen to form carbon dioxide and water:
C3H8(g)+5 O2(g)→3 CO2(g)+4 H2O(g)

If 10.0 g of propane (C₃H₈) is burned and oxygen is present in excess determine the mass of carbon dioxide (CO₂) produced.

3. The quantity of one reactant is provided, and the quantity of other reactant(s) has to be determined to react completely with the specified reactant quantity.

<b>Example problem:</b>
Given: 12.0 g of magnesium (Mg).
Find: mass of hydrochloric acid (HCl) required to react completely with the Mg.
Equation: Mg(s)+2HCl(aq)→MgCl2(aq)+H2(g)

4. Any of the above three scenarios, and product quantity is also provided. In this case, we need to compare actual product quantity with theoretical yield calculated from the reactants’ quantities, and then calculate the efficiency.

<b>Example problem:</b>
Given: 5.00 g of aluminum (Al), 20.0 g of copper(II) chloride
Actual mass of product obtained: 8.50 g of copper metal (Cu).
Find: The theoretical yield of copper and the percent yield (efficiency).
Equation (balanced): 2Al+3CuCl2→2AlCl3+3Cu

