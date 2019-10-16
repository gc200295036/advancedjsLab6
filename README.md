# advancedjsLab6
TITLE (async/await/fetch)
Introduction To Fetch API: Fetch will gat json data from an API source data.
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
let info;


fetch('https://api.github.com/users/gc200295036')
.then(response => response.json())
.then(data => {
info = data
console.log(info);
})

Screenshot:See repo
