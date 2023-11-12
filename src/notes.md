https://youtu.be/wfMtDGfHWpA?si=ZtTaU-aSxCJtVX5-
https://legacy.reactjs.org/docs/composition-vs-inheritance.html#so-what-about-inheritance

we use compisiton or inheritance to make our code DRY aka not reusing code over and over 

components w/ props-- using props instead of hard coding data makes it so we can call certian props we need, components are the base unit for code reuse in react, to make the the same HTML data to show on the dom jsut like using a function to call somethign over and over. 

Almost always use composition over inhertiance 


--- FROM REACT TEAM 
At Facebook, we use React in thousands of components, and we haven’t found any use cases where we would recommend creating component inheritance hierarchies.

Props and composition give you all the flexibility you need to customize a component’s look and behavior in an explicit and safe way. Remember that components may accept arbitrary props, including primitive values, React elements, or functions.

If you want to reuse non-UI functionality between components, we suggest extracting it into a separate JavaScript module. The components may import it and use that function, object, or class, without extending it.

