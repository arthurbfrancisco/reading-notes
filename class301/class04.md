# Reading 04: React(React and Forms)

## What is a ‘Controlled Component’?

A Controlled Component in React is like a form where React keeps track of what's being typed in real time. This means React always knows what's in the form and can react to it.

### Should we wait to store the user's responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

We should update the state as soon as users type something into the form. It's like taking notes while someone is talking, instead of trying to remember everything they said and writing it down at the end. This way, we can immediately tell them if they made a typo or if their password is too short, for example.

### How do we target what the user is entering if we have an event handler on an input field?

In React, we can use something called event.target.value to know what a user is typing into an input field. It's as if every time a user types a letter, that letter is sent to our event handler. This way, we can keep track of what's being typed in real time.
ex:
class MyForm extends React.Component {
  state = {
    value: ''
  };

  handleChange = (event) => {
    this.setState({value: event.target.value});
  }

  render() {
    return (
      form>
        label>
          Name:
          input type="text" value={this.state.value} onChange={this.handleChange} />
        /label>
        input type="submit" value="Submit" />
      /form>
    );
  }
}

### Why would we use a ternary operator?

A ternary operator can be used as a shortcut for an if-else statement. It's a one-liner that tests a condition and returns one value if the condition is true and another if the condition is false. It makes the code cleaner and easier to read when dealing with simple conditional statements.

#### The if-else statement you provided can be rewritten with a ternary operator like this:

console.log(x === y ? true : false);

Here's how it works:

x === y is the condition we're testing.
If x === y is true, then true will be logged.
If x === y is false, then false will be logged.