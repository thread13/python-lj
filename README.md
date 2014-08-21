# Python LiveJournal #
**A python realization of LiveJournal (LJ) API **
A full description of the protocol can be found at: 
http://www.livejournal.com/doc/server/ljp.csp.xml-rpc.protocol.html

## Installation ##
Just type (pip integration is work in progress):

    pip install lj
    
## Usage ##


    import lj
    client.LJServer("Python-Blog3/1.0", "http://daniil-r.ru/bots.html; i@daniil-r.ru")
        serv.login("yourusername", "yourpassword")
        serv.postevent("Awesome post", "Awesome subject", props={"taglist": "githgub,livejournal"})