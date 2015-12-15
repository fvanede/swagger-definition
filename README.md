# swagger-definition
Swagger definition as YAML and JSON format for HC REST web services:
* C2B Public
  * Leaderboard web service (tournaments and ranking of players)
* C2B Secured (token based)
  * Player data
* B2B Secured (ip filtering and Basic Authentication)
 * Registration service, including operations to return player information, jackpot values, player preferences etc.

Used bootprint-swagger to pretty print the JSON definition file and placed it in the documentation subdirectory. The command for this is:
`bootprint swagger swagger.json documentation/`. Documentation shall be a subdirectory in which an `index.html` and style sheet `main.css` are generated.
See http://www.npmjs.com/package/bootprint-swagger for more information.
 
