Strings for testing on web-browser

fetch('/message',{method: 'POST',headers:{'Content-Type': 'application/json'}, body: JSON.stringify({text: 'fourth message'})}).then(console.log)

fetch('/message/4',{method: 'PUT',headers:{'Content-Type': 'application/json'}, body: JSON.stringify({text: 'fourth message', id:10})}).then(console.log)

fetch('/message/4',{method: 'DELETE'}).then(console.log)
