1. Find total number of common friends for any possible friend pairs. The key idea is that if two people are friend then they have a lot of mutual/common friends.
Write a spark script to find total number of common friends for any possible friend pairs. The key idea is that if two people are friend then they have a lot of mutual/common friends.

Input files:
1. soc-LiveJournal1Adj.txt
The input contains the adjacency list and has multiple lines in the following format: <User><TAB><Friends>
Here, <User> is a unique integer ID corresponding to a unique user and <Friends> is a comma-separated list of unique IDs (<User> ID) corresponding to the friends of the user.
Note that the friendships are mutual (i.e., edges are undirected): if A is friend with B then B is also friend with A. The data provided is consistent with that rule as there is an explicit entry for each side of each edge. So when you make the pair, always consider (A, B) or (B, A) for user A and B but not both.
Output: The output should contain one line per user in the following format: <User_A>, <User_B><TAB><Mutual/Common Friend Number>
where <User_A> & <User_B> are unique IDs corresponding to a user A and B (A and B are friend). < Mutual/Common Friend Number > is total number of common friends between user A and user B.
 
2. Find the friends pair with maximum number of mutual friends. Output the result in descending order.

3. List the 'user id' and 'rating' of users that reviewed businesses classified as “Colleges &
Universities” in list of categories.
4. List the business_id , full address and categories of the Top 10 businesses located in "NY" using the average ratings.
