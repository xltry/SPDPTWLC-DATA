# SPDPTWLC-DATA
The experimental instances  of the selective pickup and delivery problem with time window and loading cost (SPDPTWLC) , which are generated based  on a classical data generator presented in (Ropkeand Cordeau, 2009; Ropke et al., 2007) for the PDPTW.  The coordinates of customers are randomly selected within a [0,50]×[0,50] square according to a uniform distribution and the depot is located in (25,25). The number of available vehicles| K| is set to be N/4, where N is the number of customers.  Same as the Ropke’s generator, the planned time horizon of route T is set by 600, the vehicle capacity Q is 20 and the width of time window w is 60 for all the test instances.   The time window of each customer is constructed by randomly selecting ai in [0,T−di,n+1] and setting bi=ai+w.  
According to the number of pickups and deliveries, the instances in our experiment can be divided into nine classes, which have 10, 20, 30 pickups and 20, 40, 60 deliveries, respectively.Each class has five instances and, hence, there are 45 instances in total. An extra class of instances with 10 pickups and 10 deliveries are designed for the branch-and-cut algorithm realized by the ILOG CPLEX to compare and illustrate the efficiency of proposed branch-and-price-and-cutalgorithm.  
