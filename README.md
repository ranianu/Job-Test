**Box-Model**

Every element that can be displayed on a web page is comprised of one or more rectangular boxes. Box model typically describes how these rectangular boxes are laid out on a web page. which is used to create a definition for the way the HTML elements are organized on the screen. This approach accounts for options such as margins, padding, borders, and all the properties that manipulate them. It can be used as a toolkit for customizing the layout of different elements.

**Demo of box model: checkout the ( Box.html ) in the main repository.**




**JavaScript Test**

1.  Return the sum of the price of all properties as a single value.

     **const sum = sales.reduce((total, sale) => sale.price + total, 0)**

2.  Return the items which were sold in 2017.
    
    **const SaleIn2017 = sales.filter(sale => new Date(sale.dateSold).getFullYear() === 2017 )**

3.  Return an array of all of the itemsSold properties as strings, sorted alphabetically.

    **const itemSold = sales.map(sale => sale.itemSold).sort()**

4.  Using id as an argument, return the sale which matches the id.

    **const SaleByIdTarget = (sales) => (id) => sales.find(sale => sale.id === id);**
    
    **const SaleById = SaleByIdTarget(sales)**
    
    **const targetSale = SaleById('j_123')**
