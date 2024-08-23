# Bricks Heist
![Room Banner](images/room.png)

Howdy, today we are gonna solve the Bricks Heist challenge (easy difficulty) 💯

### Enumeration
Firstly, lets start a `nmap` scan and look at the results:

![Room Banner](images/nmap.png)

The scan shows that there are multiple services running. Lets first check out the website itself and start a `directory bruteforce` in the meanwhile

![Room Banner](images/gob_https.png)

Now we know which directories exist and that we are up against a `wordpress` website. There is this really great tool called `wpscan` which can enumerate a wordpress website with great detail.
Let's fire it up and look at the results for furter enumeration.
