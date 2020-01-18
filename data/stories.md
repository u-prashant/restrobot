## complete path with email
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
    - utter_ask_mail
* affirm
    - utter_ask_email_id
* email_id{"email_id": abc@xyz.com}
    - slot{"email_id": abc@xyz.com}
    - action_send_email
    - utter_goodby
    - export
    
    ## complete path with email 1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"price": "<300"}
    - slot{"price": "low"}  
    - action_search_restaurants
    - utter_ask_mail
* affirm
    - utter_ask_email_id
* email_id{"email_id": abc@xyz.com}
    - slot{"email_id": abc@xyz.com}
    - action_send_email
    - utter_goodby
    - export

    ## complete path with email 2
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Mumbai"}
    - slot{"location": "Mumbai"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"price": ">700"}
    - slot{"price": "high"}  
    - action_search_restaurants
    - utter_ask_mail
* affirm
    - utter_ask_email_id
* email_id{"email_id": abc@xyz.com}
    - slot{"email_id": abc@xyz.com}
    - action_send_email
    - utter_goodby
    - export

    ## complete path with email 3
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Hyderabad"}
    - slot{"location": "Hyderabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Chinese"}
    - slot{"cuisine": "Chinese"}
    - utter_ask_budget
* restaurant_search{"price": "300 to 700"}
    - slot{"price": "mid"}  
    - action_search_restaurants
    - utter_ask_mail
* affirm
    - utter_ask_email_id
* email_id{"email_id": abc@xyz.com}
    - slot{"email_id": abc@xyz.com}
    - action_send_email
    - utter_goodby
    - export
    
    ## complete path without email 
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Hyderabad"}
    - slot{"location": "Hyderabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Chinese"}
    - slot{"cuisine": "Chinese"}
    - utter_ask_budget
* restaurant_search{"price": "300 to 700"}
    - slot{"price": "mid"}  
    - action_search_restaurants
    - utter_goodby
    - export
    
    ## complete path without email 1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Mumbai"}
    - slot{"location": "Mumbai"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"price": ">700"}
    - slot{"price": "high"}  
    - action_search_restaurants
    - utter_goodby
    - export
    
    ## complete path with email 2
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"price": "<300"}
    - slot{"price": "low"}  
    - action_search_restaurants
    - utter_goodby
    - export
    
## complete path without email 3
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
    - utter_goodby
    - export 

## complete path with email without greet
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
    - utter_ask_mail
* affirm
    - utter_ask_email_id
* email_id{"email_id": abc@xyz.com}
    - slot{"email_id": abc@xyz.com}
    - action_send_email
    - utter_goodby
    - export
    
    ## complete path with email 1 without greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"price": "<300"}
    - slot{"price": "low"}  
    - action_search_restaurants
    - utter_ask_mail
* affirm
    - utter_ask_email_id
* email_id{"email_id": abc@xyz.com}
    - slot{"email_id": abc@xyz.com}
    - action_send_email
    - utter_goodby
    - export

    ## complete path with email 2 without greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Mumbai"}
    - slot{"location": "Mumbai"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"price": ">700"}
    - slot{"price": "high"}  
    - action_search_restaurants
    - utter_ask_mail
* affirm
    - utter_ask_email_id
* email_id{"email_id": abc@xyz.com}
    - slot{"email_id": abc@xyz.com}
    - action_send_email
    - utter_goodby
    - export

    ## complete path with email 3 without greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Hyderabad"}
    - slot{"location": "Hyderabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Chinese"}
    - slot{"cuisine": "Chinese"}
    - utter_ask_budget
* restaurant_search{"price": "300 to 700"}
    - slot{"price": "mid"}  
    - action_search_restaurants
    - utter_ask_mail
* affirm
    - utter_ask_email_id
* email_id{"email_id": abc@xyz.com}
    - slot{"email_id": abc@xyz.com}
    - action_send_email
    - utter_goodby
    - export
    
    ## complete path without email without greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Hyderabad"}
    - slot{"location": "Hyderabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Chinese"}
    - slot{"cuisine": "Chinese"}
    - utter_ask_budget
* restaurant_search{"price": "300 to 700"}
    - slot{"price": "mid"}  
    - action_search_restaurants
    - utter_goodby
    - export
    
    ## complete path without email 1 without greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Mumbai"}
    - slot{"location": "Mumbai"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"price": ">700"}
    - slot{"price": "high"}  
    - action_search_restaurants
    - utter_goodby
    - export
    
    ## complete path with email 2 without greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"price": "<300"}
    - slot{"price": "low"}  
    - action_search_restaurants
    - utter_goodby
    - export
    
## complete path without email 3 without greet
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
    - utter_goodby
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
    
## complete path 5
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
* restaurant_search{"price": "more than 700"}
    - slot{"price": "high"}
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
