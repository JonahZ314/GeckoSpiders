# GeckoSpiders 
<h3>Xing Tao Shi, Taylor Wong, Chris Yu</h3>
<h2>interface Deque[E] </h2> Implemented in class QQ (Doubly-Linked Node Based)
  <h3>Methods</h3>
    <p>
    <b>addFirst(E x): </b>
      enqueues item to the front of the queue
    </p>
    <p>
    <b>addLast(E x): </b>
      enqueues item to the end of the queue
    </p>
    <p>
    <b>removeFirst(): </b>
      dequeues the first item in the queue
      </p>
    <p>
    <b>removeLast(): </b>
      dequeues item from the end of the queue
    </p>
    <p>
    <b>peekFirst():</b>
      returns the first item in the queue so you can take a "peek" at it
      </p>
    <p>
    <b>peekLast(): </b>
      return the last item in the queue so you can take a "peek" at it
    </p>

<h3>
Deque is implemented using doubly-linked nodes because the nodes have pointer to 
what is in front and behind, allowing us to implement the methods above in O(1) runtime.      
</h3>

## ERRORS FIXED

We resolved an error where in removeLast(), if degree is bigger than size 1, it will set front.getNext() to null which should be _end.setNext(null) (line 109).

<br>
<br>
<br>
<br>
* Special thanks to QQ and CrispySpoon for the helpful feedback! *
