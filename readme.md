# p2p on the web

James Halliday (substack)

https://bits.coop - worker-owned software consulting cooperative

follow me on secure scuttlebutt
(p2p decentralized social database):

@9nTgtYmvW4HID6ayt6Icwc8WZxdifx5SlSKKIX/X/1g=.ed25519

* ssb://%o6ht9BgxteQXSmvqiaSXwDkLUKw8Cq5x28eY296qlRg=.sha256
* /ipfs/QmfLVT9dwJUTvB1pV4SuixLm6pGb1GSjiRHgqKvs3EXmoT
* https://github.com/substack/devit-2017-notes (legacy web)

---
# /¡\ warning /!\

later on in this talk there will be
loud noises and moving images

---
# the web

an open pltform where anyone can publish?

no.

---
# dimensions of access

* access to a personal computer
* access to electricity and internet access
* ability to perceive sound, color, text size, contrast
* device capabilities

these may vary over time or be situational

---
# barriers to participation on the web

* domain names cost money (and access to finance)
* servers and hosting cost money
* requires technical skill

web hosting demands perpetual rents!

---
# platforms

facebook, twitter, etc

* providers own the infrastructure and domain name
* providers decide features on users behalf

---
# power dyanamics of web server technology

* servers - private property (DNS record, hardware)
* clients - subject to the whims of server operators

the default web architecture perpetuates:

* hierarchy
* paternalism
* consumer/producer relationship

---
# strange effects of centralization: distance

with centralized platforms:

to send a file across the room,
you might send the data around the planet

---
# centralized downsides

* aquihired / shuts down
* runs out of VC bubble money
* changes their API
* hikes their prices
* you could use too much data
* walled garden / censorship
* data given to government/advertisers
* only as good as your internet uplink

then your app will break
or else you or users will be sad!

---
# things the web is good at

* links
* universal VM
* access to system peripherals: audio, gpu, network, bluetooth

---
# how can we build a better web?

* more equal
* more democratic
* more suitable for real world situations

---
# a cooperative alternative

* peers provide the infrastructure for each other
* no gatekeepers
* users control the network topology

cooperative peer production

---
# clients and servers

from each according to their ability,
to each according to their need

---
# clients in p2p

* everything is a client!
* even servers are clients

---
# servers in p2p

* high availability clients
* not special in any way

---
# hypothetical web delivery alternative

a package manager lives in a service worker

* get the data from p2p networks
* users can configure when they upgrade
* users can configure where/who they upgrade from

---
# two kinds of p2p

* perpetuate scarcity (cryptocurrencies)
* perpetuate abundance (bittorrent, etc)

---
# cooperative peer to peer

services that nobody can own

---
# cooperative peer to peer

How do you make money on cooperative p2p?

You don't.

Instead, you create abundance for everyone.

(Unfortunately the ability to do this has class dimensions.)

Maybe you can get some grants or something.

---
# cooperative peer to peer

* secure scuttlebutt
* bitorrent
* ipfs
* dat/hyper{drive,core}
* hyperlog

---
# peer to peer techniques

* DHT - look up keys in a global hash table
* kappa architecture - logs as a single source of truth
* gossip network - share information with peers, like rumors or a virus

---
# namespaces

* namespaces are private property (not cooperative)
* cryptographic hashes are public property

---
# "identities"

* public keys + signatures
* use libsodium/nacl (npm install chloride)
* names are what your friends call you

---
# gossip architecture

secure scuttlebutt network model:

* when you follow somebody's feed, you replicate their data
* your followers help to host your content

* random connections are a good place to start

---
# kappa architecture

* log - as the single source of truth for data
* materialized views - build indexes completely from the log
* merkle DAGs (like git!) for logs

---
# peer production of technology

another dimension of power:

technologists or businesses decide how technology should work

usually to suit their own needs or interests

---
# tiny modules

* do one thing well
* easy to learn, replace, and repair
* ecosystem of cooperative peer production

---
# tiny modules

if programmer X uses a module written by programmer Y
and programmer Y uses a module written by programmer X

X <---> Y

Now you have a reciprocal loop of mutual cooperation!

---
# demo: p2p social network on the web!

some tiny modules:

* level-browserify
* webrtc-swarm
* hyperlog
* yo-yo

