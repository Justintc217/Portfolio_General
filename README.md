# Portfolio_General

Welcome to my portfolio!

I recommend looking at the following projects first:

Nand2Tetrs

ConnectZero

StockProphet

## History of milestones
A long time ago I began my journey as all coders do learning the very basics. Lists? what are those? I began by creating a fibonnaci sequence and found the 10001st prime number. I advanced on to harder and harder math problems such as finding the the value of the first triangle number to have over five hundred divisors.

Then came a day when I started to have my own ideas. I created a changing base function and then had the bold idea of creating a rock paper scisors game. These were lofty aspirations for a newcomer like myself. But if I can build rock paper scissors AI then why not build a learning AI?

So I set out to build an AI that learns chopsticks as you play it. You can see the code in the portfolio under cct. I didn't even bother creating a regular preprogrammed AI. Looking back, my expectations were ridiculous, but I'm also glad they were. So I naively tried, allowing the AI to play against itself and create a database of moves and states. If it won it saved the states and moves of the player that won. I don't remember it performing very well though I recall that it did learn to make certain good moves more frequently after it learned from playing against me.

Fast forward to my last year at my university which took my python skills to the next level. I used python briefly in a class on cosmology. Homework was typically related to graphing the end of the universe or warping space. I went through a phase of creating image manipulation programs. You've never seen Vladimir Putin swimming with dolphins inside a rose floating above a city now have you? I finally had a brief course on python for astronomy which gave me a much needed overview of the basics. Throughout the year I also did research and began to use python for program analysis. My friend and I built the ugliest monster of code for our research that the world has ever beheld, and suprisingly it worked and was quite useful. I initialized my own project as well to streamline the research as well. Some of my teammates even used my program to speed up their own research.

There is always a lull at some point, but it didn't last for long. All I needed was something to pique my interest. Neural networks. I had always been fascinated with intelligence and thought itself. I remember being amazed when I first learned about neural networks many years ago. I never thought I would one day work on them, but I think I really wanted to. Anyway, I watched several youtube videos about how they work and set out to build one of my own. It wasn't very clear how to do that, particularly the back propogation part. I finally found a decent article that went through the math and I pieced together my own formula. With this I built my very own 3-layer neural network with back-propogation to play tic tac toe. Again I had high expectations, and this time it really did kind of work. It could beat a rng player at 70-80% of the time and it would slowly adapt over time. But it still wasn't a formidable opponent. 

I worked on a few small projects after this. most notably I built a star simulator using PYGAME that simulates the movement of multiple stars with 2D gravity. It was pretty cool. I also built a game in unity and picked up C#. It was fun for 5 minutes. You and your opponent moved around as balls, dodged objects and tried to knock each other off the stage. Also you were gravitationally attracted to each other. The most impressive feat was actually just getting the angled camera to adjust while playing.

Later, I learned about TensorFlow and Keras. I figured if I already understand the fundamentals behind neural networks then why not just use a pre-made package to speed things up. I learned how to work with Keras and rebuilt the tic tac toe game from scratch. It took a lot of messing around and tweaking but eventually I got an AI that learned entirely from self-play and played perfectly against an rng 100-0. It even taught me another double bind move I hadn't thought of before.

From there I dived head on into a much bigger project. predicting stocks with AI. I knew it wouldn't be easy and I gave it quite a shot spending months researching AI, learning about the stock market, gathering data, cleaning data, transforming data into technical indicators, and testing verious neural networks. I learned an incredible amount. I did my best to challenge my assumptions and when it was working I tried to figure out if I might have made an error or possibly introduced some bias. I knew investing with an AI was risky and I was going to treat this project with the utmost fidelity. It's unclear whether it was successful. It seems like it could learn patterns to a degree but probably not high enough to be profitable relative to a buy and hold strategy. In the meantime I've decided to put the project on the back burner while I run programs to scrap free one week data online.

So what next. I shot for the moon and learned that its not easy to reach. I decided to work on something I had wanted to do for a long time. Since I was a kid I enjoyed playing connect four and was quite good at it. I had previously built a preprogrammed AI that would search about 5 moves ahead and used a point system to guess which move was best. It was quite good and even beat some of my friends but it wasn't good enough. I wanted an AI, a real artificial intelligence to learn from self play starting from scratch. Following some research into AlphaZero (the Google Deepmind AI program that could beat the best players of Chess, Shogi, and Go) I decided to embark on my latest project: ConnectZero...
