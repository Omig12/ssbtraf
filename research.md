# Scuttlebutt timing attack

Scuttlebutt is a decentralized peer to peer network which offers a way for it's user's to send end to end encrypted private messages. We belive that by analysing the size, frecuency and structure of the hash produced by this messages we might be able to extract some useful information about the sender and the reciever of such private messages. 

**Timing** is a tecnique we can employ, to oberseve the streams of messeges and infere some gossip between some specific clients.

## What are Fourier Transforms anyway?

It's a series of discrete adaptations of the complex Fourier Series, that allow us to observe changes on a signal over a continuous amount of time (or functions of the frequencies of participation of certain elements over time). This is done by splitting the continuous time signal into discrete intervals, and then treating the discrete interval as a group of frequency measurements of each type of change, resulting in series of frequency measurements over the length of the signal, effectively decomposing the signal into the frequency of its components over time.

## The approach:

The approach we implement stems from a disccussion found on [Stack Overflow]() which suggest that it might be possible to figure out who the recipient of a private message in ScuttleButt is by establishing a correllation of the behaviour of two participants within a Fourier Time Series.

### Possible Improvements:
* Utilize machine learning to create models that best fit possible interactions between users. Matching f(userID)->(userID) by observing 
(userID, msgTimestamp) ~ (userID, msgTimestamp).
