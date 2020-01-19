## intent:affirm
- yes
- yep
- yeah
- indeed
- that's right
- ok
- great
- right, thank you
- correct
- great choice
- sounds really good
- sounds good
- thanks

## intent:goodbye
- bye
- goodbye
- good bye
- stop
- end
- farewell
- Bye bye
- have a good one

## intent:greet
- hey
- howdy
- hey there
- hello
- hello there
- hi
- hi there
- good morning
- good evening
- dear sir

## intent:restaurant_search
- i'm looking for a place to eat
- I want to grab lunch
- I need to have food
- I am searching for a dinner spot
- I am looking for some restaurants in [Delhi](location).
- I am looking for some restaurants in [Bangalore](location)
- show me [chinese](cuisine) restaurants
- show me [chines](cuisine:chinese) restaurants in the [New Delhi](location:Delhi)
- show me a [mexican](cuisine) place in the [centre](location)
- i am looking for an [indian](cuisine)
- search for restaurants
- anywhere in the [west](location)
- I am looking for [asian fusion](cuisine) food
- I am looking a restaurant in [294328](location)
- in [Gurgaon](location)
- [South Indian](cuisine)
- [North Indian](cuisine)
- [Italian](cuisine)
- [Chinese](cuisine:chinese)
- [chinese](cuisine)
- [Lithuania](location)
- Oh, sorry, in [Italy](location)
- in [delhi](location)
- I am looking for some restaurants in [Mumbai](location)
- I am looking for [mexican indian fusion](cuisine)
- can you book a table in [rome](location) in a [moderate](price:mid) price range with [british](cuisine) food for [four](people:4) people
- [central](location) [indian](cuisine) restaurant
- please help me to find restaurants in [pune](location)
- Please find me a restaurantin [bangalore](location)
- [mumbai](location)
- show me restaurants
- please find me [chinese](cuisine) restaurant in [delhi](location)
- can you find me a [chinese](cuisine) restaurant
- [delhi](location)
- please find me a restaurant in [ahmedabad](location)
- please show me a few [italian](cuisine) restaurants in [bangalore](location)
- [less than 300](price:low)
- [300-700](price:mid) range
- [greater than 700](price:high)
- [moderate](price:mid) price range
- can you show me some [cheap](price:low) places to eat
- [>700](price:high)
- [<700](price:mid)
- [<300](price:low)
- [>300](price:mid)
- [in range of 300 to 700](price:mid)
- [not more than 300](price:low)
- [not more than 700](price:mid)
- [mid](price)
- [low](price)
- [high](price)
- I need food
- [Delhi](location)
- in need food
- i'm hungry
- [delhi](location)
- [South Indian](cuisine)
- [high](price)

## intent:email_id
- [email](email)
- my email id is [email](email)
- email - [email](email)
- [prasad.arun88@gmail.com](email)

## intent:stop
- bye

## synonym:4
- four

## synonym:Delhi
- New Delhi

## synonym:bangalore
- Bengaluru

## synonym:chinese
- chines
- Chinese
- Chines

## synonym:high
- greater than 700
- >700

## synonym:low
- less than 300
- cheap
- <300
- not more than 300

## synonym:mid
- moderate
- 300-700
- <700
- >300
- in range of 300 to 700
- not more than 700
- average

## synonym:vegetarian
- veggie
- vegg

## regex:email
- (b[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,}\b)

## regex:greet
- hey[^\s]*

## regex:pincode
- [0-9]{6}
