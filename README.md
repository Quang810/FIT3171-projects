# FIT3171-projects
This is the scenario of the project. This Read Me file does not fully listed all the details of the project, and can only be used as note.

After graduating, you are approached by a startup company which wants to compete with AirBnB in the accommodation and tourism sector. This startup, AirTnT -- short for "AirBnB, tourism and technology" -- intends to provide a more personalised experience compared to AirBnB, while having lower cost than traditional hotels and travel agencies. In the concept of the 'gig economy', AirTnT seeks to engage freelance tour guides and house-sharers.

AirTnT has customers who are identified by a unique customer id. When a customer checks in to an AirTnT facility (i.e. house-share), AirTnT records the customer's first and last names, address, date of birth, current mobile number, one
for identity verification^>, one , and emergency contact number (if they are not already on the system). They also record the date and time of check in. The system needs to maintain a record of all check ins for a particular customer. When a customer checks out, the date and time of their departure for this holiday is recorded.

While in AirTnT, customers are located in a house-share. The house-share is identified by a house-share code and name. AirTnT wishes to record the total number of rooms in each house-share and the number of currently available (empty) rooms. Rooms located in a house-share are assigned a room number within that house - thus, for example, each house has a room number 1. The room's phone number (e.g. if a complimentary VoIP phone is provided by the house's owner) and room type are also recorded. Rooms are classified (their room type) as either fixed or open-plan. Not all rooms are supplied with a complimentary phone.
During a customer's check-in, sometimes they may need to be moved from one room to another, possibly in a different house-share (e.g. if the room is damaged). If this occurs, the date and time the customer is assigned to the new room and/or house-share are recorded (a history of all such assignments during check-in is required). While in AirTnT each customer is assigned one tour guide (identified by a tour guide id) as their main tour guide. A customer's main tour guide may be in charge of many customers. The AirTnT system records each tour guide's first and last names, phone number, and Instagram handle (e.g. @tour_guide). A tour guide may have one or more specialisations (e.g. foodie tours, nature tours, bicycle tours, etc), but not all tour guides who work for AirTnT have a specialisation.

During their check-in, customers are prescribed with activities as part of their tour experience by tour guides. Activities consist of things such as Pub Visits, Bungee Jumping etc.; they also include activities which might be compulsory such as "AirTnT Bicycle Safety Induction" or "Buy AirTnT Travel Insurance". A customer may have activities prescribed by their main tour guide or any other tour guide working for AirTnT. An activity is identified by an activity code. Each activity has a name (such as "Nevis 134m Bungee Jumping") and includes a description of what the activity involves, the time required for the activity and the current standard cost for this activity. When a particular activity is conducted during a customer's check-in, the date and time when the activity is carried out is also recorded. A particular activity is completed before any further activities are run (two of them cannot occur simultaneously). Some activities, such as Bungee Jumping are carried out by other Tourism Providers, more personalised activities may require a tour guide such as AirTnT Safety Induction.

If a tour guide carries out the activity, the tour guide who completes the activity is recorded (the tour guide who completes the activity may be different from the tour guide who prescribes it). Even if a team of tour guides is involved in the activity (e.g. safety induction), only one tour guide (the most senior tour guide in charge) is recorded as completing the activity.

If an activity is performed by a Tourism Provider (e.g. extreme sports facilities), AirTnT does not record the details of the Tourism Provider who completed the activity.

Not all check-ins require an activity to be carried out (e.g. someone just wants to have a 'staycation' and not go anywhere).
Activities may require "extra" items such as stationery, food, USB sticks (for photos), or name badges. Each item held in stock is assigned an item code by AirTnT headquarters. The item description, current stock and price are recorded. For accounting purposes, each item is assigned to a unique cost centre, such as Food/Beverage, Photography, or Stationery. A cost centre is identified by a cost centre code and has a recorded cost centre title and admin team member's name (this is a person at AirTnT headquarters who is in charge of buying stock!). The quantity of each item used in a particular activity is recorded.

Customers are billed for the cost for the activity itself and also any "extra" items which are used as part of an activity. (e.g. "Bike Ride and Picnic" consists of the activity cost itself and food items). The billed charge is based on the activity/item cost at the date and time of the activity.

AirTnT also records details of its housekeeping staff and their allocation to work in the house-share. At any point in time a housekeeping staff member can only work in (be assigned to) one house-share. A housekeeper is identified by a unique numeric housekeeper id. AirTnT also records the staff member's first and last name, as well as an alphanumeric Police Check Certificate code (if available). The initial date a housekeeper is assigned to work in a house-share is recorded. Housekeepers may be moved between house-shares as staffing requirements change. When a housekeeper finishes an allocation with a particular house-share the date they finished is also recorded. Within these changes, a house-keeper may return to a house-share they previously worked in; if they do so, a new allocation is recorded.
