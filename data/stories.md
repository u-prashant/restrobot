## complete path
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"price": "<300"}
    - slot{"price": "low"}  
    - action_search_restaurants
    - utter_goodbye
    - export

## location specified
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"price": ">700"}
    - slot{"price": "high"}
    - action_search_restaurants
* affirm
    - utter_goodbye
    - export

## complete path 2
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
* restaurant_search{"price": "300 to 700"}
    - slot{"price": "mid"}
    - action_search_restaurants
    - utter_goodbye

## complete path 3
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "italy"}
    - slot{"location": "italy"}
	- utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
* restaurant_search{"price": "not more than 300"}
    - slot{"price": "low"}
    - action_search_restaurants
* goodbye
    - utter_goodbye

## complete path 4
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
* restaurant_search{"price": "not more than 700"}
    - slot{"price": "mid"}
    - action_search_restaurants
    - slot{"location": "delhi"}
    - export
    
## happy_path
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "mumbai", "price": "300 to 500"}
    - slot{"cuisine": "italian"}
    - slot{"location": "mumbai"}
    - slot{"price": "mid"}
    - action_search_restaurants
    - slot{"location": "mumbai"}
* affirm
    - utter_goodbye
