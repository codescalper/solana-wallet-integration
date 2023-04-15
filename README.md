<h1>Solana Wallet Integration</h1>

 <p> This is a sample project demonstrating how to integrate Solana wallets into a React app using the Solana Wallet Adapter. </p>

 <h2>Tech Stack</h2>

 <ul> <li>React</li> <li>Next.js</li> <li>Solana Wallet Adapter</li> <li>Solana Web3.js library</li> <li>Solana Wallet Adapter React UI library</li>

 <h2>Getting Started</h2>

 <p> To get started, you'll need to have Node.js and npm installed. You can download them from the <a href="https://nodejs.org/">official website</a>. </p>

 <ol> <li>Clone the repository:</li> </ol>

 <pre><code>$ git clone https://github.com/codescalper/solana-wallet-integration.git</code></pre>

 <ol start="2"> <li>Change into the project directory:</li> </ol>

 <pre><code>$ cd solana-wallet-integration</code></pre>

 <ol start="3"> <li>Install dependencies:</li> </ol>

 <pre><code>$ npm install</code></pre>

 <p> After the installation is complete, you can start the development server by running: </p>

 <pre><code>$ npm run dev</code></pre>

 <p> This will start the development server at <code>http://localhost:3000</code>. You can access the app by visiting this URL in your web browser. </p>
 
<h2>Packages Used</h2> 
<ul> 
<li>@solana/web3.js</li>
 <li>@solana/wallet-adapter-backpack</li>
<li>@solana/wallet-adapter-base</li>
<li>@solana/wallet-adapter-react</li>
<li>@solana/wallet-adapter-react-ui</li>
<li>@solana/wallet-adapter-wallets</li>
<li>next</li> <li>react</li> 
<li>react-dom</li> </ul>





 <h2>Working of the Project</h2>

 <p> This project demonstrates how to integrate Solana wallets into a React app using the Solana Wallet Adapter. The app is built with Next.js, a popular React-based framework for building server-side rendered (SSR) web applications. </p>

 <p> The project contains the following components: </p>

 <ul> 
 <li>
 <code>index.tsx</code>: The main app component that renders the AppBar and PingButton components.
 </li>
  <li><code>_app.tsx</code>: The custom Next.js App component that initializes the Solana Wallet Adapter and sets up the connection to the Solana network.
  </li>
  <li><code>AppBar.tsx</code>:The component that renders the application header, including the Solana logo, the app title, and the WalletMultiButton component provided by the Solana Wallet Adapter React UI library.
  </li>
  <li><code>PingButton.tsx</code>: The component that contains the logic for sending a "ping" transaction to the Solana network using the user's selected wallet.</li>  <li><code>WalletContextProvider.tsx</code>: The component that sets up the connection to the Solana network and initializes the available wallets for the Wallet Provider component.</li> 
   </ul>
<h2>Contribution</h2>

 <p> If you would like to contribute to this project, please fork the repository, make your changes, and create a pull request. We welcome all contributions, including bug fixes and feature enhancements. </p>
 <h2>Issues</h2>

 <p> If you encounter any issues while using this project, please create an issue on the <a href="https://github.com/codescalper/solana-wallet-integration/issues">GitHub repository</a>. </p>
