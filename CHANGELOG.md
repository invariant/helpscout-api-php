## 1.2.7 (April 4, 2013)

* Updated examples.
* When creating a conversation or thread, the createdAt property is correctly set now.
* Fixed a typo that was causing 'closedBy' to not be set properly on a conversation.

## 1.2.6 (March 28, 2013)

* Fixed an issue where a conversation created without a customer id was causing an exception.

## 1.2.5 (March 1, 2013)

* Updated with support for new line item properties (actionType and actionSourceId). See [developer docs](http://developer.helpscout.net/) for more information.

## 1.2.4 (January 21, 2013)

* Conversations and threads can now be marked as 'imported' at creation time.

## 1.2.3 (December 7, 2012)

* Added 'phone' conversation and thread type.

## 1.2.2 (November 5, 2012)

* Added a method to retrieve a list of customers for a mailbox.

## 1.2.1 (October 31, 2012)

* Added examples for write endpoints (create/update conversation, create/update customer).

## 1.2.0 (October 25, 2012)

* Conversation write endpoints added. Conversations can now be created, updated, and deleted. Threads can be created, and attachments can be created and associated with a thread.
* Customer write endpoints added. Customers can now be created and updated.
* Customers can now be searched for by name and/or email.

## 1.1.0 (October 16, 2012)

* Conversation now has a type property that specifies if the type of conversation is an 'email' or 'chat'.
* UserRef and CustomerRef have been removed and replaced by a PersonRef. The PersonRef class has a 'type' property that specifies if the person is a 'user' or a 'customer'.
* A new Chat thread type was added.