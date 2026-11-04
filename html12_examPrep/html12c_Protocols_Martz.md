**Before you start:** rename this file to `html12c_Protocols_lastname.md`, using your own last name. Watch videos 7–11 and use **Part 3** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:** Cody M

---

# Task 12c — Internet Protocols

Type your answers on the blank line under each **Answer:**, or fill in the tables. Explain in your own words where a question asks why.

## 1. Which protocol?

**a.** For each situation, write the protocol that does the job: **HTTP, HTTPS, FTP, SFTP, DNS, TCP, or IP**.

| Situation | Protocol |
|---|---|
| You type `example.com` and your computer needs its IP address | IP |
| You upload your website's files to a web host | TCP |
| You log in to your bank's website | HTTPS |
| A server sends a plain web page to your browser | HTTP |
| Packet 7 of a file never arrived, so it gets sent again | TCP |
| Each packet needs an address so it reaches the right computer | DNS |
| You upload files to a server and want the transfer encrypted | STCP |

**b.** In your own words, what is a protocol? Give an example from everyday life of two people following the same "rules" so they understand each other.

**Answer:** A protocol is a set of guidelines computers follow to ensure compatible communication. One example is police officers speaking in radio codes (i.e. 10-4) to communicate efficiently through the radio.


## 2. IP addresses and DNS

**c.** Which of these are valid IPv4 addresses? Write **Valid** or **Not valid**, and give the reason for any that are not.

| Address | Valid? | Reason |
|---|---|---|
| `192.168.0.1` | Valid | 4 numbers exist within the possible range |
| `10.0.300.5` | Invalid | Numbers only go up to 255, so 300 is impossible |
| `172.16.4` | Invalid | IP addresses consist of 4 numbers. This one only has 3 |
| `8.8.8.8` | Valid | 4 numbers exist within the possible range |

**d.** DNS is called the internet's "phone book." Explain why that comparison makes sense.

**Answer:** DNS contains the names for people's IP addresses, much like a phone book contains the names for people's phone numbers.


## 3. Packets

**e.** A photo is sent across the internet. It is split into 20 packets, and they take different paths. Packet 12 arrives last and packet 5 never arrives at all. Explain what happens, and which protocol handles it.

**Answer:** A request is sent back to the server to send packet 5 again. TCP, the protocol behind it, also reorders everything to make sure the data is preserved.


## 4. HTTP and HTTPS

**f.** Write the status code for each situation.

| Situation | Status code |
|---|---|
| The page loaded fine | 200 |
| You typed a page name that does not exist | 404 |
| Something broke on the server | 500 |

**g.** A website has a login form but uses `http://` instead of `https://`. What is the risk? What would the browser show?

**Answer:** An http:// URL would cause the browser to show a warning, since data sent through that URL will not be secure.


**h.** What do SSL and TLS have to do with HTTPS? Which one is newer?

**Answer:** SSL/TLS are encryption methods used by HTTPS. TLS is the newer one.


## 5. FTP

**i.** What is FTP used for in web design? Why is SFTP a better choice than plain FTP?

**Answer:** FTP is called "File Transfer Protocol", and is used to move files between a computer and a server. In web design, it's how a website is published. SFTP is a better option because it encrypts data.


## 6. The parts of a URL

**j.** Break each URL into its parts.

`https://www.medinapets.com/dogs/grooming.html`

| Part | Answer |
|---|---|
| Protocol | https:// |
| Subdomain | www |
| Domain name | medinapets |
| Top-level domain (TLD) | .com |
| Path | /dogs/ |
| File name | grooming.html |

`http://library.example.edu/books/index.html`

| Part | Answer |
|---|---|
| Protocol | http:// |
| Subdomain | library |
| Domain name | example |
| Top-level domain (TLD) | .edu |
| Path | /books/ |
| File name | index.html |

**k.** Is the second URL secure? How can you tell?

**Answer:** The second URL is NOT secure since the protocol is HTTP, not HTTPS.


## 7. Putting it together

**l.** These steps happen when you type a URL and press Enter, but they are out of order. Number them 1–5.

| Order | Step |
|---|---|
| 5 | The browser puts the packets back together and draws the page |
| 1 | DNS finds the server's IP address |
| 3 | The browser sends an HTTPS request for the page |
| 2 | TCP/IP opens a connection to the server |
| 4 | The server sends back the HTML, CSS, and images in packets |

**m.** FTP is not one of those steps. When does FTP get used instead?

**Answer:**


## Closing 12c — Vocabulary

| Term | Your definition |
|---|---|
| Protocol | Rules computers use to communicate |
| IP address | A number used to identity a device on a network |
| DNS | Domain Name System - turns domains into IPs |
| Packet | A section of data sent to or from a server |
| HTTPS | Protocol for sending encrypted web pages |
| URL | The full address for a web page |