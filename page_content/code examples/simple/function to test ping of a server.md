This script will run a ping test and echo a message based on the result.

```
f.testping("www.codesimplescript.com")

f.testping{
	if set v.function_passed[0]
		v.ping=s.ping(v.function_passed[0])
		if v.ping > 50
			s.echo("Yikes, the ping test to the server v.function_passed[0] took v.ping MS.")
		else
			s.echo("Hey the server v.function_passed[0] had a ping of v.ping MS. That is great!")
		end
	else
		s.echo("Sorry, we need a server to test")
	end
}
```
