---
title: "Enter Hand"
date: 2018-05-20T11:21:14-04:00
draft: false
weight: 50
---

![HandBefore](../images/gen/Rubber/HandBefore.png)

This page allows the scorekeeper to enter the contract that was bit for the hand, and the result of playing the hand.

For the contract and results buttons, the color of the button has the following meaning:

- The dark yellow
<svg width="15.00" height="15.00" viewBox="-10.1 -10.1 20.2 20.2" class="piechart" style="display: inline-block;">
  <circle cx="0" cy="0" r="10" fill="yellow" stroke="black" stroke-width="1"></circle>
</svg>
buttons indicates what should be selected next.
- The light yellow
<svg width="15.00" height="15.00" viewBox="-10.1 -10.1 20.2 20.2" class="piechart" style="display: inline-block;">
  <circle cx="0" cy="0" r="10" fill="lightyellow" stroke="black" stroke-width="1" stroke="black" stroke-width="1"></circle>
</svg>
buttons indicates that this still needs to be selected, but something else should be selected first.
- The light green
<svg width="15.00" height="15.00" viewBox="-10.1 -10.1 20.2 20.2" class="piechart" style="display: inline-block;">
  <circle cx="0" cy="0" r="10" fill="lightgreen" stroke="black" stroke-width="1"></circle>
</svg>
buttons indicates the selected item.
- The gray
<svg width="15.00" height="15.00" viewBox="-10.1 -10.1 20.2 20.2" class="piechart" style="display: inline-block;">
  <circle cx="0" cy="0" r="10" fill="rgb(210,210,210)" stroke="black" stroke-width="1"></circle>
</svg>
buttons indicates another item was selected for this item.

![Hand](../images/gen/Rubber/Hand.png)


The contract is entered at the top, the number of tricks, the suit or no trump, the double status and the declarer.  The declarer diamond always has the scorekeeper on the bottom.  If the scorekeeper is entering the data, then the remaining names are in the same position on the page as players at the table.

Enter the honors earned by any player, **0** is selected by default.  This section is only displayed when a contract suit has been selected.  When a suit is chosen, then the honor points will be **0**, **100**, **150**.  In No trump, **0**, **150**.  Select the player that earned the honors.

Once the contract has been entered, then the **Made** and **Down** buttons appear, once one of them is clicked, then the trick number buttons appear.  For made contracts the numbers refer to the number of tricks above 6.  For down contracts the numbers refer to the number of tricks the contract is down.

Verify the score at the bottom right, above the **OK** button.  At the bottom right, above the **Clear** button, there is a breakdown of how the score was calculated.

When the contract and result is correct, hit the **OK** button and go to the [summary page](summary.html).

The **Clear** button is to remove all the contract and result selections.

The **Cancel** button will not save any results, and return to the [summary page](summary.html).

The scorekeeper can be changed in the middle of the round by hitting the **Change Scorekeeper** button.

If a declarer button has a red square with the word *Vul* in it, then that players team is vulnerable for that hand.  Not vulnerable is shown with a gray square with the word ~~vul~~.
