# Myntra Size Chart

We've all used a size chart while online shopping. Let's recreate one using HTML.
 
Acceptance Criteria
 
- The header row should be in `<thead>` and `<th>`
- The data rows should be wrapped in `<tbody>`
- Naming of rows and columns should be same as given in image
- Appropriate use of `<tr>` and `<td>` tags
 
 
CSS part for table is optional.
<!doctype html>
<html>
<head>
<title>  my web page </title>
<style>
    table,
    th,
    td {
        border: 1px solid black;
        border-collapse: collapse;
    }
    </style>
</head>
<body>

<table style = width:100%>
<tr style="background-color:red;">
<th>Part</th>
<th>XS</th>
<th>S</th>
<th>M</th>
<th>L</th>
<th>XL</th>
</tr>
<tr style="background-color:orange;">
<td>Waist</td>
<td>25</td>
<td>28</td>
<td>30</td>
<td>31</td>
<td>32</td>
</tr>
<tr style="background-color:pink;">
<td>Chest</td>
<td>34</td>
<td>34</td>
<td>38</td>
<td>40</td>
<td>41</td>
</tr>
<tr style="background-color:gray;">
<td>Sleeve</td>
<td>23</td>
<td>24</td>
<td>24</td>
<td>25</td>
<td>25</td>
</tr>
</table>

</body>
</html>
