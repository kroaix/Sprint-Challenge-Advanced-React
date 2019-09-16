- [x] Why would you use class component over function components (removing hooks from the question)?

  I feel like class components have more control over state and what happens in the lifecycle of your app. You get to specifically say what you want to happen when the component mounts, what happens when it updates, and what happens when it unmounts.

- [x] Name three lifecycle methods and their purposes.

  componentDidMount: Part of the mounting phase, the method gets called as soon as the render() method is called initially. Creates our app/loads components.

  componentDidUpdate: This method is not called for the first render() like componentDidMount. Instead, it is invoked immediately after an update occurs to state.

  componentWillUnmount: Invoked immediately before a component unmounts/dies. It is in this method that you will cleanup any ongoing tasks.

- [x] What is the purpose of a custom hook?

  Custom hooks are reusable! They keep your code DRY. You build the hook out yourself and it allows you to apply non-visual behaviour and stateful logic throughout your components using the same, reusable custom hook. 

- [x] Why is it important to test our apps?

  I kept asking myself this at first and wondering if I will ever actually implement these tests on my own. Last night when I was finishing up my app I had applied styling and ran my tests one last time and the tests passed BUT came up with a bunch of error messages. I was using Material-UI for the first time and I had accidentally nested a h6 within a paragraph. I fixed that and the errors went away. Testing is a great way to avoid these accidents and helps us to find bugs and fix them before deploying our apps.