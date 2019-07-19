# aard-costs
Costs for potential, instinct, mastery.<br>
<br>
 >> Change log: <br>
    7/19/2019 Fixed regex but that wasn't catching > 2 word skills/spells for instinct. <br>
    <br>
    <br>
 >> Syntax is: <br>
       costs help<br>
       (potential|mastery \<type>|instinct \<type>) \<#><br>
       (potential|mastery \<type>|instinct \<type>) to \<#><br>
       (potential|mastery \<type>|instinct \<type>) \<start> \<#><br>
        The  variable is optional, otherwise your current potential is used.<br>
         e.g. <b>potential 5</b> Will calculate how much for you to buy 5 potential.<br>
         e.g. <b>potential to 100</b> Will calculate how much for you to increase your potential to 100.<br>
         e.g. <b>potential 100 5</b> Will calculate how much to buy 5 potential if you have 100.<br>
         e.g. <b>mastery electric 5</b> Will calculate how much to buy 5 electric mastery.<br>
         e.g. <b>mastery electric to 104</b> Will calculate how much to buy electric mastery from your current amount to 104.<br>
         e.g. <b>mastery electric 100 5</b> Will calculate how much to buy 5 electric mastery if you have 100.<br>
         e.g. <b>instinct dodge 5</b> Will calculate how much to buy 5 dodge instinct.<br>
         e.g. <b>instinct dodge to 104</b> Will calculate how much to buy dodge instinct from your current amount to 104.<br>
         e.g. <b>instinct dodge 100 5</b> Will calculate how much to buy 5 dodge instinct if you have 100.<br>
