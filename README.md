Since the free version of Postman has no git integration I just chose to just export the test collection and upload it to github manually.

  - Import TestCollections.postman_collection.json in Postman (upper left corner)
  - Navigate to the collections tab and hover over TestCollections
  - Click the arrow and run
  - Clicking on CreateTest, ReadTest ect. Allows you to inspect pre and post request javascript

How would you run your tests in a DevOps pipeline?
  - There is a way to run Postman tests in a DevOps pipeline. Using newman, a tool to run exported Postman collections in the command line. So basically any sort of unit testing software that supports running tests from the command line will work.
  - It's also possible to integrate newman with your continuous integration servers and build systems.
  - Simply add it to an existing pipeline or create a new one for it.
