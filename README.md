# Sal's Shipping
**Intro to programming: Sal's Shipping (CodeCademy project):**

Sal runs the biggest shipping company in the tri-county area, Sal’s Shippers. Sal wants to make sure that every single one of his customers has the best, and most affordable experience shipping their packages.

![image](https://user-images.githubusercontent.com/100479971/227393963-a28cdcea-3257-44c5-b3ac-cd725ecbc07d.png)

This project, consist on a program (written on Python) that will take the weight of a package and determine the cheapest way to ship that package using Sal’s Shippers.

Sal’s Shippers has several different options for a customer to ship their package:

- Ground Shipping, which is a small flat charge plus a rate based on the weight of your package.
- Ground Shipping Premium, which is a much higher flat charge, but you aren’t charged for weight.
- Drone Shipping (new), which has no flat charge, but the rate based on weight is triple the rate of ground shipping.

<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax"><span style="font-weight:700;font-style:normal">Weight of Package</span></th>
    <th class="tg-0lax"><span style="font-weight:700;font-style:normal">Price per Pound</span></th>
    <th class="tg-0lax"><span style="font-weight:700;font-style:normal">Flat Charge</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-buh4">2 lb or less</td>
    <td class="tg-buh4">$1.50</td>
    <td class="tg-buh4">$20.00</td>
  </tr>
  <tr>
    <td class="tg-0lax">Over 2 lb but less than or equal to 6 lb</td>
    <td class="tg-0lax">$3.00</td>
    <td class="tg-0lax">$20.00</td>
  </tr>
  <tr>
    <td class="tg-buh4">Over 6 lb but less than or equal to 10 lb</td>
    <td class="tg-buh4">$4.00</td>
    <td class="tg-buh4">$20.00</td>
  </tr>
  <tr>
    <td class="tg-0lax">Over 10 lb</td>
    <td class="tg-0lax">$4.75</td>
    <td class="tg-0lax">$20.00</td>
  </tr>
</tbody>
</table>

**Ground Shipping Premium**

Flat charge: $125.00

**Drone Shipping**

<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax"><span style="font-weight:700;font-style:normal">Weight of Package</span></th>
    <th class="tg-0lax"><span style="font-weight:700;font-style:normal">Price per Pound</span></th>
    <th class="tg-0lax"><span style="font-weight:700;font-style:normal">Flat Charge</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-buh4">2 lb or less</td>
    <td class="tg-buh4">4.50</td>
    <td class="tg-buh4">$00.00</td>
  </tr>
  <tr>
    <td class="tg-0lax">Over 2 lb but less than or equal to 6 lb</td>
    <td class="tg-0lax">$9.00</td>
    <td class="tg-0lax">$00.00</td>
  </tr>
  <tr>
    <td class="tg-buh4">Over 6 lb but less than or equal to 10 lb</td>
    <td class="tg-buh4">$12.00</td>
    <td class="tg-buh4">$00.00</td>
  </tr>
  <tr>
    <td class="tg-0lax">Over 10 lb</td>
    <td class="tg-0lax">$14.25</td>
    <td class="tg-0lax">$00.00</td>
  </tr>
</tbody>
</table>

This little Python program asks the user for the weight of their package and then tells them which method of shipping is cheapest and how much it will cost to ship their package using Sal’s Shippers.
