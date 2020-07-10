## happy path
* greet
  - utter_greet
  - utter_divide
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
  - utter_divide
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

## query kgp long
* greet
  - utter_greet
  - utter_divide
* query_intro
  - utter_ask_query
* querykgp
  - respond_querykgp

## query cq intro long
* greet
  - utter_greet
  - utter_divide
* query_intro
  - utter_ask_query
* querycq
  - respond_querycq
  - utter_further_query

## fallback story
* out_of_scope
  - action_default_fallback
