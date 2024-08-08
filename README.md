DATA
You are provided with the ipl data from the first season to the 13th season which was
held in 2020. Read and analyze the data properly before loading it into your sql server.

Your first priority is to get 2-3 players with high S.R who have faced at least 500 balls.And
to do that you have to make a list of 10 players you want to bid in the auction so that
when you try to grab them in auction you should not pay the amount greater than you
have in the purse for a particular player.

Now you need to get 2-3 players with good Average who have played more than 2 ipl
seasons. And to do that you have to make a list of 10 players you want to bid in the
auction so that when you try to grab them in auction you should not pay the amount
greater than you have in the purse for a particular player.

Now you need to get 2-3 Hard-hitting players who have scored most runs in boundaries
and have played more the 2 ipl season. To do that you have to make a list of 10 players
you want to bid in the auction so that when you try to grab them in auction you should
not pay the amount greater than you have in the purse for a particular player

Your first priority is to get 2-3 bowlers with good economy who have bowled at least 500
balls in IPL so far.To do that you have to make a list of 10 players you want to bid in the
auction so that when you try to grab them in auction you should not pay the amount
greater than you have in the purse for a particular player.

Now you need to get 2-3 bowlers with the best strike rate and who have bowled at least
500 balls in IPL so far.To do that you have to make a list of 10 players you want to bid in
the auction so that when you try to grab them in auction you should not pay the amount
greater than you have in the purse for a particular player.

Now you need to get 2-3 All_rounders with the best batting as well as bowling strike rate
and who have faced at least 500 balls in IPL so far and have bowled minimum 300
balls.To do that you have to make a list of 10 players you want to bid in the auction so
that when you try to grab them in auction you should not pay the amount greater than
you have in the purse for a particular player.

After doing all that you have the list of all the players you are going to bid in the auction
so create a visual representation in the form of graphs , tables and charts to present in
front of team management before the auction.

Additional Questions for Final Assessment
NOTE:-Deliveries is the table created using the IPL_Ball data whereas the Matches table has been
created using the IPL_Matches data
1. Get the count of cities that have hosted an IPL match
2. Create table deliveries_v02 with all the columns of the table ‘deliveries’ and an additional
column ball_result containing values boundary, dot or other depending on the total_run
(boundary for >= 4, dot for 0 and other for any other number)
(Hint 1 : CASE WHEN statement is used to get condition based results)
(Hint 2: To convert the output data of the select statement into a table, you can use a
subquery. Create table table_name as [entire select statement].
3. Write a query to fetch the total number of boundaries and dot balls from the
deliveries_v02 table.
4. Write a query to fetch the total number of boundaries scored by each team from the
deliveries_v02 table and order it in descending order of the number of boundaries
scored.
5. Write a query to fetch the total number of dot balls bowled by each team and order it in
descending order of the total number of dot balls bowled.
6. Write a query to fetch the total number of dismissals by dismissal kinds where dismissal
kind is not NA
7. Write a query to get the top 5 bowlers who conceded maximum extra runs from the
deliveries table
8. Write a query to create a table named deliveries_v03 with all the columns of
deliveries_v02 table and two additional column (named venue and match_date) of venue
and date from table matches
9. Write a query to fetch the total runs scored for each venue and order it in the descending
order of total runs scored.
10. Write a query to fetch the year-wise total runs scored at Eden Gardens and order it in the
descending order of total runs scored.
