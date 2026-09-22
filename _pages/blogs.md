---
title: "Blogs"
permalink: /blogs/
layout: splash
---

<!-- Custom CSS for Blog Page -->

<!-- Include custom CSS -->
<style>
  /* Main page styling */
  .blogs-page {
    font-family: 'Arial', sans-serif;
    background-color: #f9f9f9;
    padding: 40px 20px;
  }

  /* Title and intro text */
  .blogs-title {
    font-size: 36px;
    text-align: center;
    margin-bottom: 20px;
    color: #333;
    font-weight: bold;
  }
  .intro-text {
    font-size: 18px;
    color: #555;
    text-align: center; /* Text aligned to the center */
    line-height: 1.6;
  }

  /* Blog Grid styling */
  .blog-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    margin-top: 40px;
  }

  /* Blog Card styling */
  .blog-card {
    background-color: white;
    border-radius: 10px;
    overflow: hidden;
    width: 22%; /* Adjust width to make them fill the space */
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    padding: 20px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    text-decoration: none !important;
    color: inherit;
    cursor: pointer;
  }

  .blog-card,
  .blog-card:visited,
  .blog-card:hover,
  .blog-card:focus,
  .blog-card * {
    text-decoration: none !important;
  }

  .blog-card:hover,
  .blog-card:hover * {
    text-decoration: none !important;
  }

  .blog-card:hover {
    transform: translateY(-8px) scale(1.03);
    box-shadow: 0 12px 28px rgba(0, 0, 0, 0.15);
  }

  .blog-img {
    width: 100%;
    height: 200px; /* Fixed height */
    object-fit: cover; /* This will crop the image to fit the container without stretching */
    margin-bottom: 15px; /* Add space below the image */
  }

  .blog-card h3 {
    font-size: 22px;
    color: #333;
    font-weight: bold;
    margin: 0;
    transition: color 0.2s ease;
    text-decoration: none !important;
  }

  .blog-card:hover h3 {
    color: #0073e6;
    text-decoration: none !important;
  }

  .excerpt {
    font-size: 16px;
    color: #777;
    line-height: 1.5;
    margin-top: 10px;
    flex-grow: 1;
    text-decoration: none !important;
  }

  /* Categories section */
  .categories {
    text-align: center;
    margin-top: 60px;
    font-size: 20px;
    font-weight: bold;
    color: #333;
  }

  .categories h2 {
    margin-bottom: 18px;
  }

  .categories ul {
    display: flex;
    justify-content: center;
    gap: 22px;
    list-style: none;
    padding: 0;
    flex-wrap: wrap;
  }

  .categories li {
    display: flex;
    align-items: center;
    justify-content: center;
    min-width: 140px;
    min-height: 70px;
    padding: 10px 18px;
    background-color: #f5f5f5;
    border-radius: 20px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.06);
    font-size: 1.05rem;
    font-weight: 600;
    color: #222;
    text-align: center;
    transition: background 0.3s, color 0.3s, box-shadow 0.3s;
    margin-bottom: 10px;
    line-height: 1.2;
  }

  .categories li:hover {
    background-color: #0073e6;
    color: #fff;
    box-shadow: 0 4px 16px rgba(0,115,230,0.12);
  }

  /* Contribute section */
  .contribute {
    text-align: center;
    margin-top: 60px;
    font-size: 18px;
    font-weight: bold;
    color: #555;
  }

  .contribute a {
    color: #0073e6;
    text-decoration: none;
  }

  .contribute a:hover {
    text-decoration: underline;
  }

  /* Mobile responsiveness */
  @media (max-width: 768px) {
    .blog-card {
      width: 48%;
    }
    .categories ul {
      gap: 12px;
    }
    .categories li {
      min-width: 110px;
      min-height: 60px;
      font-size: 0.98rem;
      padding: 8px 10px;
    }
  }

  @media (max-width: 480px) {
    .blog-card {
      width: 100%;
    }

    .blogs-title {
      font-size: 28px;
    }

    .intro-text {
      font-size: 16px;
      text-align: center;
    }
  }
</style>

<!-- Page Content -->

