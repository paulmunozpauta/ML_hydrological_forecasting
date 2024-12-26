<h1>Machine Learning Hydrological Forecasting</h1>

<p>This repository provides hands-on Jupyter Notebooks for building machine learning models for hydrological forecasting. The project environment is managed using Poetry to ensure consistency across platforms.</p>

<hr>

<h2>📁 Project Structure</h2>

<pre>
ml-hydrological-forecasting/
├── notebooks/              # Jupyter notebooks
│   ├── example_notebook.ipynb
├── pyproject.toml          # Poetry dependency file
├── poetry.lock             # Poetry lock file (auto-generated)
├── README.md               # Project documentation
</pre>

<hr>

<h2>🚀 How to Run the Project</h2>

<p>You can run this project by either <strong>cloning the repository</strong> or <strong>copying the folder</strong> from GitHub to your computer.</p>

<h3>🛠️ Prerequisites</h3>
<ol>
  <li><strong>Install Miniconda or Anaconda</strong>:
    <ul>
      <li>Download <a href="https://docs.conda.io/en/latest/miniconda.html" target="_blank">Miniconda</a> (lightweight) or <a href="https://www.anaconda.com/" target="_blank">Anaconda</a> (full version).</li>
      <li>Follow the installation instructions for your operating system (macOS, Linux, or Windows).</li>
      <li>Verify that Conda is installed by running:
        <pre><code>conda --version</code></pre>
      </li>
    </ul>
  </li>
  <li><strong>Install Python 3.7.16</strong>:
    <ul>
      <li>If you have Conda installed, create an environment with Python 3.7.16 using:
        <pre><code>conda create --name IUPWARE python=3.7</code></pre>
      </li>
    </ul>
  </li>
</ol>

<hr>

<h2>🏗️ Step 1: Create a Conda Environment</h2>

<p>To isolate your project environment and ensure compatibility, follow these steps:</p>

<h3>For macOS, Linux, and Windows Users</h3>
<ol>
  <li>Create a new Conda environment named <code>IUPWARE</code> with Python 3.7:
    <pre><code>conda create --name IUPWARE python=3.7</code></pre>
  </li>
  <li>Activate the environment:
    <pre><code>conda activate IUPWARE</code></pre>
  </li>
</ol>

<hr>

<h2>🏗️ Step 2: Install Poetry</h2>
<ol>
  <li>Install Poetry in the Conda environment:
    <pre><code>pip install poetry</code></pre>
  </li>
  <li>Verify the installation:
    <pre><code>poetry --version</code></pre>
  </li>
</ol>

<hr>

<h2>🏗️ Step 3: Install Project Dependencies</h2>

<h3>Option 1: Clone the Repository</h3>
<ol>
  <li>Open a terminal or command prompt.</li>
  <li>Clone the repository to your computer:
    <pre><code>git clone https://github.com/yourusername/ml-hydrological-forecasting.git
cd ml-hydrological-forecasting
    </code></pre>
  </li>
</ol>

<h3>Option 2: Copy the Folder</h3>
<ol>
  <li>Download or copy the project folder from GitHub to your computer.</li>
  <li>Navigate to the copied folder in your terminal:
    <pre><code>cd /path/to/copied-folder/ml-hydrological-forecasting</code></pre>
  </li>
</ol>

<h3>Install Dependencies</h3>
<ol>
  <li>Install the dependencies listed in <code>pyproject.toml</code>:
    <pre><code>poetry install</code></pre>
  </li>
  <li>Activate the Poetry-managed environment:
    <pre><code>poetry shell</code></pre>
  </li>
</ol>

<hr>

<h2>📊 Step 4: Run Jupyter Notebooks</h2>
<ol>
  <li>Start the Jupyter Notebook server:
    <pre><code>jupyter notebook</code></pre>
  </li>
  <li>Open the notebook file (e.g., <code>example_notebook.ipynb</code>) in your browser and run the cells.</li>
</ol>

<hr>

<h2>❓ Troubleshooting</h2>
<ul>
  <li><strong>Python Version Issues</strong>: Make sure you have Python 3.7.16 installed. Check your version:
    <pre><code>python --version</code></pre>
  </li>
  <li><strong>Dependencies Not Installing</strong>: If Poetry isn’t installing the libraries, clear the Poetry cache and try again:
    <pre><code>poetry cache clear pypi --all
poetry install
    </code></pre>
  </li>
  <li><strong>Environment Not Activating</strong>: Ensure you’re in the correct directory where <code>pyproject.toml</code> is located.</li>
</ul>

<hr>

<h2>⚙️ What Does This Project Use?</h2>
<p>The environment is managed using Poetry. The dependencies are:</p>
<ul>
  <li><code>scikit-learn 1.0.2</code>: Machine learning algorithms</li>
  <li><code>numpy ^1.21.5</code>: Numerical computations</li>
  <li><code>pandas ^1.3.5</code>: Data manipulation</li>
  <li><code>matplotlib ^3.5.3</code>: Data visualization</li>
  <li><code>jupyter ^1.0.0</code>: Interactive notebooks</li>
</ul>
<p>All dependencies are listed in the <code>pyproject.toml</code> file.</p>

<hr>

<h2>📜 License</h2>
<p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for details.</p>