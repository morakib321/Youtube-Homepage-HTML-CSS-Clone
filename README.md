<h1>YouTube Layout + Flex & Grid Practice</h1>

<p>
A small front-end practice project featuring a mini YouTube-style layout and three focused practice files for 
<strong>Flexbox</strong> and <strong>CSS Grid</strong>. The goal is to get comfortable with modern layout 
techniques and apply them in a slightly larger UI.
</p>

<hr>

<h2> Project Structure</h2>

<pre>
.
├── index.html               # YouTube-like layout (header, sidebar, responsive video grid)
├── youtube.css              # Styles for main layout (header/sidebar/grid responsiveness)
├── flex-practice.html       # Small Flexbox experiments (axes, flex, gaps, alignment)
├── flexbox.html             # Simple top nav built with Flexbox (Home • Search • Download)
└── grid-practice.html       # Grid experiments (fixed tracks, fr units, gaps)
</pre>

<ul>
  <li>Main page markup and Google Fonts setup are in <code>index.html</code></li>
  <li>Responsive grid, header/sidebar, tooltips, and media queries live in <code>youtube.css</code></li>
  <li>Flexbox fundamentals are explored in <code>flex-practice.html</code></li>
  <li>Compact Flexbox navbar layout is in <code>flexbox.html</code></li>
  <li>Grid experiments (columns, gaps, fractions) are in <code>grid-practice.html</code></li>
</ul>

<hr>

<h2> Getting Started (Local)</h2>

<ol>
  <li>Clone the repository:
    <pre><code>git clone &lt;your-repo-url&gt;.git
cd &lt;your-repo-folder&gt;</code></pre>
  </li>
  <li>Open any HTML file in your browser (no build step required):
    <ul>
      <li><code>index.html</code> → full YouTube-style page</li>
      <li><code>flex-practice.html</code> → Flexbox demos</li>
      <li><code>flexbox.html</code> → Flexbox navbar</li>
      <li><code>grid-practice.html</code> → Grid demos</li>
    </ul>
  </li>
  <li>If using VS Code, install <strong>Live Server</strong> to enable auto-reload.</li>
</ol>

<hr>

<h2> What This Project Demonstrates</h2>

<ul>
  <li><strong>Flexbox:</strong> row layouts, flexible columns with <code>flex: 1/2</code>, 
      spacing with <code>justify-content</code>, and vertical centering with <code>align-items</code>.</li>
  <li><strong>CSS Grid:</strong> fixed + fractional columns, responsive card grids, and grid gaps.</li>
  <li><strong>Responsive layout:</strong> media queries adapt the video grid from 2 → 3 → 4 columns.</li>
  <li><strong>Sticky UI regions:</strong> fixed header and sidebar similar to YouTube.</li>
  <li><strong>Accessibility basics:</strong> focus styles on inputs and sufficient color contrast.</li>
</ul>

<hr>

<h2> Notes & Assets</h2>

<ul>
  <li>Google Fonts (Roboto) is used in <code>index.html</code></li>
  <li>Icons and images are referenced from <code>icons/</code>, <code>thumbnail/</code>, and <code>profile photo/</code> folders. Replace or update assets as needed.</li>
  <li>Ensure CSS paths in <code>index.html</code> match the location of <code>youtube.css</code>.</li>
</ul>

<hr>

<h2> Implementation Highlights</h2>

<ul>
  <li><strong>Header:</strong> Flexbox layout with logo/menu, search, and action icons.</li>
  <li><strong>Sidebar:</strong> Fixed vertical navigation with hover effects.</li>
  <li><strong>Video cards:</strong> Thumbnail with duration label and info grid (avatar + details).</li>
</ul>

<hr>

<h2> How to Customize</h2>

<ul>
  <li>Tweak media queries in <code>youtube.css</code> to adjust grid columns.</li>
  <li>Replace content, titles, channels, and view counts directly in <code>index.html</code>.</li>
  <li>Experiment with Flexbox gaps, grid auto-rows, and CSS variables for colors or spacing.</li>
</ul>

<hr>

<h2>To-Do / Future Ideas</h2>

<ul>
  <li>Add a mobile menu toggle for the sidebar.</li>
  <li>Implement a search results page or filter chips.</li>
  <li>Extract shared styles into variables or utility classes.</li>
  <li>Add basic keyboard navigation for header icons/tooltips.</li>
</ul>

<hr>

<h2>License</h2>
<p>
This is a practice project for learning purposes. You may use it freely for study or portfolio projects.
</p>
