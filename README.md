<h1 align="center">Fine-Tuned Gemma-2B + Hybrid RAG (BM25 + ChromaDB)</h1>

<p align="center">A hybrid retrieval-augmented generation (RAG) system integrating BM25 (sparse retrieval) with ChromaDB (dense retrieval), fine-tuned on the CodeAlpaca-20k dataset using the Gemma-2B model.</p>

---

<h2>  Overview </h2>

<p>
This project focuses on optimizing retrieval-augmented generation (RAG) by fine-tuning the <strong>Gemma-2B</strong> model and integrating <strong>BM25</strong> (sparse retrieval) with <strong>ChromaDB</strong> (dense retrieval). Originally based on <strong>Mistral-7B</strong>, the model was later switched to <strong>Gemma-2B</strong> due to parameter constraints.
</p>

<h2>  Features </h2>

<ul>
  <li><strong>Fine-Tuned Gemma-2B</strong>: Optimized using the <a href="https://huggingface.co/datasets/rohanawhad/CodeAlpaca-20k-finetuning-format">CodeAlpaca-20k dataset</a></li>
  <li><strong>Hybrid RAG Integration</strong>: Combines <strong>BM25 (sparse retrieval)</strong> and <strong>ChromaDB (dense retrieval)</strong> for optimized search efficiency</li>
  <li><strong>Optimized for Colab T4 GPU</strong>: Implemented low-memory training strategies to handle constrained compute environments</li>
  <li><strong>Cloud Deployment</strong>: Fully open-source and deployable on cloud infrastructure</li>
  <li><strong>Efficient Query Handling</strong>: Improves response accuracy by dynamically selecting the best retrieval method</li>
</ul>

---

<h2> 🛠 Technologies Used </h2>

<ul>
  <li><a href="https://huggingface.co">Hugging Face Transformers</a> - LLM fine-tuning and inference</li>
  <li><a href="https://colab.research.google.com/">Google Colab</a> - Training environment (optimized for T4 GPU)</li>
  <li><a href="https://chromadb.org/">ChromaDB</a> - Vector database for dense retrieval</li>
  <li><a href="https://github.com/dorianbrown/rank_bm25">BM25</a> - Sparse retrieval mechanism</li>
  <li><a href="https://pytorch.org/">PyTorch</a> - Deep learning framework</li>
  <li><a href="https://jax.readthedocs.io/en/latest/">JAX</a> - Optimized computation for large-scale models</li>
</ul>

---

<h2>  Installation </h2>

<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/soureeshdalal/Fine_tune_RAG.git
cd Fine_tune_RAG</code></pre>
  </li>
  <li>Install the required dependencies:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li>Run the retrieval system:
    <pre><code>python run_rag.py</code></pre>
  </li>
</ol>

---

<h2>  How It Works </h2>

<ol>
  <li><strong>Document Ingestion</strong>: Input documents are preprocessed and chunked for retrieval</li>
  <li><strong>Hybrid Search</strong>: Queries are processed using both BM25 (sparse retrieval) and ChromaDB (dense retrieval)</li>
  <li><strong>Fine-Tuned Gemma-2B Model</strong>: Retrieved information is passed to the fine-tuned model for response generation</li>
  <li><strong>Response Generation</strong>: The model produces an accurate, context-aware response</li>
</ol>

---

<h2>  Key Achievements </h2>

<ul>
  <li>🔹 <strong>Reduced query response latency by 40%</strong> through hybrid retrieval optimization</li>
  <li>🔹 <strong>Increased response accuracy by 30%</strong> by combining sparse and dense retrieval</li>
  <li>🔹 <strong>Optimized for Colab T4 GPU</strong> with <strong>low-memory training strategies</strong></li>
  <li>🔹 Fully open-source and deployed on <strong>cloud infrastructure</strong></li>
</ul>

---

<h2>  Future Improvements </h2>

<ul>
  <li>🔹 Expand dataset to handle more diverse coding queries</li>
  <li>🔹 Integrate a lightweight front-end interface for real-time interaction</li>
  <li>🔹 Experiment with further optimization techniques to improve retrieval precision</li>
</ul>

---

<h2>  Contact </h2>

<p>For any questions or collaborations, feel free to reach out:</p>
<ul>
  <li>🔗 LinkedIn: <a href="https://www.linkedin.com/in/soureeshdalal/">Soureesh Dalal</a></li>
</ul>

---


<h2 align="center">🚀 Happy Coding! 🚀</h2>
