# React Details

* How does React app start up?
<p>
Ans: 
<ul>
<li>All of your projects's js file are bundled together into a single file, then placed on to a server, where user can access it from server</li>
<li>User makes a request to the server and gets an HTML file + the bundle</li>
<li>User's browser execute your code.</li>
    <ul>
        <li>Find the div with id of 'root' in the DOM</li>
        <li>Tell react to take controll of that element</li>
        <li>Tell react to get JSX from the App component, turn it into HTML and show it in the root</li>
    </ul>
</ul>
</p>