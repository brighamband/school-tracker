<script>
	let cs203 = 'Proxy Lab 2';
	import { classwork } from '../data.js';
</script>

<h1>School Tracker Table</h1>

<table>
	<thead>
		<tr>
			<th />
			<th>Su</th>
			<th>Mo</th>
			<th>Tu</th>
			<th>We</th>
			<th>Th</th>
			<th>Fr</th>
			<th>Sa</th>
		</tr>
	</thead>
	<tbody>
		{#each classwork as el}
			<tr>
				<td>{el.class}</td>
				<td />
				<td>add here</td>
				<td />
				<td />
				<td />
				<td />
				<td />
			</tr>
		{/each}
		<tr>
			<td>CS 203</td>
			<td />
			<td />
			<td />
			<td />
			<td />
			<td>{cs203}</td>
			<td />
		</tr>
		<tr>
			<td>CS 240</td>
			<td />
			<td />
			<td />
			<td />
			<td />
			<td />
			<td />
		</tr>
		<tr>
			<td>CS 260</td>
			<td />
			<td />
			<td />
			<td />
			<td />
			<td />
			<td />
		</tr>
	</tbody>
</table>
{JSON.stringify(classwork)}

<style>
	th,
	td {
		padding: 2rem;
		border: 2px solid black;
	}
</style>
