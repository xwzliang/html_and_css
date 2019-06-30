# Tables

## Basic table structure
```
<table>
  <tr>
    <td>15</td>
    <td>15</td>
	<td>30</td>
  </tr>
  <tr>
    <td>15</td>
    <td>15</td>
	<td>30</td>
  </tr>
  <tr>
    <td>15</td>
    <td>15</td>
	<td>30</td>
  </tr>
</table>
```
You indicate the start of each row using the opening `<tr>` tag. (The tr stands for table row.)
Each cell of a table is represented using a `<td>` element. (The td stands for table data.)

## Table headings
```
<table>
  <tr>
	<th></th>
	<th scope="col">Saturday</th>
	<th scope="col">Sunday</th>
  </tr>
  <tr>
	<th scope="row">Tickets sold:</th>
	<td>120</td>
	<td>135</td>
  </tr>
  <tr>
	<th scope="row">Total sales:</th>
	<td>$600</td>
	<td>$675</td>
  </tr>
</table>
```
Even if a cell has no content, you should still use a <td> or <th> element to represent the presence of an empty cell otherwise the table will not render correctly. (The first cell in the first row of this example shows an empty cell.)

## Spanning columns and rows
`<td colspan="2">text</td>`
`<td rowspan="2">text</td>`

## Long tables
```
<table>
  <thead>
	<tr>
	  <th>Date</th>
	  <th>Income</th>
	  <th>Expenditure</th>
	</tr>
  <thead>
  <tbody>
	<tr>
	  <th>2nd January</th>
	  <td>285</td>
	  <td>48</td>
	</tr>
	<!-- additional rows as above -->
	<tr>
	  <th>31st January</th>
	  <td>129</td>
	  <td>64</td>
	</tr>
  </tbody>
  <tfoot>
	<tr>
	  <td></td>
	  <td>7824</td>
	  <td>1241</td>
	</tr>
  </tfoot>
</table>
```
There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content) -- thead, tbody and tfoot.

## Old Code width and spacing (Use CSS instead)
```
<table width="400" cellpadding="10" cellspacing="5">
  <tr>
	<th width="150"></th>
	<th>Withdrawn</th>
	<th>Credit</th>
	<th width="150">Balance</th>
  </tr>
  <tr>
	<th>January</th>
	<td>250.00</td>
	<td>660.50</td>
	<td>410.50</td>
  </tr>
</table>
```
The opening <table> tag could also use the cellpadding attribute to add space inside each cell of the table, and the cellspacing attribute to create space between each cell of the table. The values for these attributes were given in pixels.

## Old Code border and background
```
<table border="2"  bgcolor="#efefef">
  <tr>
	<th width="150"></th>
	<th>Withdrawn</th>
	<th>Credit</th>
	<th width="150" bgcolor="#cccccc">Balance</th>
  </tr>
  <tr>
	<th>January</th>
	<td>250.00</td>
	<td>660.50</td>
	<td bgcolor="#cccccc">410.50</td>
  </tr>
</table>
```

