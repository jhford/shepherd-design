Components
==========

The major systems of shepherd are:
- Event Server
- Dispatcher
- Runner

Shepherd also uses Reddis queues and MongoDB storage for data storage
and queueing operations.

<pre>   
   E -----> D -----> R
              <-----
</pre>
