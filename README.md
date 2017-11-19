# HyperFool

HyperFool is a Web Debugging Proxy that helps web developers figure out stuff about HTTP(S) traffic between your computer and a backend server. It uses an HTTP proxy / HTTP monitor / Reverse Proxy to show you all the HTTP requests going between, say a web page, and a server.

Fooling around with HTTP requests from a backend is not easy nowadays (11.2017), we've got over-powered tools that most web developers don't use, such as Fiddler or Charles. They do too much, and not one feature is web related. We need something simple, straightforward, and command line extensible, but packaged in a GUI form because we like to see and fool around before we drill down to details and script stuff.

Specifically:
1. The ability to (EASILY, FAST) mock out a backend call.
1.1. Based on an existing call - "Take whatever this specific call just returned, and keep returning the same response until I say otherwise".
1.2. Return variations of a JSON based on regex's / code.
2. The ability to grep (search) through multiple HTTP requests responses / requests (can't do that ATM with Chrome Dev Tools)
3. Save HTTP requests "samples", easily categorize / search through them.
4. ???
5. Profit.
