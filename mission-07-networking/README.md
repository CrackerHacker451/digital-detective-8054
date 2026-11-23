# Mission 7 — How computers communicate
## 1. Task / objective
Explain network concepts, perform privacy-safe connectivity/DNS observations, and describe website loading.
## 2. Work completed
### Task 7.1 — Concepts
| Concept | Explanation | Example |
|---|---|---|
| LAN | A network covering a small local area such as a home or lab. | Devices sharing a home router |
| MAN | A network covering a city or a large campus. | A metropolitan education network |
| WAN | A network connecting large geographical areas. | The internet |
| DNS | Translates a domain name into a network address. | `example.com` to an IP address |
| Router | Connects networks and forwards data between them. | Home router between devices and ISP |
| Protocol | A set of rules for communicating. | HTTP/HTTPS and TCP/IP |
| Packet switching | Divides data into packets that can travel through network routes. | A webpage response sent as many packets |
| Client-server | A client requests a service and a server provides it. | Browser requesting a web page |

### Task 7.2 — Observations
A connectivity test helps check whether a route to a public destination responds. A DNS lookup displays the address records associated with a domain name. DNS lets a browser find network addresses from a memorable website name rather than requiring a user to know an address directly.

Privacy-safe observation: `ping` reached `example.com`, and DNS returned public address records. Public IP addresses and local network names are intentionally not included.

### Task 7.3 — Opening a website
1. The browser is the client and creates an HTTPS request for the website.
2. The browser asks DNS for the domain's server address.
3. DNS responds with an address; no human-readable website name is sent as the only network routing information.
4. The request travels through the local network and router toward the server using Internet protocols.
5. A router or multiple routers forward packets toward the destination network.
6. The server receives the request, processes it and sends response packets.
7. The browser receives packets, follows protocol rules, assembles the response and displays the page.

## 3. Commands / tools used
`ping example.com`, `dig example.com` or a DNS lookup tool, and a browser.
## 4. My understanding
Networks exchange information using addresses and rules. Routers move traffic, DNS resolves names, protocols establish communication behavior, and packet switching allows data to be carried in manageable units.
## 5. Difficulties faced
No major difficulties.
## 6. How I resolved them
Not applicable.
## 7. Evidence / files
Privacy-safe command observations and the network table in this README. No local IP or Wi-Fi details are included.
## 8. Commit details
Commit: `Explain networking concepts and website communication`; pushed to GitHub.
