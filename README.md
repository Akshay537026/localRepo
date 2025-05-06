<h1>📁 My First Git Project</h1>

<p>
I created a local repository using Git on my machine. In this project, I first added some content using Visual Studio Code (VS Code).
</p>

<h2>🔧 Git Initialization and Local Setup</h2>

<p>To initialize the Git repository and commit the initial files, I ran the following commands in the terminal:</p>

<pre><code>git init
git add .
git commit -m "Initial commit"
</code></pre>

<h2>🌐 Connecting to GitHub</h2>

<p>
After creating a new repository on GitHub (without adding a description or README to avoid merge conflicts), I linked my local repository using:
</p>

<pre><code>git remote add origin &lt;repository-link&gt;
</code></pre>

<p>Then, I pushed my local code to GitHub using:</p>

<pre><code>git push -u origin main
</code></pre>

<h2>💡 Additional Notes</h2>

<ul>
  <li>I did not initialize a README on GitHub to prevent conflicts with my local files.</li>
  <li>The <code>-u</code> flag in <code>git push -u origin main</code> sets the upstream, so future <code>git push</code> and <code>git pull</code> commands work without specifying the branch name.</li>
  <li>My local project is now fully synced with GitHub, and I can continue development with version control.</li>
</ul>
