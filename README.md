# nft-drop
## Intro 
This project is my REACTION to the video 
<div>
  <a href="https://www.youtube.com/watch?v=wtjHSOhi4LA"><img src="https://img.youtube.com/vi/wtjHSOhi4LA/0.jpg" alt="IMAGE ALT TEXT"></a>
</div>

## Detail 
### React/Next.js 
#### React Hook
  - ✅ The useEffect Hook allows you to perform side effects in your components.
        </br>Some examples of side effects are: fetching data, directly updating the DOM, and timers.
    
        Replace class, componentDidMount, componentDidUpdate
  - ✅ The React useState Hook allows us to track state in a function component.
      </br>State generally refers to data or properties that need to be tracking in an application.
<br/> Example:        
```js
const [brand, setBrand] = useState("Ford");
const [model, setModel] = useState("Mustang");
```

https://www.w3schools.com/react/react_usestate.asp 👆

 ### Solana
 1. IDE
    https://beta.solpg.io
2. Libs
    https://www.metaplex.com
#### NFT
    include 2 files: 0.jpg, 0.json
    <br/>The json file is where you define NFT's properties: hat, ears, eyes (blue)
    
    
<img src="https://github.com/HaLamUs/nft-drop/blob/main/assets/monkey.png" width="400">
  https://opensea.io/assets/solana/214gAnKQUfFoD6AW4aRtETJNA73WZ3mYUybMEp3PDqHy 👆

#### How are NFTs stored?
We do not save the raw/origin png to Solana chain, we use a 3rd party (candy machine) for hosting assets and keep the id (reference keys) in blockchain

<img src="https://github.com/HaLamUs/nft-drop/blob/main/assets/blockchain.png" width="400">

#### Sugar candy 
  With this powerful tool, you can guard your NFT 

  Example: Add start/end date, bot tax

  📌 Remember to change the wallet payment with your address.

  https://docs.metaplex.com/developer-tools/sugar/guides/sugar-for-cmv3#bot-tax
  
---
## Author

This repo was developed by [@lamha](https://github.com/HaLamUs). 
Follow or connect with me on [my LinkedIn](https://www.linkedin.com/in/lamhacs). 

## License
[MIT licensed.](LICENSE)
