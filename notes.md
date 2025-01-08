```const url = require("url")

let x = new URL("https://www.google.com:8080")

console.log(Host: ${x.hostname})
console.log(Protocol: ${x.protocol})
console.log(Port: ${x.port})
console.log(path: ${x.pathname})
console.log(Query Parameters: ${x.searchParams})
console.log(Fragment: ${x.hash})

x.searchParams.set("id,"2")
console.log(x.href)```