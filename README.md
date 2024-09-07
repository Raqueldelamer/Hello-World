# Hello-World

<h2>"GitHub API" environment in Postman & Bearer Token</h2>
<br>

Setting up a new GET request to {{baseUrl}}user/repos was straigtforward with step by step instructions. As for getting a token, I noticed that you have to be very careful with this process and where you store the token as it can stop working if not set correctly before generating it. The bearer token was tricky to get. Unfortunately I didn’t take screenshots of the process because I was in a breakout room getting verbal instructions from Robert. The token is one time view from the GitHub website. Had I not saved it and sent it to myself in an email, I would’ve potentially lost it because they don’t send emails with they token like other api sites do. Also, another tricky thing about it is that I refreshed the page and lost my 201 Created access to the post repo page. Thankfully I took a screenshot of it, which is below with part of the json because when attempting to redo the Post user/repos with the token entered, I received a 422 Unprocessable Error code. :(
<br>
<br>
{"name":"Hello-World","description":"This is your first repo!","homepage":"https://github.com",
"private":false,
"is_template":true}
<br><br>
This is your first repo!

Postman - GitHub Repo <br>

<img src="https://github.com/user-attachments/assets/b280b5e3-a761-4fa2-9846-18d5d838be0b">
<br>
<img src="https://github.com/user-attachments/assets/21a391f0-98d0-44c8-8a18-d2ff08e88fa9">
