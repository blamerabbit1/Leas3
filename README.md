<p>1</p>
<p>2</p>
<p>3</p>
<p>4</p>
<p>5</p>
<p>6</p>
let elems = document.querySelectorAll('p');
console.log(elems);
let elems = document.querySelectorAll('p');

for (let elem of elems) {
	console.log(elem);
}
let elems = document.querySelectorAll('p');

for (let elem of elems) {
	console.log(elem.textContent);
}
let elems = document.querySelectorAll('p');

for (let elem of elems) {
	let text = +elem.textContent;
	
	if (text % 3 === 0) {
		console.log(text);
	}
}****
let elems = document.querySelectorAll('p');
let sum = 0;

for (let elem of elems) {
	let text = +elem.textContent;
	
	if (text % 3 === 0) {
		sum += text;
	}
}

console.log(sum);
<ul>
	<li>2000</li>
	<li>2004</li>
	<li>2021</li>
	<li>2022</li>
	<li>2025</li>
	<li>2031</li>
</ul>
