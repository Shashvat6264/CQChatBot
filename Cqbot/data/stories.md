## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
  - utter_divide
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## chitchat
* greet
  - utter_greet
  - utter_divide
* chitchat_intro
  - utter_ask_name
* chitchat_name
  - utter_name_greet
  - utter_ask_weather
* chitchat_weather
  - utter_happy

## query kgp intro long
* greet
  - utter_greet
  - utter_divide
* query_intro
  - utter_ask_query
* query_kgp_intro
  - utter_query_kgp_intro
  - utter_further_query

## query kgp clubs long
* greet
  - utter_greet
  - utter_divide
* query_intro
  - utter_ask_query
* query_kgp_clubs
  - utter_query_kgp_clubs
  - utter_further_query

## query kgp location long
* greet
  - utter_greet
  - utter_divide
* query_intro
  - utter_ask_query
* query_kgp_location
  - utter_query_kgp_location
  - utter_further_query

## query cq intro long
* greet
  - utter_greet
  - utter_divide
* query_intro
  - utter_ask_query
* query_cq_intro
  - utter_query_cq_intro
  - utter_further_query

## query cq proc long
* greet
  - utter_greet
  - utter_divide
* query_intro
  - utter_ask_query
* query_cq_proc
  - utter_query_cq_proc
  - utter_further_query

## query cq events long
* greet
  - utter_greet
  - utter_divide
* query_intro
  - utter_ask_query
* query_cq_events
  - utter_query_cq_events
  - utter_further_query

<!-- ## query cq contact long
* greet
  - utter_greet
  - utter_divide
* query_intro
  - utter_ask_query
* query_cq_contact
  - utter_query_cq_contact
  - utter_further_query -->