A deadlock is created using NSOperationQueue. The cocept was, I created two operations and one NsOPerationQueue.

Made both operations dependent on each other to make circular wait(Necessary condition for deadlock).

Added both operations to operation queue and yey deadlock occurred.
