<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head profile="http://selenium-ide.openqa.org/profiles/test-case">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<link rel="selenium.base" href="http://www.office.co.uk/" />
<title>New Test</title>
</head>
<body>
<table cellpadding="1" cellspacing="1" border="1">
<thead>
<tr><td rowspan="1" colspan="3">New Test</td></tr>
</thead><tbody>
<tr>
	<td>open</td>
	<td>/</td>
	<td></td>
</tr>
<tr>
	<td>type</td>
	<td>id=searchBox</td>
	<td>Nike</td>
</tr>
<tr>
	<td>clickAndWait</td>
	<td>//input[@value='Search']</td>
	<td></td>
</tr>
<tr>
	<td>clickAndWait</td>
	<td>css=div.productList_info &gt; div &gt; a.displayBlock.brand</td>
	<td></td>
</tr>
<tr>
	<td>select</td>
	<td>id=sizeShoe</td>
	<td>label=9</td>
</tr>
<tr>
	<td>clickAndWait</td>
	<td>id=addButton</td>
	<td></td>
</tr>

</tbody></table>
</body>
</html>
