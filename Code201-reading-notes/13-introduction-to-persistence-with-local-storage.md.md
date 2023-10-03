# introduction-to-persistence-with-local-storage

#### Why would a developer use local storage for a web application?

When we want to store data for a user but don't want them to sign up for an account/store information on a server. It's better to keep a "key" on the user’s computer and use it when the user returns.

#### What information should not be stored in local storage?

Personally identifiable information, authentication tokens, API keys.

#### Local storage can store what type of data? How would you convert it to that type before storing?

Strings only. You would convert any other data type or object to string by using the native _JSON.stringify()_ and _JSON.parse()_ methods.
