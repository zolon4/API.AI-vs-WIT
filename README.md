#API.AI Write Up

In order to get the best experience, I built the same bot(the one that remembers stuff) two different times. First using wit, second using api.ai.

###Api.AI has default domains

Domains are predefined knowledge packages. You can make your agent understand thousands of things by flipping a switch. The Example shown to the left are the small talk domain. With smalltalk, you can make your bot respond to things like “hey” so you can work on the other functions of the bot.

![alt text](https://i.imgur.com/5AkWEro.png "Domains ex")



###Pros

* Domains
    * Predefined
    * Built in knowledge
        * They don't know everything but they know a lot
    * Easy to use
        * The console is really good and
    * The small talk domain is customizable 
        * This means you can change some of their predefined responses
        * Example
        * ![alt text](https://i.imgur.com/p3CxQCl.png "Domains ex")
    * When you ask for the news you get a big paragraph with the latest stories
    * A lot of the build in domains are pretty accurate 
        * They allow you to build around their domains 
        * An example would be a booking app where you tell the bot to book a hotel in a location for a certain date
            * The response is the location and both the starting and ending dates

###Cons

* Domains
    * They don't know everything 
    * Costs $111 to use them out of their console
    * Some of the domains only get you the intent
        * Since you have to pay to test, you only know if you will get the intent, you don't know if it will work for what you want to do
* Entities are way more confusing that wit
* Doesn't learn as well as wit

###API.AI vs Wit

####[Wit](https://wit.ai)

* About
    * Natural Language 
    * Input Parser
    * Bot engine 
    * Lightweight
* Basically you get what you need from it
* You can tell it what to give you and it performs
* Has a few built in Entities
    * many of which are the same as api.ai like weather and location
* FREE
* Learns really well
* Allows you to set your own entities easily so you always get what you want and not anything extra
* Also finds multiple intents in messages

* * *

####[Api.ai](https://api.ai)

* About
    * Voice Recognition 
    * Text-to-Speech
    * Natural Language Understanding
    *  Conversational Management 
    * Fulfillment.
* Seems a bit more complex than Wit.
    * For this use case (a bot that remembers stuff) its a bit overkill
* Could be an error on my part but the entities for api.ai are way harder to set than wit.
* Has a lot of bells and whistles that you have to pay for to use outside of their console
    * Which work well but you can easily set them up yourself and forgo the money you have to pay
* Learning is really weird
    * Its not grabbing the right words. Ive been plugging things in to train it but it still has trouble and sends back the default error message
* [Example video](https://www.youtube.com/watch?v=oz5Su105p5Y&feature=youtu.be)

* Gets caught on some things but is learning from others
* The default domains you pay for would be beneficial if you want something fast but the ones you make yourself, in my experience, take a while to learn



