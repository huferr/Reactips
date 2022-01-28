### Questions about React JS

Here you can see some questions about React/javascript environment!

<details>
<summary><strong>What is JSX?</strong></summary>
  <br>
  <p>JSX is a syntax extension to JavaScript. In other words, JSX stands to Javascript XML. It allows us to write HTML in React.</p>
  <br>
 <p>With JSX, you can create HTML elements just by writing it with its base shape:</p>
 
  ```js
  const title = <h1>Crazy</h1>;

  ReactDOM.render(title, document.getElementById('root'));
  ```
  <p>Now, look how we would have to do without using JSX:</p>
  
  ```js
  const parag = React.createElement('p', {}, 'I do not use JSX!');

  ReactDOM.render(parag, document.getElementById('root'));
  ```
  
  <p>When using JSX, you can put any javascript expressions or variables inside the curly braces in your code:</p>
  
   ```js
  const userName = "Hugo";
  const title = <h1>Hello, {userName}!</h1>;
  ```
  <p>Other example:</p>
  
  ```js
  const handleSubtitle = () => <h2>Subtitle</h2>;
  const component = () => (
    <div>
      <h1>Here is a function call in JSX:</h1>
      {handleSubtitle()}
    </div>
  )
  ```
</details>
<details>
  <summary><strong>What is Virtual DOM?</strong></summary>
  <br>
  <p>The virtual DOM is a representation of a UI (HTML Elements === React Components) which is kept in memory and synced with the real DOM.</p>
  <p>I am still working in that question...wait a sec.</p>
</details>
