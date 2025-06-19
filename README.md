<!DOCTYPE html>
<html>
<head>
	<title>Array</title>
</head>
<body>
	<script>
		let array = [0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20];
		console.log("Original Array:", array);

		let oddNumbers = array.filter(n => n % 2 === 1);
		console.log("Filtered (Odd Numbers):", oddNumbers);

		let isOddFlags = array.map(n => n % 2 === 1);
		console.log("Mapped (Is Odd Flags):", isOddFlags);
	</script>
</body>
</html>