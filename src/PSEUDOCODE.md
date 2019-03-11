Step 1:
use the command yarn from the root directory to install your node_modules. Then yarn start. - Done

Step 2:
There are a couple of spots in the application where you'll need to write the code to get the application functional.

These spots are in reducers/index.js, actions/index.js, and components/Counter.js.

reducers
Our reducer that handles our two action cases:
increment and decrement. It receives the state
of our redux store, along with an action created
by our action creator.
Set the count increment and decrement for each case - Done

actions
Our action creators will return
an action packet that our reducer will
receive.
Note that the action creator is not at all
responsible for handling any of the actual
logic of updating the central Redux store. That
is left to the reducer(s).

- Pass in count to the increment and decrement functions - Done
- return type and payload objects for both functions - Done

components

- Pass the count props to increment and decrement buttons
