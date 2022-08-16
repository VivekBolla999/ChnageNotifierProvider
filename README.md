                              State management in flutter

Change notifier : A class called ChangeNotifier sends change notifications to its listeners. This implies that you can call the notifyListeners() method of a class that has been extended or combined with a ChangeNotifier to subscribe to changes in that class. The widgets that are subscribed to this class will be informed to rebuild by this function.

State notifier : On the other hand, StateNotifier is an immutable state management solution where the state can be directly changed within the notifier. It is an amplification of the ValueNotifier. Also, StateNotifier is an independent package that doesn’t rely on Flutter, unlike ChangeNotifier, and it can be used within your Dart projects as well.



Difference between change notifier and state notifier:
       Change notifier                                                            state notifier

Mutable state(objects are mutable)                                       immutable(objects are immutable)(modifies the state)
Dependent on flutter                            		                 independent on flutter
Time complexity is higher                   		                     time complexity is lower
In the long run it is hard to manage code                                easy to manage code in long run
Manually call notifylisteners()                                          automatically calls
