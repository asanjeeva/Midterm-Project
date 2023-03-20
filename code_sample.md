# Code Sample


Some of the code sample written by me

### HTML
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>

<script>
function fizzbuzz() {
var display = document.getElementById('display');
var displayHTML = "";
for (i = 0; i < 100; i++) {
displayHTML += "<p>" + i + "</p>";
}
display.innerHTML = displayHTML;
}
</script>
</head>
<body onload="fizzbuzz()">
<div id="display">
</div>
</body>
</html>
  
### Lebron James Vs Jordan HTML
  <!DOCTYPE html>
<html>
<head>
	<title>Comparison between Michael Jordan and LeBron James</title>
	<style>
		table, th, td {
			border: 1px solid black;
			padding: 10px;
			text-align: center;
		}
	</style>
</head>
<body>
	<h1>Comparison between Michael Jordan and LeBron James</h1>
	<table>
		<tr>
			<th></th>
			<th>Michael Jordan</th>
			<th>LeBron James</th>
		</tr>
		<tr>
			<td><strong>Championships won</strong></td>
			<td>6</td>
			<td>4</td>
		</tr>
		<tr>
			<td><strong>Finals MVPs</strong></td>
			<td>6</td>
			<td>4</td>
		</tr>
		<tr>
			<td><strong>Regular season MVPs</strong></td>
			<td>5</td>
			<td>4</td>
		</tr>
		<tr>
			<td><strong>Scoring titles</strong></td>
			<td>10</td>
			<td>1</td>
		</tr>
		<tr>
			<td><strong>All-NBA selections</strong></td>
			<td>11</td>
			<td>17</td>
		</tr>
		<tr>
			<td><strong>All-Defensive selections</strong></td>
			<td>9</td>
			<td>6</td>
		</tr>
		<tr>
			<td><strong>Points per game (career)</strong></td>
			<td>30.1</td>
			<td>27.1</td>
		</tr>
	</table>
	<p>While LeBron James has had an impressive career, Michael Jordan is widely considered the better player due to his superior championship record, Finals MVPs, and scoring titles. However, LeBron has more All-NBA selections and has played for longer than Jordan did, which adds to his overall accomplishments. Ultimately, the debate over who is the better player is subjective and comes down to personal preference.</p>
</body>
</html>

