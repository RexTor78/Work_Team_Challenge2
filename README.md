# Work_Team_Challenge2
In this project we try to define basic ideas to explain more tidy as posible the structure of diagram Table.
Determining specifications_id into main Restaurant_list and a new table Food specifications with a specification Key how a Primary Key, we solve the problem at first starts of diagram had with a cuisine type or menu type, now we can filter more easy the restaurant with a lot of specifications.
We made some similar with transactions table, that makes more usable and traceable the relashionship between restaurants and customers.
About the questions of the Challenge:
# Which parts of the city have the most restaurants per sq km?
We can Filter with a query  by district including restaurant_id and we can detect the more cluttered areas easy.
# Where can a vegan burger restaurant be found, with an opening time filter...  e
# eg. customer wants to visit on thursday at 6pm?
For this situation we can do a join using information of tables 'restaurant details', 'food specifications' and
'restaurant list'and we solve quickly this situation.
# How many specified cuisine (eg. Vietnamese) restaurants are there in the city?
Filtering information by cuisine_type in the Restaurant List we have this information at moment.
# U: which restaurants are the best for big groups/parties?
You just need to filter by capacity in the Restaurant Detail table.
