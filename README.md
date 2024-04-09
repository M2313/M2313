<html>

<head>

<title>ARRAY ADDITION</title>

</head>

<body>

<script language="javascript">

a=new Array(5);

var s=0;

document.write("<h1><u>Array Addition</u></h1>");

for(i=0;i<5;i++)

{

a[i]=parseInt(prompt("Enter the number"));

}

document.write("<h1>The given Array elements are</h1>");

document.write("<br>");

for(i=0;i<5;i++)

{

document.write(a[i]);

document.write("<br>");

s=s+a[i];

}

document.write("The addition of given Array elements are "+s);

</script>

</body>

</html>
