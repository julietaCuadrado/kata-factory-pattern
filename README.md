<h1>Why another TDD Kata</h1>
I dont know you, bus as for me, to really enjoy katas's and patterns, I've got to make them with my bare hands

Factory and Abstract Factory Creational Patterns are natural and straight concepts to understand, but anyway I wanted to triple-check that I really understand all that they have to offer.

So, I made up this kata for me.

<h1>The Katja Kata</h1>
You are Katja TheMostlyGrey, a 75-year-old heroine, and you have decided to run a goodbye ride before your definitive attemp of settling down.
From your 1st attemp you have a grandson who has raised in the art of I-dont-know-what-im-forging. His artist name is UncertainTom and he is able of making ancient weapons. Ancient wwapons as a raw concept, because he is not able of predicting what is going to be forged once the proccess is ongoing

There are three well-know categories of ancient weapons, and then it is the fourth: the Unkown-Ancient-Thing, as UncertaingTom is able of conjuring things from other time / reality, so you can end you can endup with really weird unkown stuff in your hands.
Categories are:  Axes, Swords, Maces


Well, conjuring stuff is a bit tired, but also you beloved grandson is pretty depressed, so he is not able to conjure more than three things in each session.

Now you are with him in front of the KinderSurpriseForgeOfFateAndThings.

What is your initial set of weapons for your ride?

*****************

<h1>HOW TO USE</h1>

<h2>Step 1 - Docker</h2>

Yes, its dockerized! 

<code>$ docker-compose up -d</code>

<h2>Step 2 - Do vendor </h2>
As its dockerized, the one generating the vendor should be the docker, ofc

<code>$ docker exec -ti factory_php_1composer dumpautoload</code>

<h2>Step 3 - Do test </h2>

This is a TDD Kata - so test is the most important point of this kata, so you want to read and run the tests

<code>$ docker exec -ti factory_php_1 ./vendor/bin/phpunit --bootstrap vendor/autoload.php tests</code>


<h1>TO DO</h1>

Choose a consistent coding style



