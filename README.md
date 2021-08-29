# Apriori-Algorithm-On-App-Usage-Data
Apriori Algorithm Intuition:

What are the three essential relations between the support, confidence and lift?

Given two Apps A1 and A2, here are the three essential relations to remember:

Relation between the support and the confidence:
confidence(A1 -> A2) =support(A1,A2)/support(A1)

Relation between the lift and the support:
lift(A1 -> A2) =support(A1,A2)/support(A1)*support(A2)

Relation between the lift and the confidence (consequence of the two previous equations):
lift(A1 -> A2) =confidence(A1 -> A2)/support(A2)

Data:
	AppName
0 	Whatsapp,Youtube,Meet,Amazon,Instagram
1 	Discord,Netflix,Instagram,Spotify
2 	Whatsapp,Youtube,Zoom,Netflix,Facebook,SnapCha...
3 	Whatsapp,Youtube,Meet
4 	Whatsapp,Youtube,Meet,Netflix,Instagram
5 	Youtube,Meet,SnapChat,Instagram,Spotify
6 	Whatsapp,Youtube,Meet,SnapChat,Instagram
7 	Whatsapp,Youtube,Zoom,Netflix,SnapChat,Instagram
8 	Whatsapp,Youtube,Meet,Netflix,Facebook,Amazon ...
9 	Whatsapp,Youtube,Meet,Netflix,Instagram
10 	Whatsapp,Youtube,SnapChat,Instagram,Spotify
11 	Whatsapp,Youtube,Twitter,Pinterest,Spotify
12 	Whatsapp,Youtube,Twitter,Meet,Instagram
13 	Whatsapp,Youtube,Meet,Netflix,Instagram
14 	Whatsapp,Youtube,Facebook,Amazon,Instagram
15 	Whatsapp,Youtube,Twitter,Meet,Spotify
16 	Whatsapp,Youtube,Netflix,SnapChat,Instagram
17 	Whatsapp,Youtube,Meet,Facebook,Wynk
18 	Whatsapp,Youtube,Discord,Meet
19 	Whatsapp,Youtube,Twitter
20 	Whatsapp,Youtube,Zoom,Hotstar,Amazon
21 	Whatsapp,Youtube,Meet,Spotify
22 	Whatsapp,Youtube,Meet,Amazon Prime,Instagram
23 	Whatsapp,Youtube,Facebook,Instagram
24 	Youtube,Meet,SnapChat,Amazon,Instagram
25 	Whatsapp,Youtube,Pinterest,Amazon,Instagram
26 	Whatsapp,Youtube,Twitter,Meet,Zoom,Facebook
27 	Whatsapp,Youtube,Meet,Amazon Prime,Instagram
28 	Whatsapp,Youtube,Meet,SnapChat,Amazon,Amazon P...
29 	Whatsapp,Youtube,Meet,Amazon,Instagram
30 	Meet,SnapChat,Instagram,Spotify
