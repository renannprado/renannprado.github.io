+++ 
draft = false
date = 2018-09-24T17:44:12+54:00
title = "Who Am I?"
slug = "whoami" 
tags = ["personal", "renann prado", "blog", "programming", "whoami"]
categories = ["personal", "me", "blog"]
+++

# Tell me about yourself...

Those who have been asked this same question over and over during interviews, please raise their hands :raised_hand:.
To answer this and other questions, let me walk you through `who am I` in a fun, geeky way :smile:, but I really expect anybody to understand as well. I'll also tell some non-tech personal mostly irrelevant stuff :stuck_out_tongue_winking_eye:.

So, let's start...

# Who am I?

`whoami` is a command in *nix systems that shows what user is currently logged into the computer.

`finger` is a command that shows user information.

If we combine them together...

```bash
~#finger $(whoami)

Login: renannprado         			Name: Renann Prado
Directory: /home/GER/hamburg        Shell: [/bin/pt-br, /bin/en, /bin/de, /bin/elvish]
On since 1990 on tty1 from /planet/earth/brazil/sao_paulo
   21 years idle
```

Disclaimer: I'm just starting to learn German, so don't take that seriously haha.

## I've been working for...

`uptime` shows how long the system has been running.

```bash
~#uptime --pretty
up 6 years, 8 months
```

`history` shows your "past" while using the system :stuck_out_tongue_winking_eye:.

```bash
~#history

1   Synchron Informática
2   Amdocs
3   Agile Solutions [Iron Mountain, SAP, Cisco]
4   UOL
5   Avenue Code [eBay]
7   Real State Company
```

The companies in between square brackets I worked as a consultant.

If you want to know more, please go to my [linkedin](https://www.linkedin.com/in/renannprado/?locale=en_US).

## My skills so far are...

`ls` list content of a directory :smile:.

`sed` replaces text in

(in no particular order and not everything)

```bash
~#ls /usr/local/bin/ | sed s/\t/\n/
Java
Kotlin
Golang
Docker
Kubernetes
Microservices
Spring
Jenkins
gRPC
```

## While working I listen to...

I don't like to talk too much about music genres (it's hard to find where your favorite band fits), so I'll just list a handful of bands I listen to.

```bash
~#ls ~/music | sed s/\t/\n/
Iron Maiden
Led Zeppelin
Black Sabbath
Ozzy Osbourne
Dio
Queens of the Stone Age
The Killers
The Vines
Oasis
The Strokes
The Stripes
Arctic Monkeys
Raul Seixas
Lulu Santos
Franz Ferdinand
Rage Against the Machine
Nena
David Guetta
etc
```

Also, I often listen to random noise at https://modarchive.org/ :smile:.

## In my free time I like to...

`ps` shows processes that are currently running.

```bash
~#ps

 1 pts/1    00:00:00 programming
 2 pts/1    00:00:00 go-out-with-friends
 3 pts/1    00:00:00 play-video-games
 4 pts/1    00:00:00 watch-movies-series
 5 pts/1    00:00:00 listen-to-music
 6 pts/1    00:00:00 travel
 7 pts/1    00:00:00 sleep
```

# What you can expect from this blog

- Tips & tricks for linux, java, spring, golang, docker, kubernetes, jenkins, etc
- Discussions around CI/CD, microservices, architecture design, security, etc
    - My objective here is also often not give you an answer, but raise the discission around certain subjects
- Post-mortem about past projects, frustrations, etc
- Experience reports
- News about software development, programming languages, frameworks, etc

That's pretty much everything I could remember, but of course there can be articles about something else as well :smile:. 

Thanks for reading and keep happy coding :smile:.