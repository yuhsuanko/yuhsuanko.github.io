---
layout: page
title: Projects
subtitle: Data Science Projects
---

<p style="max-width: 720px; margin: 1.5rem auto; text-align: center; font-size: 1.1rem; color: #444;">
  I specialize in analyzing and leveraging data from diverse sources and formats, including structured tables, unstructured text, images, and real-time streams, to extract insights and solve real-world problems.<br><br>
  Here is a collection of machine learning and AI projects that encompass large language models, computer vision, machine learning, fraud detection, and applied analytics. Each project is designed with practical impact and relevance to industry needs in mind.
</p>


<!-- Top Navigation Buttons -->
<div id="project-nav" style="display: flex; justify-content: center; gap: 1.5rem; margin-top: 2rem; margin-bottom: 2rem; flex-wrap: wrap;">
  <a href="#genai" class="project-anchor-btn">Generative AI</a>
  <a href="#vision" class="project-anchor-btn">Computer Vision</a>
  <a href="#risk" class="project-anchor-btn">Machine Learning & Analytics</a>
</div>

<!-- Styles -->
<style>
  html { scroll-behavior: smooth; }

  .project-anchor-btn {
    padding: 8px 16px;
    font-size: 1rem;
    border: 1px solid #ccc;
    border-radius: 6px;
    text-decoration: none;
    color: #333;
    background-color: #f8f8f8;
    transition: all 0.2s ease;
  }
  .project-anchor-btn:hover {
    background-color: #333;
    color: white;
    border-color: #333;
  }

  .project-group { margin-top: 3rem; }

  .project-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 1.5rem;
    margin-bottom: 2rem;
    box-shadow: 0 1px 4px rgba(0,0,0,0.06);
    background: #fff;
  }

  .project-card h3 {
    margin-top: 0;
    margin-bottom: 0.3rem;
  }

  .project-card em {
    color: #666;
    font-size: 0.95rem;
  }

  .project-card ul {
    margin: 0.5rem 0 0.8rem 1rem;
  }

  .project-card p {
    margin: 0;
    color: #444;
  }

  .github-link-box {
    margin-top: 1.2rem;
    padding: 10px 16px;
    border: 1px solid #ddd;
    border-radius: 8px;
    background-color: #f9f9f9;
    display: inline-block;
    transition: background-color 0.2s ease;
  }

  .github-link-box a {
    text-decoration: none;
    font-weight: 600;
    color: #333;
    display: flex;
    align-items: center;
    gap: 8px;
    font-size: 1rem;
  }

  .github-link-box:hover {
    background-color: #f0f0f0;
  }

  .github-link-box .arrow {
    font-size: 1.1rem;
    color: #333;
  }

  .project-image {
  display: block;
  max-width: 240px;
  margin: 0 auto 1.2rem auto;
  border-radius: 6px;
  }

.project-card {
  max-width: 900px;
  margin: 0 auto 40px;
  background-color: #fff;
  border-radius: 16px;
  box-shadow: 0 4px 16px rgba(0,0,0,0.06);
  overflow: hidden;
  padding: 24px;
}

.project-content {
  display: flex;
  flex-direction: row;
  gap: 24px;
  align-items: flex-start;
}

.project-image-box {
  flex: 0 0 260px;
}

.project-image {
  width: 100%;
  height: auto;
  border-radius: 12px;
  object-fit: cover;
}

.project-info {
  flex: 1;
}

/* 📱 Responsive */
@media (max-width: 768px) {
  .project-content {
    flex-direction: column;
  }

  .project-image-box {
    width: 100%;
  }
}

</style>


<!-- Section: Generative AI -->
<div class="project-group">
  <h2 id="genai">Generative AI & Large Language Models</h2>

  <div class="project-card">
    <img src="/assets/img/ai-analytics.png" alt="AI Trend Analysis" class="project-image">
    <h3>Multi-Industry AI Trend Analysis</h3>
    <p><em>Apr 2025 – May 2025</em></p>
    <ul>
      <li>Analyzed 200K+ AI-related articles using GPT-4, BERTopic, BERT sentiment models, and NER.</li>
      <li>Identified industry trends and automation risks, achieving 71% accuracy in risk prediction.</li>
    </ul>
    <p><strong>Key Skills:</strong> GPT-4, BERTopic, BERT, Sentiment Analysis, NER, Visualization</p>

    <div class="github-link-box">
      <a href="https://github.com/yuhsuanko/Multi-Industry_AI_Trend_Analysis" target="_blank">
        <i class="fab fa-github"></i> View on GitHub <span class="arrow">→</span>
      </a>
    </div>
  </div>

  </div>


  <div class="project-card">
    <img src="/assets/img/crewai.png" alt="CrewAI Logo" class="project-image">
    <h3>AI Agents for Healthcare Research</h3>
    <p><em>Mar 2025 – Apr 2025</em></p>
    <ul>
      <li>Designed a generative agent system for coming up ideas for healthcare research.</li>
      <li>Implemented CrewAI’s Planner–Analyst–Critic multi-agent architecture with in-context learning.</li>
    </ul>
    <p><strong>Key Skills:</strong> LLMs, CrewAI, Adaptive Reasoning, Conversational AI, Prompt Design</p>

    <div class="github-link-box">
      <a href="https://github.com/yuhsuanko/AI-Agents_Generate-Healthcare-Research" target="_blank">
        <i class="fab fa-github"></i> View on GitHub <span class="arrow">→</span>
      </a>
    </div>
  </div>


  <div class="project-card">
    <h3>Instruction-Tuned LLMs for Fraud Detection</h3>
    <p><em>Feb 2025 – Mar 2025</em></p>
    <ul>
      <li>Explored narrative alignment of LLMs using instruction-tuned fraud prompts and Ollama evaluation.</li>
      <li>Simulated model explainability for fraud predictions through prompt-engineered storytelling.</li>
    </ul>
    <p><strong>Key Skills:</strong> LLMs, Ollama, Instruction Tuning, Fraud Analytics, Narrative Generation</p>

    <div class="github-link-box">
      <a href="https://github.com/yuhsuanko/Instruction-Tuned-LLMs-for-Fraud-Detection" target="_blank">
        <i class="fab fa-github"></i> View on GitHub <span class="arrow">→</span>
      </a>
    </div>

  </div>
