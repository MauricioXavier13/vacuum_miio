# vacuum_miio
Cards and scripts to clean up your house. Multi floor availables either.

Clean your home with your Xiaomi/Roborock vacuum
You can use this configuration to multi-map/multi-floor setup or with a single one

Pre-requisites:
- Integrations:
  - Xiaomi Miio Vacuum | https://www.home-assistant.io/integrations/xiaomi_miio

- HACS Custom-Cards:
  - custom:button-card | https://github.com/custom-cards/button-card
  - custom:bar-card | https://github.com/custom-cards/bar-card
  - custom:text-divider-row | https://github.com/iantrich/text-divider-row
  - custom:paper-buttons-row | https://github.com/jcwillox/lovelace-paper-buttons-row
  - custom:text-element | https://github.com/custom-cards/text-element
  - custom:swipe-card | https://github.com/bramkragten/swipe-card
  - card-tools | https://github.com/thomasloven/lovelace-card-tools

# Discover your segments params:
  Use miio command-line tool:
  
    miiocli vacuum --ip <ip of the vacuum> --token <your vacuum token> get_room_mapping
    Bash
  - https://www.home-assistant.io/integrations/xiaomi_miio#retrieving-room-numbers
  
  You can also testing it or discovered it by sending random params with segment clean service and see what rooms is painted in mi home app.


# main_controls_card

![image](https://user-images.githubusercontent.com/74264882/112759735-405fb500-8fec-11eb-84e6-82fe5dc94d9b.png)




# floor_room_selection_card

<img width="271" alt="Manual Room Clean" src="https://user-images.githubusercontent.com/74264882/112748406-45ecd900-8fb3-11eb-9347-2748a5b65f62.png">

# Clean Profile 1

![image](https://user-images.githubusercontent.com/74264882/112759749-58cfcf80-8fec-11eb-8ff0-069de67cb66c.png)

# Clean Profile 2

![image](https://user-images.githubusercontent.com/74264882/112759767-6c7b3600-8fec-11eb-962b-7c632e59cbae.png)

# Clean Profile 3

![image](https://user-images.githubusercontent.com/74264882/112759780-77ce6180-8fec-11eb-862d-c5813599e8a5.png)

# Maintenance Card

![image](https://user-images.githubusercontent.com/74264882/112759792-8583e700-8fec-11eb-8fd5-32f21d98d744.png)

Instructions step by step inside each card/Configuration file

![Screenshot_20210326-211007](https://user-images.githubusercontent.com/74264882/112693217-29985180-8e78-11eb-92e5-6ae0ec4c7024.jpg)
![Screenshot_20210326-211027](https://user-images.githubusercontent.com/74264882/112693236-32892300-8e78-11eb-9ba3-c1e965c91493.jpg)
