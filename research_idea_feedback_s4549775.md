---
title: Research Idea Feedback
author: Hendrik Werner
date: \today
fontsize: 12pt
geometry: margin=5em
---

-------- ----------------
**For**  Constantin Blach
**From** Hendrik Werner
-------- ----------------

# Introduction
It is good that you go over what AES is, to give a bit of background for your research idea. I think you need to be a little more specific about the Galois-Fields and functions. You want to define new functions that work on number fields. What are the number fields used for, and what do the functions need to do?

> AES is inmiddels al rond tien jaar het grondprincipe van encrypties online.

Why is AES not used offline?

You say it can be useful to use $GF(p)$, where $p$ is prime. How do you know this? Is that not your research question?

The research question is clear, though it is not clear to me how you want to go about answering it. Maybe you could break it down into smaller subquestion a bit more.

You identify a "possible subquestion". When would this question be relevant? Why is it only a possibility that this question needs to be answered?

# Relevance
I think there is some formatting error, as you say an attacker needs $2^1 26$ computation steps to solve the easiest version of AES, but that is only 52. That does not seem very secure. You probably wrote `2^126`, but I think you meant `2^{126}`, which would be much more secure.

Apart from that, I agree with the importance of trying to make one of the most used encryption algorithms in use today even more secure.

# Theoretical Background

> Het meest belangrijke concept voor dit werk is natuurlijk hoe AES in elkaar zit, hoe het werkt en wat de mogelijke problemen zijn. Hier is veel informatie over te vinden, bijvoorbeeld bij een Dozent van de RU, Joan Daemen, die AES mee heeft bedacht.

If it is important, and there is a lot of information about it, then why don't you tell us? Alternatively you could reference a paper, book, or something by Joan Daemen.

> Bovendien is AES het meest gebruikte algoritme in het internet. Daarom is er ook al veel onderzoek na gedaan [...]

So then tell us about it.

This part definitely needs the most work. You tell the reader that something is important, and that there is lots of available research on the topic, but then you do not provide any information. Also you need more literature.

The last paragraph is really good. I think you should rewrite the first three to be more like the last one:

1. Mention the topic.

	> beveiliging van AES

2. What are the main statements of the research?

	> problemen met AES gevonden, die tot nu toe nog niet gevaarlijk zijn, omdat we nog te weinig rekenkracht hebben

3. Provide a reference to the actual resource.

# Method
It is not clear to me what method you want to use. You want to compare the functions you think of to a current implementation of AES. How would you go about doing that?

Security is a quantitative measure, so how do you want to quantify it? You have two different versions of the AES algorithm $A_1, A_2$. Can they be directly compared? If so, then how? Or if you have some input $i$, how can $A_1(i)$ and $A_2(i)$ be compared? Is there some measurable property of $A_k(i)$ that makes it secure?

You mention that you may want to ask some security researchers to find leaks. So do you plan on conducting a survey?

# General
All in all you need to be more specific. In several cases you say things like

> Ik moet dus zelf eigen functies bedenken, die in een GF(p) berekeningen uitvoeren, waardoor het moeilijke wordt om het te achtervolgen.

What are the actual computations that the function needs to do, and what is "het"?

If you specify your research question and method a bit more, I think this is a great topic of huge interest to almost everybody who uses digital encryption.