</div>

<!-- Section: Computer Vision -->
<div class="project-group">
  <h2 id="vision">Computer Vision & Image Modeling</h2>

  <div class="project-card">
    <h3>Face-to-BMI Prediction System</h3>
    <p><em>Apr 2025 – May 2025</em></p>
    <ul>
      <li>Trained CNN and ViT models on facial images for BMI regression (Pearson r = 0.68).</li>
      <li>Used VGG-Face, ResNet50, ViT; experimented with ensemble and gender as features.</li>
    </ul>
    <p><strong>Key Skills:</strong> CNN, ViT, Regression, Facial Features, Ensemble Modeling</p>

    <div class="github-link-box">
      <a href="https://github.com/yuhsuanko/FaceToBMI-CNN" target="_blank">
        <i class="fab fa-github"></i> View on GitHub <span class="arrow">→</span>
      </a>
    </div>

  </div>

  <div class="project-card">
    <h3>Detection of AI-Generated Human Images</h3>
    <p><em>Feb 2025 – Mar 2025</em></p>
    <ul>
      <li>Used DINOv2 and CNNs to distinguish synthetic faces from real ones (70% accuracy).</li>
    </ul>
    <p><strong>Key Skills:</strong> Deepfake Detection, CNNs, DINOv2, Binary Classification</p>

    <div class="github-link-box">
      <a href="https://github.com/yuhsuanko/RealOrAI-FaceClassifier" target="_blank">
        <i class="fab fa-github"></i> View on GitHub <span class="arrow">→</span>
      </a>
    </div>

  </div>
</div>

<!-- Section: Risk & Analytics -->
<div class="project-group">
  <h2 id="risk">Machine Learning Modeling & Analytics</h2>

  <div class="project-card">
    <h3>Credit Card Fraud Detection</h3>
    <p><em>May 2025 – Jun 2025</em></p>
    <ul>
      <li>Engineered fraud signals across 780K+ transactions including CVV mismatch, velocity, time windows.</li>
      <li>Trained LightGBM with SMOTE, achieving 0.54 recall and 0.73 ROC AUC.</li>
    </ul>
    <p><strong>Key Skills:</strong> LightGBM, SMOTE, Fraud Features, Class Imbalance, Evaluation Metrics</p>

    <div class="github-link-box">
      <a href="https://github.com/yuhsuanko/Credit-Card-Fraud-Detection" target="_blank">
        <i class="fab fa-github"></i> View on GitHub <span class="arrow">→</span>
      </a>
    </div>

  </div>

  <div class="project-card">
    <h3>Spotify Music Recommendation System</h3>
    <p><em>Feb 2025 – Mar 2025</em></p>
    <ul>
      <li>Used K-Means + XGBoost + NLP (TF-IDF, Word2Vec) to personalize playlist suggestions.</li>
    </ul>
    <p><strong>Key Skills:</strong> Recommender Systems, Clustering, XGBoost, Word2Vec, TF-IDF</p>

    <div class="github-link-box">
      <a href="https://github.com/yuhsuanko/Spotify-Music-Recommendation-System" target="_blank">
        <i class="fab fa-github"></i> View on GitHub <span class="arrow">→</span>
      </a>
    </div>

  </div>

  <div class="project-card">
    <h3>Chicago Crime Prediction</h3>
    <p><em>Oct 2024 – Dec 2024</em></p>
    <ul>
      <li>Analyzed city crime trends and built logistic regression to predict arrests (81% AUC).</li>
    </ul>
    <p><strong>Key Skills:</strong> Logistic Regression, AUC, Spatial-Temporal Modeling</p>

    <div class="github-link-box">
      <a href="https://github.com/yuhsuanko/Chicago-Crime-Analysis-and-Arrest-Prediction" target="_blank">
        <i class="fab fa-github"></i> View on GitHub <span class="arrow">→</span>
      </a>
    </div>

  </div>

  <div class="project-card">
    <h3>AML Transaction Monitoring – E.SUN Bank</h3>
    <p><em>Jul 2023 – Sep 2024</em></p>
    <ul>
      <li>Deployed Isolation Forest and LightGBM to detect third-party payment fraud, cutting false positives by 30%.</li>
    </ul>
    <p><strong>Key Skills:</strong> AML, LightGBM, Isolation Forest, Risk Modeling, Financial Compliance</p>
  </div>
</div>