<article class="markdown-body">
  <h1>GPT-4 Turbo Coding Agent</h1>
  
  <p>A Streamlit application that uses AI to analyze coding problems, generate Python solutions, and execute them in a sandboxed environment.</p>
  
  <h2>Overview</h2>
  
  <p>This application acts as a coding assistant that can:</p>
  <ol>
    <li>Extract coding problems from uploaded images using Gemini's vision capabilities</li>
    <li>Generate optimized Python solutions using GPT-4 Turbo</li>
    <li>Execute code in a sandboxed environment using E2B Code Interpreter</li>
    <li>Provide execution results and error analysis</li>
  </ol>
  
  <h2>Features</h2>
  
  <ul>
    <li><strong>Image Recognition</strong>: Upload images containing coding problems for automatic extraction</li>
    <li><strong>Text Input</strong>: Enter coding problems directly via text area</li>
    <li><strong>Solution Generation</strong>: AI-powered generation of optimized Python solutions</li>
    <li><strong>Secure Execution</strong>: Run code in an isolated sandbox environment</li>
    <li><strong>Execution Analysis</strong>: View execution results, logs, and generated files</li>
    <li><strong>Error Handling</strong>: Intelligent error analysis and timeout protection</li>
  </ul>
  
  <h2>Requirements</h2>
  
  <p>The application requires the following API keys:</p>
  <ul>
    <li>OpenAI API Key (for GPT-4 Turbo)</li>
    <li>Google Gemini API Key (for vision capabilities)</li>
    <li>E2B API Key (for sandboxed code execution)</li>
  </ul>
  
  <h2>Installation</h2>
  
  <ol>
    <li>Clone this repository</li>
    <li>Install dependencies:</li>
  </ol>
  
  <pre><code>pip install streamlit agno e2b_code_interpreter pillow</code></pre>
  
  <h2>Usage</h2>
  
  <ol>
    <li>Run the Streamlit app:</li>
  </ol>
  
  <pre><code>streamlit run app.py</code></pre>
  
  <ol start="2">
    <li>Enter your API keys in the sidebar</li>
    <li>Choose one of the following:
      <ul>
        <li>Upload an image containing a coding problem</li>
        <li>Type your coding problem in the text area</li>
      </ul>
    </li>
    <li>Click "Generate & Execute Solution" to process</li>
    <li>View the solution and execution results</li>
  </ol>
  
  <h2>Limitations</h2>
  
  <ul>
    <li>Code execution timeout is set to 30 seconds</li>
    <li>Only one input method (image or text) can be used at a time</li>
    <li>The sandbox environment is reset for each execution</li>
  </ul>
  
  <h2>Dependencies</h2>
  
  <ul>
    <li>Streamlit: Web application framework</li>
    <li>Agno: AI agent framework</li>
    <li>E2B Code Interpreter: Sandboxed code execution environment</li>
    <li>PIL (Pillow): Image processing library</li>
  </ul>
  
  <h2>Security Note</h2>
  
  <p>All code is executed in an isolated sandbox environment for security.</p>
</article>
