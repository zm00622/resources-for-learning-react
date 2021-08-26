# resources-for-learning-react
Resources for Learning React

__________________________________________

**Lifecycle Methods Explained with Hooks**

https://www.youtube.com/watch?v=Zz9pLellSQA

**componentDidUpdate**

useEffect(() = > {

  console.log("We have run the useEffect hook");
  
}); 

(Notice there is no array in the parameters, just the arrow function!)

**componentDidMount**

useEffect(() = > {

  console.log("We have run the useEffect hook");
  
} []);

(Notice there IS an array in the parameters!)

**componentWillUnmount**

useEffect(() = > {

  console.log("We have run the useEffect hook");
  
    return () => {
    
      console.log("The component has unmounted");
      
    };
    
} []);

__________________________________________

<img src="https://github.com/zm00622/resources-for-learning-react/blob/main/Lifecycle%20Methods%20vs.%20Hooks.png?raw=true"></img>
