In this Series ie project I have tried to study State Based Application
    - How does state works
    - What are the use of the States
    - 

## One Rule for State
### Never Update any variabe from state directly !
    - Instead use methods 

State syntex 
- const [count , setCount] = useState(0);// "0" is the default value ie can be boolean- true, can be an object 
- Refer App.js of this project for the basic State usage 

<button onClick = {()=> count >= 10 ? "": setCount(count + 1)} >Increase Counter</button>
