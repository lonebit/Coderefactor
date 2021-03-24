# Coderefactor
First of all its very dificult to review any code without background knowledge of the project

But there some things that can be optimized

1- Use laravel default log
2- Use request validation before sending data to repository or before saving it into db
3- Seprate Service for notification
4 - in notification also remove curl call make another service for it
5- use laravel ORM and relatioships where you can i know db query is fast but query is not complex we can use ORM.
6 - use event and listener for notifications also we can use observer somewhere
7 - when there not complex query or a one or two liner we dont need repository function for it


