# cardealerproject
# A Car dealer wants to automate the billing process of cars based on the car selected. The
# the showroom price). Car dealer can apply discount only if the
customer opts in for either insurance or additional accessories and cannot cross 30,000.
There should be an error saying maximum discount to be applied should not cross 30,000 and
only apply 30,000 as discount.
If the customer doesn’t opt-in for insurance or additional accessories and if the dealer tries to
add a discount it should show an error saying any one of the additional features have to be
added and 0 discount has to be added.
After selecting car and opt in options the total amount to be paid has to be displayed
Sample Input 1:
Select car model: Virtus Highline
Do you need Insurance: yes
Do you need Additional Accessories: no
Dealer discount: 2%
Output:
Total cost 14,54,130 (Virtus Highline 13,08,000 + 1,13,990(RTO) + 47,300(Insurance) +
11,000(TCS) - 26160(Dealer discount))
Sample Input 2:
Select car model: Taigun Topline
Do you need Insurance: yes
Do you need Additional Accessories: yes
Dealer discount: 20,000
Output:
Total cost 19,38,290 (Taigun Topline 17,71,000 + 1,13,990(RTO) + 47,300(Insurance) +
11,000(TCS) + 15,000(Additional Accessories) - 20,000(Dealer discount))
Sample Input 3:
Select car model: Polo Trendline
Do you need Insurance: no
Do you need Additional Accessories: no
Dealer discount: 0
Output:
Total cost 9,94,990 (Polo Trendline 8,70,000 + 1,13,990(RTO) + 0(Insurance) + 11,000(TCS) +
0(Additional Accessories) - 0(Dealer discount))