<!-- Page Content -->
<div class="blogs-page">
  <h1 class="blogs-title">Welcome to the Data Science Group Blogs</h1>

  <p style="text-align:center;">
    Dive into blogs and insights spanning Machine Learning, AI, Deep Learning, and Data Science.
    From beginner-friendly guides to deep technical explorations, discover content curated by the DSG. Stay tuned for updates and insightful posts from our talented team!
  </p>

  <div class="blog-grid">
    <a href="https://medium.com/@ydvaayan/activation-functions-b28c9083c0f3" class="blog-card" target="_blank" rel="noopener noreferrer">
      <img src="{{ site.baseurl }}/assets/images/blogs/activation/af.png" alt="Activation functions - Aayan Yadav" class="blog-img">
      <h3>Activation functions: Blogathon 2023</h3>
      <p class="excerpt">Find out how neural networks mimic the human brain to make decisions using activation functions, to help improve accuracy and learning efficiency.</p>
    </a>
    <a href="{{ site.baseurl }}/blogs/babysteps_tf1" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/babysteps_with_tf/babysteps_tf1.jpg" alt="Baby steps with Tensorflow #1" class="blog-img">
      <h3>Baby steps with Tensorflow #1</h3>
      <p class="excerpt">A beginner's guide to understanding TensorFlow and its application in deep learning.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/babysteps_tf2" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/babysteps_with_tf/babysteps_tf12.png" alt="Baby steps with Tensorflow #2" class="blog-img">
      <h3>Baby steps with Tensorflow #2</h3>
      <p class="excerpt">Continuing the exploration of TensorFlow, we dive deeper into its functionalities and practical applications.</p>
    </a>

  <a href="{{ site.baseurl }}/blogs/boosting" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/boosting/boosting_blog.png" alt="Boosting" class="blog-img">
      <h3>Boosting Decrypted</h3>
      <p class="excerpt">An introduction to boosting algorithms and how they improve model performance.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/chebnet" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/Chebnet.jpg" alt="ChebNet" class="blog-img">
      <h3>ChebNet: CNN on Graphs with Fast Localized Spectral Filtering</h3>
      <p class="excerpt">Exploring ChebNet, a new approach to graph neural networks using fast localized spectral filtering.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/clustering" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/clustering/clustering_blog.png" alt="Clustering" class="blog-img">
      <h3>Clustering Described</h3>
      <p class="excerpt">Learn about clustering techniques and how they're used to group similar data points in machine learning.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/cnn_with_tf" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/cnn_with_tf/cnn_with_tf1.jpg" alt="Convolutional Neural Network with TensorFlow Implementation" class="blog-img">
      <h3>Convolutional Neural Network with TensorFlow Implementation</h3>
      <p class="excerpt">Dive into the world of CNNs and discover how TensorFlow simplifies the implementation of deep learning models.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/data_science_congress" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/data_science_congress_blog.png" alt="Data Science Congress" class="blog-img">
      <h3>Data Science Congress. Something legendary.</h3>
      <p class="excerpt">Get the highlights from the most anticipated Data Science Congress. The future of AI is here, and it's legendary.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/decision_trees" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/dt/dt_blog.jpg" alt="Decision Trees Decoded" class="blog-img">
      <h3>Decision Trees. Decoded.</h3>
      <p class="excerpt">From theory to practice—unlock the secrets behind Decision Trees and how they power many machine learning algorithms.</p>
    </a>

  <a href="https://medium.com/@laabhanvi_j/decision-trees-7183a72c78d6" class="blog-card" target="_blank" rel="noopener noreferrer">
      <img src="{{ site.baseurl }}/assets/images/blogs/dt2025/decision_trees_2025.png" alt="Decision Trees - Laabhanvi Jain" class="blog-img">
      <h3>Decision Trees: Blogathon 2025</h3>
      <p class="excerpt">A Blogathon 2025 submission that goes deep into the maths and theory behind how a machine pick the best decision for a given problem through a series of questions</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/deepwalk" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/deepwalk/deepwalk_blog.png" alt="Understanding Deepwalk" class="blog-img">
      <h3>Understanding Deepwalk</h3>
      <p class="excerpt">Step into the realm of graph-based machine learning and see how DeepWalk revolutionizes the way we understand relationships in data.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/gat" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/gat/gat_blog.jpg" alt="Understanding GAT" class="blog-img">
      <h3>Understanding Graph Attention Networks (GAT)</h3>
      <p class="excerpt">Explore the world of Graph Attention Networks, where attention mechanisms meet graph theory to create smarter, more accurate models.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/gcn" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/gcn/gcn_blog.png" alt="Graph Convolutional Networks (GCN)" class="blog-img">
      <h3>A Review: Graph Convolutional Networks (GCN)</h3>
      <p class="excerpt">Uncover the power of Graph Convolutional Networks and their ability to learn from complex, structured data like never before.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/godnet" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/godnet/godnet_blog.jpg" alt="GodNet: Neural Network to Predict the Future" class="blog-img">
      <h3>GodNet: A Neural Network Which Can Predict Your Future?</h3>
      <p class="excerpt">Is this the next breakthrough or just a glimpse into AI's potential to predict the unpredictable? GodNet—more than just hype.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/graph_sage" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/graph_sage/graph_sage_blog.jpg" alt="Graph SAGE" class="blog-img">
      <h3>Graph SAGE (SAmple and aggreGatE) : Inductive Learning on Graphs</h3>
      <p class="excerpt">Discover how Graph SAGE is transforming inductive learning and enabling scalable, dynamic learning on graphs.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/hugo" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/hugo/hugo_blog.svg" alt="How To Setup Timer Hugo" class="blog-img">
      <h3>How To Setup Timer Hugo</h3>
      <p class="excerpt">Struggling with your Hugo setup? Get the step-by-step guide for setting up Timer Hugo for a smoother experience.</p>
    </a>

  <a href="https://summergeometry.org/sgi2025/ironing-out-wrinkles-with-mesh-fairing/" class="blog-card" target="_blank" rel="noopener noreferrer">
      <img src="{{ site.baseurl }}/assets/images/blogs/sgi/mesh_fairing.png" alt="Mesh Fairing - SGI 2025 at MIT" class="blog-img">
      <h3>Ironing Out Wrinkles with Mesh Fairing</h3>
      <p class="excerpt">Your triangle mesh looking wrinkled? Come explore how surface fairing smooths out those geometry wrinkles, making your meshes cleaner and more reliable for rendering and physics!</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/logistic" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/logistic/logistic_blog.jpg" alt="Logistic Regression Simplified" class="blog-img">
      <h3>Logistic Regression. Simplified.</h3>
      <p class="excerpt">Logistic Regression doesn't have to be intimidating. Get a simple, clear breakdown of this powerful algorithm.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/loss_function_optimization" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/loss_function_optimization/loss_function_optimization1.jpg" alt="Loss Functions and Optimization" class="blog-img">
      <h3>Loss Functions and Optimization Algorithms. Demystified.</h3>
      <p class="excerpt">Ever wondered why loss functions matter? Unravel the mystery behind them and learn how optimization drives machine learning models.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/placement_experience" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/placement_experience/placement_experience.jpg" alt="Placement Experience" class="blog-img">
      <h3>Placement Experience</h3>
      <p class="excerpt">Curious about what it takes to crack data science placements? Here's a first-hand experience that reveals all the secrets!</p>
    </a>

   <a href="https://medium.com/@advika9shilpi/principal-component-analysis-solution-to-dimensionality-curse-in-ml-fd318d763633" class="blog-card" target="_blank" rel="noopener noreferrer">
      <img src="{{ site.baseurl }}/assets/images/blogs/pca/pca.png" alt="PCA - Advika Sinha" class="blog-img">
      <h3>Principal Component Analysis: Blogathon 2024</h3>
      <p class="excerpt">Find out how PCA is like a data GPS, and the covariance matrix is the engine that drives it, crunching the numbers to reveal the hidden patterns!!</p>
    </a>

  <a href="https://stump-opal-f29.notion.site/Randomized-Smoothing-Smoothing-your-way-to-Certified-Robustness-a2e2a45134c9440bbfa0f951864c2f0f" class="blog-card" target="_blank" rel="noopener noreferrer">
      <img src="{{ site.baseurl }}/assets/images/blogs/randomized_smoothing/rs.png" alt="Randomized Smoothing" class="blog-img">
      <h3>Randomized Smoothing</h3>
      <p class="excerpt">Smoothe your way to Certified Robustness using adversarial machine learning, which is all about fortifying AI models against attacks, critical in shaping the future of safe, reliable AI.</p>
    </a>
  
  <a href="{{ site.baseurl }}/blogs/regularization" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/regularization/regularization_blog.png" alt="Regularization Clarified" class="blog-img">
      <h3>Regularization. Clarified.</h3>
      <p class="excerpt">Worried about overfitting? Learn how regularization techniques are the unsung heroes that make your models generalize better.</p>
    </a>

  <a href="https://medium.com/@agam.pandeyy/understanding-regularization-regressions-ebb1fe928c0d" class="blog-card" target="_blank" rel="noopener noreferrer">
      <img src="{{ site.baseurl }}/assets/images/blogs/regularization2023/regularization.png" alt="Understanding Regularization Algorithms in Regression-Agam Pandey" class="blog-img">
      <h3>Regularization Algorithms in Regression: Blogathon 2023</h3>
      <p class="excerpt">Regression models too rigid or too flexible? Learn how regularization strikes the perfect balance, enhancing model accuracy and generalization.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/roadmap" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/word_embedding/roadmap.png" alt="Roadmap to Data Science" class="blog-img">
      <h3>Roadmap To Data Science</h3>
      <p class="excerpt">From novice to expert—this roadmap will guide you through the essentials of Data Science. Start your journey now!</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/style_transfer_cnn" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/style_with_cnn/style_transfer_with_cnn1.gif" alt="Artistic Style Transfer with CNN" class="blog-img">
      <h3>Artistic Style Transfer with Convolutional Neural Network</h3>
      <p class="excerpt">Ever wanted to turn your photos into art? Learn how to use CNNs for artistic style transfer and create masterpieces with AI.</p>
    </a>

   <a href="{{ site.baseurl }}/blogs/svd" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/svd/svd_blog.png" alt="Singular Value Decomposition" class="blog-img">
      <h3>Singular Value Decomposition. Elucidated.</h3>
      <p class="excerpt">SVD might sound intimidating, but it's actually one of the most useful techniques in data science. Let's break it down and make it crystal clear.</p>
    </a>
    
  <a href="https://medium.com/@parthbadgujar/d1b670c79725" class="blog-card" target="_blank" rel="noopener noreferrer">
      <img src="{{ site.baseurl }}/assets/images/blogs/transformers/transformers.png" alt="Transformers Like Never Before! - Parth Badgujar" class="blog-img">
      <h3>Transformers Like Never Before: Blogathon 2023</h3>
      <p class="excerpt">Discover how Attention in transformers helps neural networks focus on important information, improving performance through queries, keys, and values.</p>
    </a>

  <a href="https://medium.com/@advika9shilpi/using-lora-to-train-llms-efficiently-c339eafc7f47" class="blog-card" target="_blank" rel="noopener noreferrer">
      <img src="{{ site.baseurl }}/assets/images/blogs/lora/lora.png" alt="Using LoRA to train LLMs efficiently" class="blog-img">
      <h3>Using LoRA to Train LLMs efficiently</h3>
      <p class="excerpt">Click to find out how LoRA revolutionizes fine-tuning for LLMs without compromising performance. </p>
    </a>

   <a href="{{ site.baseurl }}/blogs/word_embedding" class="blog-card">
      <img src="{{ site.baseurl }}/assets/images/blogs/word_embedding/word_embedding9.png" alt="Word Embedding" class="blog-img">
      <h3>Word Embedding</h3>
      <p class="excerpt">Words are more than just words—discover how word embeddings turn text into numerical representations for smarter machine learning models.</p>
    </a>
  </div>
<!-- 
  <div class="categories">
    <h2>Categories</h2>
    <ul>
      <li>Machine Learning</li>
      <li>Deep Learning</li>
      <li>Natural Language Processing</li>
      <li>Reinforcement Learning</li>
      <li>Data Preprocessing</li>
      <li>Computer Vision</li>
      <li>Time Series Analysis</li>
      <li>AI in Industry</li>
    </ul>
  </div> -->

  <div class="contribute">
    <p>If you're a Data Science enthusiast and want to contribute your knowledge and ideas, feel free to get in touch! We are always looking for new authors who can share their insights and experiences in the world of Data Science and AI.</p>
    <p><a href="{{ site.baseurl }}/contact">Contact Us</a> to contribute!</p>
  </div>
</div>
