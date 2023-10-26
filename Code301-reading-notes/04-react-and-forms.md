# react-and-forms

#### What is a ‘Controlled Component’?

Components (typically form components) that have their state and behavior controlled by the parent component.

#### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

As soon as they enter them, to provide a “single source of truth” as per controlled components.

#### How do we target what the user is entering if we have an event handler on an input field?

event.target.value

#### Why would we use a ternary operator?

To shorten _if_ statements into one line of code.

#### Rewrite the following statement using a ternary statement:

_if(x===y){_
_console.log(true);_
_} else {_
_console.log(false);_
_}_

x === y ? console.log(true) : console.log(false)
